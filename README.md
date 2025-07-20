# Tone_State_EO

This repository aims to support study the differences in tone on State Election Officials social media accounts by creating graphics and content for the study. To do so, it uses two methodologies.

1. **Clustering**: This methodology is used to cluster the social media posts of the State Election Officials into groups based on their tone. We do so using different methods, comparing them, and also using different features like party affiliation or battleground status.
2. **Word Counts**: This methodology is used to first classify the type of words using POS tagging, hand-picking the potential biased words from the following word types: adjectives, nouns, auxiliary verbs, verbs, pronouns, and others, andf then looking for differences in use based on the same features utilized for clustering.

**Note:** This repository does not comment on the results of the analysis, but rather provides the code and data used to perform the analysis of the two methodologies mentioned above.

## Structure:
The repository is structured as follows:

🚫 - Part of .gitignore and/or not included in the repo
```
.
├── 📁 Clustering
│   ├── clustering.ipynb
│   ├── getting_embeddings.ipynb
│   └── 📁 graphs_clustering # Contains the graphs created with the clustering analysis
├── 📁 Explanation
│   ├── Explanation.md # Contains the explanation of the project and repo
│   └── Plan.qmd # contains the initial plan for the project
├── LICENSE
├── 📁 POS_tagging
│   ├── Exploration_of_process # Contains the exploration of the POS tagging process
│   ├── POS_tagging_lists.ipynb # Contains the creation of the POS tagging lists
│   └── word_counts # Contains the word count graphs for the biased words
├── README.md
└── 📁 data
    ├── Cleaning_files
    ├── bias_words # contains the final file of the biased words
    ├── clean (🚫)
    └── raw (🚫)
```