# News Sentiment and Word Cloud Analysis Project

## Overview
This project analyzes news articles from the `News_Category_Dataset_v3.json` to extract sentiment and common themes over several years. Through sentiment analysis and word cloud generation, the project identifies patterns and trends in media coverage.

## Features
- Sentiment Analysis: Determine the general sentiment (positive, negative, neutral) of news each year.
- Word Cloud Generation: Visualize the most common words in the news for each year, highlighting prevalent topics.

## Data
- The dataset includes news articles categorized by date, headline, and description.
- Stopwords are filtered from `stopwords_en.txt` to ensure meaningful word frequency analysis.

## Results
Sentiment scores and word clouds from 2012 to 2022 reflect key annual news themes and public sentiment, influenced by major global events.

## Dependencies
- Python 3.8 or higher
- NLTK for natural language processing
- wordcloud for generating word clouds
- matplotlib for plotting images

## Installation
Install all dependencies using pip:

`pip install nltk wordcloud matplotlib`


## Usage
Execute the scripts to perform analysis:

`python sentiment_analysis.py`
`python word_cloud_generation.py`


## Contributions
To contribute to this project:
1. Fork it under your repository.
2. Create a new branch for your modifications.
3. Commit your changes.
4. Push to the branch.
5. Create a new Pull Request.

## License
This project is open-source and available under the MIT License.

## Acknowledgements
- The sentiment analysis was enhanced by insights from DataCamp's NLTK tutorials.
- The word clouds are generated using the `wordcloud` Python library.

