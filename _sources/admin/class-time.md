(class-time)=
# Is it time for class?

```{raw} html
<head>
    <script>

        function displayParagraph() {
            const options = {
                timeZone: 'America/New_York', // Change this to the desired time zone (e.g., 'Europe/London', 'Asia/Tokyo', etc.)
                hour: 'numeric',
                minute: 'numeric',
                weekday: 'long',
                day: 'numeric',
                month: 'long',
                year: 'numeric'
            };

            const now = new Date();
            const formatter = new Intl.DateTimeFormat('en-US', options);
            const formattedDate = formatter.format(now);

            const dayOfMonth = now.getDate();
            const month = now.getMonth(); // January = 0, February = 1, ..., December = 11

            // Check if it's a Wednesday (dayOfWeek === 3), the time is between 1:00 PM (13:00) and 3:30 PM (15:30),
            if (now.getDay() === 3 && ((now.getHours() === 13 && now.getMinutes() >= 0) || (now.getHours() > 13 && now.getHours() < 15) || (now.getHours() === 15 && now.getMinutes() <= 30)) && month >= 7 && month <= 11 && dayOfMonth >= 30 && dayOfMonth <= 12) {
                document.getElementById("paragraph").textContent = `Yes, but you should be paying attention to class.`;
            } else {
                document.getElementById("paragraph").textContent = `No.`;
            }
        }
    </script>
</head>
<body onload="displayParagraph()">
    <p id="paragraph""></p>
</body>
```
