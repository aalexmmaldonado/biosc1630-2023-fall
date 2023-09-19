(activity:method-recommendation)=
# Method recommendation

**Total duration:** 140 minutes

## Objective

Students will practice critical evaluation and decision-making in the context of computational biology method selection.

## Context

In this activity, you will be a junior researcher tasked with helping a senior researcher with their project.
They have just sequenced the genome of a recently unearthed microorganism with a high-impact publication in the works.

To bolster the impact of this paper, the senior researcher wants to annotate the function of these proteins accurately.
We have access to the amino acid sequences of numerous proteins.
Obtaining 3D protein structures has been challenging.
Only a few poor-quality crystallographic structures were possible.
Experimental assays would be the next step, but it is time-consuming, and we are worried about someone else publishing these results first.

The senior researcher has asked you to recommend an *in silico* method to annotate these proteins.
Your recommendation should be scientifically sound and practical for this research article.
However, they have asked you to drop everything and provide them with a recommendation within an hour to avoid being scooped.

:::{caution}
This type of situation is, unfortunelty, common.
:::

## Form groups

**Duration:** 1 minute

Have the students split up into groups of two or three.
Ensure at least one student per group has access to the internet via a laptop.

## Article background

**Duration:** 44 minutes

In a real-life scenario, you would search for and identify methods yourself.
For this activity, the instructor has selected two articles for your consideration.

(activity:method-recommendation:paper-a)=
**A.** Bileschi, M. L., Belanger, D., Bryant, D. H., Sanderson, T., Carter, B., Sculley, D., ... & Colwell, L. J. (2022). Using deep learning to annotate the protein universe. *Nature Biotechnology, 40*(6), 932-937. DOI: [10.1038/s41587-021-01179-w](https://doi.org/10.1038/s41587-021-01179-w)

(activity:method-recommendation:paper-b)=
**B.** Gligorijević, V., Renfrew, P. D., Kosciolek, T., Leman, J. K., Berenberg, D., Vatanen, T., ... & Bonneau, R. (2021). Structure-based protein function prediction using graph convolutional networks. *Nature communications, 12*(1), 3168. DOI: [10.1038/s41467-021-23303-9](https://doi.org/10.1038/s41467-021-23303-9)

Not all students may have the background to digest these papers quickly.
The instructor can optionally provide useful background on the following topics to get everyone up to speed.

- [Gene ontology](https://geneontology.org/docs/ontology-documentation/),
- [Enzyme Commission (EC) numbers](https://enzyme.expasy.org/enzyme_details.html)
- [Pfam (now InterPro)](https://www.ebi.ac.uk/interpro/),
- [CAFA challenge](https://biofunctionprediction.org/cafa/),
- [Graph neural networks](https://distill.pub/2021/gnn-intro/),
- [Convolutional neural networks](https://saturncloud.io/blog/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way/),
- [Recurrent neural networks](https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/),
- [One-hot encoding](https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/).

## Presentation

**Preparation:** 25 minutes

**Slots:** 6 minutes per group

Each group will prepare a **five-minute presentation** to the "senior researcher" recommending one of the two papers above.
There will be time for questions afterward.
The class will be roughly split into supporters of [paper A](activity:method-recommendation:paper-a) and [paper B](activity:method-recommendation:paper-b).
Here is some information to help you prepare your presentation.

- **Purpose:**
  The senior researcher has asked you to recommend one of these two methods.
  Your recommendation should be clearly stated, with enough supporting evidence motivating your selection to convince the senior researcher they can trust your conclusions.
- **Audience background:**
  Assume that your audience is the senior researcher and some of their collaborators.
  They are all experimental biologists who will be familiar with gene ontology, biochemistry, protein structure, and biological assays for protein function annotation.
  Methods for *in silico* protein function annotation will be entirely new for them.
  Terms like "machine learning," "neural network," and "classifiers" are familiar, but they do not know what or how it works.
- **Technology:**
  You will make your presentation in a shared [Google Drive](https://www.google.com/drive/) folder.

<!-- ### Example

Below is a presentation for a different paper.

- Sanderson, T., Bileschi, M. L., Belanger, D., & Colwell, L. J. (2023). ProteInfer, deep neural networks for protein functional inference. *eLife, 12*, e80942. DOI: [10.7554/eLife.80942](https://doi.org/10.7554/eLife.80942)
 -->
