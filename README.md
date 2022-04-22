![image](https://i.imgur.com/cegca2P.png)


# Welcome to 1015_proj repository

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which uses machine learning to detect for depressive mood in social media posts. 

1. [Data Scraping, Cleaning and EDA](https://github.com/yipjunkai/1015_proj/blob/master/proj.ipynb) 
- Import twitter dataset from Kaggle
- Data scrapping of subreddits using Pushshift API
- Cleaning and merging of both dataset
- EDA (Wordcloud)
- Model generation
- Model training
- Model analysis
    
    
2. [Data Preparation, Model Creation and Training, Results Analysis](https://github.com/yipjunkai/1015_proj/blob/master/analysis.ipynb)
- Model importing
- Cleaning of testing dataset 
- Analysis of model on testing dataset
    
    
## Tech Stack
Data Handling/Visualisation: Python, numpy, seaborn, wordcloud, pandas
Data Scraping: Pushshift, Kaggle
Machine Learning: keras, tensorflow, nltk
Infrastructure: Google Colab


## Contributors

- @yipjunkai - Neural Network Creation/Training, Data Standardisation (Yip Jun Kai)
- @KayTeo - Data Scraping, Model Testing, Pre-Analysis/Post-Analysis (Keith Teo)
- @lumiinous - Data Scraping, Data Cleaning, Video + Slides Making, Post-Analysis (Tan Jian Wei)

## Problem Definition

- Are we able to predict depressive sentiment in social media posts?

## Models Used

1. Recurrent Neural Network

## Conclusion

- RNN needs relative position of words to understand meaning and predict sentiment
- Long Short Term Memory, an RNN variant, improves model accuracy by using memory state cells to learn word context
- Adding a dropout layer can reduce overfitting of models
- It is possible to predict the sentiment of posts with reasonable accuracy
- Depressive and non-depressive posts have similar words appearing in high frequency, making frequency analysis ineffective
- Long posts are strongly correlated with depressive sentiment
- High post frequency of user is correlated with low sentiment


## What did we learn from this project?

- Handling unstructued data resampling methods and the nltk package
- Recurrent Neural Networks, Keras and Tensorflow
- Using APIs to scrape data
- Collaborating through GitHub
- Concepts about Loss and Accuracy

## References

- <https://www.reddit.com/r/teenagers/>
- <https://www.reddit.com/r/depression/>
- <https://www.reddit.com/r/SuicideWatch/>
- <https://alexlenail.me/NN-SVG/index.html>
- <https://www.kaggle.com/datasets/kazanova/sentiment140>
- <https://doi.org/10.7759/cureus.8627>
- <https://www.straitstimes.com/singapore/health/imh-study-points-to-likely-increase-in-mental-health-issues-in-spore-amid-covid-19>
- https://github.com/pushshift/api
- https://psaw.readthedocs.io/en/latest/
- 
