# SubtlePropaganda

This is a project repository for the DH-412 History and the Digital 2021 Course project that analyses the Hollywood and U.S. Department of Defence Collaboration.

## Abstract

The Department of Defense of the United States of America (DoD) and Hollywood have a long-lasting and gainful relationship. Given that they are leaders in their respective fields, it is of particular interest to understand the collaboration between them. This article investigates 1) What the DoD offers to the film industry and what they get back in return and 2) How does the DoD decide to assist a movie or not. The study uses text mining and analysis on the remarks made by DoD while deciding on the decision to support or not. The results show that Hollywood receives the support of costly and military-related paraphernalia from the top agencies of the DoD and in return sheds good light on DoD in the movies. Simultaneously, DoD cast off the movies that narrated uncomfortable stories about the United States.

## Members

- [Ravinithesh Reddy Annapureddy](ravinitheshreddy.github.io)
- [Yörüsün Asli](asli.yorusun@epfl.ch)

## Repo Organization

    ├── README.md <- The top-level README for developers using this project.
    |
    ├── data <- The final, canonical data sets placed in subdirectories used in the notebooks for analysis
    │
    ├── notebooks <- Jupyter notebooks used for analysis.
        ├──analysis_with_scattertext.ipynb: The notebook with analysis on the remarks and plots of movies using scattertext.
        ├──data_aggregation.ipynb: The notebook used to augment the original dataset with plots, release dates, generes.
        ├──movies_genres_assisstance.ipynb: The notebook with analysis on generes of the movies.
        ├──NER_analysis_remarks.ipynb: The notebook with the analysis on the remarks of the movies using Named Entity Recognition analysis.
        ├──scrape_reviews.ipynb: The notebook used to augment the dataset with user reviews of the movies on IMDB.
        ├──sentiment_analysis.ipynb: The notebook with analysis on the remarks and plots of movies using Aspect Based Sentiment Analysis.
        ├──support_production_assistance.ipynb: The notebook with basic EDA analysis on the dataset.
    │
    ├── Images <- The folder with images to be used in the report.
    │
    ├── plots <- The directory with subdirectories containing the plots produced as part of the analysis.
    │
    └── data_changes.md <- The markdown file detailing the changes made to the original dataset.
    |
    ├──TextPreprocessing.md <- The markdown file detaing the preprocessing steps performed on the text corpus.
    |
    └── report: The directory contains the report of the project.

## Installation

To run the various notebooks, the following packages are required in addition to standard libraries such as numpy, pandas, matplotlib, seaborn:

1. scattertext

```bash
pip install scattertext
```

2. Spacy

```bash
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_trf
```

3. PyTextRank

```bash
pip install pytextrank
```

4. Requests

```bash
pip install requests
```

5. Plotly

```bash
pip install plotly==4.14.3
```

The extension for jupyter lab/notebook should be installed following the instructions [here](https://plotly.com/python/getting-started/#jupyter-notebook-support)

5. WordCloud

```bash
pip install wordcloud
```

6. IMDbPY

```bash
pip install imdbpy
```

7. aspect_based_sentiment_analysis

```bash
pip install aspect-based-sentiment-analysis
```
