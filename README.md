### Master's Dissertation

### Code for Master's Dissertation, 2023

---

This repository contains the code required to implement the analysis of a master's dissertation which applies a Latent Dirichlet Allocation (LDA) topic modeling to Portuguese Parliamentary debates.

The code allows us to depart from publicly available verbatim transcripts of debates to visualizations of the different topics that characterize the speech of different political parties in different legislative sessions.

The repository is structured as follows:
- "reading_files" allows us to read the publicly available files and integrate them into a single document.
- "processing_text" allows us to take the master file and convert it into Python objects which accurately represent the structure of the data.
- "other_formats" allows us to convert the data between document types and into structures that facilitate future analysis with panda data frames.
- "cleaning_text" takes the Python-readable data and cleans the actual text (remove punctuation, highlight political party).
- "descriptive_graphs" uses the clean dataset to display main metrics and visualizations of the words used by political parties.
- "making_word_lists" subdivides the dataset into specific datasets including words used by individual political parties and for specific legislative sessions, for future deep-dives.
- "lda" actually implements the LDA modeling to the data, leveraging the sub-datasets to identify topics and then compare.
