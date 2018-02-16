# Resurrecting ancient proteins in Python

**Zach Sailer and Jeremy Anderson**

All living organisms evolved from an ancient set of ancestors. That means, the proteins that make up these organisms also evolved from an ancient set. Over a few billion years, evolution improvised, diversified, and specialized these proteins to meet life’s demands.

How did evolution do this? To explore this question, we need a window into the past.

Evolutionary biologists developed ancestral protein reconstruction—a computational method that infers ancient proteins from modern protein families. These ancestral proteins can be synthesized and characterized in a lab and compared to their modern counterparts. Using this information, we can identify key differences between ancestral and modern proteins that led to new evolutionary innovations.

In this talk, I will reconstruct an ancient protein in real-time. Together we will uncover the evolutionary past of steroid hormone receptors—a family of proteins that regulate reproduction and other biological processes in animals. This analysis will reveal an ancient split, which occurred ~450 million years ago, that led to the evolution of two important steroid receptor classes. We will reconstruct the last common ancestor before this split and compare it to modern proteins. Using this information, we will identify key changes and trace how these two receptor classes evolved.

Unfortunately, ancestral protein reconstruction is plagued by outdated software, many file formats, custom hacked scripts, and poor documentation. As a consequence, it is intimidating for beginners to learn and difficult for experts to reproduce. In the Harms lab, we saw this as a problem, so we developed Python APIs to make evolutionary biology simple, interactive and reproducible.

In this talk, I will highlight three Python packages that make our steroid receptor reconstruction simple. First, I will introduce PhyloPandas—a Python package that brings the Pandas DataFrame to phylogenetics. This dramatical simplifies phylogenetics by reading and writing phylogenetic data through a Pandas dataframe. It can then leverage the powerful data manipulation API in Pandas. Second, I will analyze the steroid receptor evolutionary tree using PhyloVega—a fast, interactive tree visualization package in Python. It translates tree data into Vega specification, a well-known visualization grammar, and generates interactive tree visualizations in Jupyter Notebooks. Finally, I will use a history-tracking phylogenetics API we created to reconstruct ancestral proteins reproducibly.

This talk will be directed at both evolutionary biologists and non-biologists. The pipeline will be reproducible from a single Jupyter Notebook. Attendees should leave with the confidence to reconstruct ancient proteins on their own. I also hope that this talk will launch a collaborative effort in evolutionary biology to improve reproducibility in this field.

Software for talk:
- PhyloPandas: www.github.com/Zsailer/phylopandas
- PhyloVega:  www.github.com/Zsailer/phylovega
- Phylogenetics: www.github.com/Zsailer/phylogenetics
