<h1 align="center">BIOSC 1630</h1>

<h3 align="center">Computational Biology Seminar</h3>

<p align="center">
    Fall 2023 •
    University of Pittsburgh •
    Department of Biological Sciences
</p>

<p align="center">
    <a href="https://github.com/aalexmmaldonado/reptar/blob/main/biosc1630-2023-fall" target="_blank">
        <img src="https://img.shields.io/github/license/aalexmmaldonado/biosc1630-2023-fall" alt="License">
    </a>
    <a href="https://github.com/aalexmmaldonado/biosc1630-2023-fall" target="_blank">
        <img src="https://img.shields.io/github/repo-size/aalexmmaldonado/biosc1630-2023-fall" alt="GitHub repo size">
    </a>
    <a href="https://github.com/aalexmmaldonado/biosc1630-2023-fall/actions/workflows/gh-pages.yml" target="_blank">
        <img src="https://github.com/aalexmmaldonado/biosc1630-2023-fall/actions/workflows/gh-pages.yml/badge.svg?branch=main" alt="GitHub repo size">
    </a>
    <a href="https://jupyterbook.org/en/stable/intro.html" target="_blank">
        <img src="book/_static/jb-badge.svg" alt="Jupyter book">
    </a>
</p>

Topics in computational biology will be explored using primary literature.
Students will present research articles orally and complete a series of writing assignments that will culminate in producing a literature review paper.

## Open education

We value accessible, open education that should be available to anyone who seeks it.
Thus, all materials for this course are released under the [Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) (CC-BY-SA-4.0) license.

## Feedback and reflection

[hypothes.is](https://web.hypothes.is/) is used to provide feedback, ask questions, and reflect on the course materials.
After making an account, you can annotate using the "Annotation sidebar" on the right-hand side of your screen.

## Building the website

This website is built using the [Jupyter Book](https://jupyterbook.org/en/stable/intro.html) framework.

First, you can create a Python virtual environment with `python3.11 -m venv ~/venvs/biosc1630-2023-fall`.
You can install Python 3.11 on Linux using `sudo apt-get install python3.11 python3.11-venv`.
Technically, other versions of Python3 should work, but I have not validated it.
Activate the new virtual environment with `source ~/venvs/biosc1630-2023-fall/bin/activate`.
You can check that it is using the correct Python version.

```bash
$ which python
/home/alex/venvs/biosc1630-2023-fall/bin/python
```

Install all dependencies with `pip install -U jupyter-book`.
Alternatively, use `pip install -r requirements.txt` from the [repository](https://github.com/aalexmmaldonado/biosc1630-2023-fall) to recreate the exact environment used to build the website.

Build the website by running the `build.sh` script after cloning the [repository](https://github.com/aalexmmaldonado/biosc1630-2023-fall).
You can now view the website by opening `book/build/html/index.html`.

Once you are finished you can `deactivate` the virtual environment.

```bash
$ deactivate
$ which python
/home/alex/miniconda3/bin/python
```

## Local copy

You can also get a local copy of this website.
Go to the [repository](https://github.com/aalexmmaldonado/biosc1630-2023-fall) and switch to the [`gh-pages` branch](https://github.com/aalexmmaldonado/biosc1630-2023-fall/tree/gh-pages).
Then click the green `< > Code` button and download a zip file containing an up-to-date compiled website.

Alternatively, you can click [this link](https://github.com/aalexmmaldonado/biosc1630-2023-fall/archive/refs/heads/gh-pages.zip) to automatically download this zip.

## Encryption

[git-secret](https://github.com/sobolevn/git-secret) is used to encrypt course materials that are in preparation.
Use [`git secret add`](https://sobolevn.me/git-secret/git-secret-add) to encrypt an untracked file.
This will add a line to `.gitignore` and `.gitsecret/paths/mapping.cfg` to mark that it should be a `.secret` file.
To stop encrypting the file, remove the lines in `.gitignore` and `.gitsecret/paths/mapping.cfg` and delete the `.secret` file.

[pre-commit](https://pre-commit.com/) hooks are used to ensure all desired files are encrypted before commits.
`git secret reveal` will allow you to decrypt these files if you have access.

## Acknowledgements

I sincerely thank the following individuals who have played a significant role in supporting the development of this course and my teaching.

- Emily Kerr for mentorship in pedagogy.
- Anita Mallinger for mentorship in writing and teaching.
- Kevin Randall for teaching advice and support.
- [Valerie Oke](https://www.biology.pitt.edu/person/valerie-oke) for providing previous course materials and guidance.
- [Jacob Durrant](https://www.biology.pitt.edu/person/jacob-durrant) for advice and support.
- [Ben J. Vincent](https://scholar.google.com/citations?user=BPoxstcAAAAJ) for providing previous course materials.
- [Katie Wetzel](http://www.hatfull.org/katie-wetzel) for providing previous course materials.
