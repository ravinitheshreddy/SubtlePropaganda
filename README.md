# SubtlePropaganda

This is a project repository for the DH-412 Semester project that analyses the Hollywood and US Department of Defence Collaboration.

## Project Description

The United States (US) is the military powerhouse of the world and at the same time, Hollywood is one of the oldest and largest film industries in the world. Therefore, examining the relationship between Hollywood and the Department of Defense (DoD) in the United States of America would explain what they are producing together. There have been large events in the past that have shown the effect of movies on the population. For example, after the movie Top Gun, produced by Jerry Bruckheimer and in collaboration with the Pentagon was released, the army set up recruitment counters outside the movie theatres to handle the numerous enlisting requests Keeping these aspects in mind, this research would help us understand the attitude of the DoD or the image that the DoD is willing to create in the public's mind in accepting/refusing to provide help to the movie makers.

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
