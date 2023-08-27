# Elizabethan Poor Laws - LDA Project

## Aim of the Project

This project aims to delve into the Elizabethan Poor Laws of 1601 to unpack the underlying religio-social and cultural frameworks. The goal is to provide a baseline understanding of how these historical laws have influenced or maintained contemporary socio-religious and cultural beliefs in the legal system. We investigate terms like "worthy" and "unworthy" poor, examine beliefs about poverty, and explore the institutional mechanisms these laws set up. For instance, localized funding mechanisms for the poor, the role of "Overseers," and financial structures like taxation are some of the key elements analyzed.

## Data Source

The text of the Elizabethan Poor Laws of 1601 was sourced from [Statutes.org.uk](https://statutes.org.uk/site/the-statutes/seventeenth-century/1601-43-elizabeth-c-2-act-for-the-relief-of-the-poor/).

## Citation

If you're looking to reference this work, please cite as follows:

```
Tauheeda Yasin Martin (2023). LDA Analysis of Elizabethan Poor Laws. ACLS-Mellon Postdoctoral Research, University of Texas at Austin in Sociology | Population Research Center. Available at GitHub repository: [URL of your GitHub Repo]
```

## Contact Information

- **Researcher**: Tauheeda Yasin Martin
- **Affiliation**: ACLS-Mellon Postdoctoral Researcher, University of Texas at Austin in Sociology | Population Research Center
- **Email**: Tauheeda.Yasin [at] austin [dot] Texas [dot] edu
- **Website**: [TauheedaYasinMartin.com](https://TauheedaYasinMartin.com)

## Contributors

Currently, this is a solo project by Dr. Tauheeda Yasin Martin.

## Initial Setup

1. **Environment**: Using Anaconda on the cloud.
2. **Install Libraries**: `conda install -c anaconda nltk scikit-learn pandas`

## LDA Analysis

1. **Data Preparation**: Loaded and cleaned data, removed stopwords.
2. **Feature Extraction**: Tokenization and Count Vectorization.
3. **Model Training**: Using LDA from scikit-learn.
4. **Parameter Tuning**: Adjusted number of topics and iterations for the LDA model.
5. **Topic Visualization**: Used pyLDAvis for visualization.

## Update Procedure

1. **Git Pull**: To fetch the latest changes.
   ```bash
   git pull origin main
   ```
2. **Make Changes**: Work on the project.
3. **Commit Changes**: Commit the updated files.
   ```bash
   git add .
   git commit -m "your commit message"
   ```
4. **Push Changes**: To update the repository.
   ```bash
   git push origin main
   ```
   
### Future Work

The aim is to extend this project by using the analysis from the LDA to explore further tools like Mermaid for visual mapping. The focus will be not only on sentiment and polarity but also on how these key terms have evolved and appear in modern legal codes. This will help trace the lineage and biases associated with terms like "unworthy" or "worthy" poor in contemporary law, especially focusing on financial and monetary sanctions.

### Dependencies

For reproducibility, the project used the following versions of libraries:

```
- nltk v3.6.2
- scikit-learn v0.24.2
- pandas v1.2.4
```

### Licensing

This project is licensed under the Creative Commons license, and open for collaboration. Please adhere to the license terms if you plan to use or modify any part of this project.

### Code Structure

- `.ipynb_checkpoints/`: Auto-saved files from Jupyter Notebook
- `LDA.ipynb`: Main notebook containing the Latent Dirichlet Allocation (LDA) analysis
- `Untitled.ipynb`, `Untitled1.ipynb`: Supplementary notebooks
- `untitled.py`: Additional Python script for data processing

## Methodology and Tools

### Latent Dirichlet Allocation (LDA)

- **Source Library**: [scikit-learn](https://scikit-learn.org/stable/)
- **Foundation Paper**: [Latent Dirichlet Allocation by David M. Blei, Andrew Y. Ng, Michael I. Jordan](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

#### Why LDA?

LDA was chosen for its effectiveness in topic modeling tasks and its widespread use in text analysis across various disciplines. It allows for the identification of hidden thematic structures in large datasets and is particularly useful for this project's focus on the socio-cultural dimensions within legal texts.

#### Steps in LDA Analysis

1. **Data Preparation**: Texts were cleaned and stopwords were removed.
2. **Feature Extraction**: Tokenization and Count Vectorization.
3. **Model Training**: Utilized scikit-learn's LDA implementation.
4. **Parameter Tuning**: Adjusted the number of topics and iterations based on model performance.
5. **Topic Visualization**: Employed pyLDAvis for a visual interpretation of topics.

#### Further Reading

- [Scikit-learn LDA documentation](https://scikit-learn.org/stable/modules/decomposition.html#latentdirichletallocation)
- [Introduction to Latent Dirichlet Allocation](https://medium.com/@lettier/how-does-lda-work-ill-explain-using-emoji-108abf40fa7d)

### Demonstrations

Coming soon...
### Acknowledgments

This project is a part of the ACLS-Mellon Postdoctoral Research. The underlying mechanism for the LDA is based on the scikit-learn library, and the structure for performing the LDA was inspired by . Special acknowledgment to OpenAI's ChatGPT for guidance in data analysis and project documentation. The methodology for LDA analysis was adapted from source and further guided by interactions with ChatGPT by OpenAI

### Citations

Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). "Latent Dirichlet Allocation". Journal of Machine Learning Research.

Griffiths, T. L., & Steyvers, M. (2004). "Finding scientific topics". Proceedings of the National Academy of Sciences.

scikit-learn Documentation on LDA
