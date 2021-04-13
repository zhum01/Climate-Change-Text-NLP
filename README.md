# Using Sentiment Scores for Stance Detection On Climate-Change Statements

This project tests out using sentiment scores as an additional feature to the pooled output of BERT (from Transformers library) to do stance detection on sentences related to climate change.

# Data 

All data were obtained from Luo et al., 2020 (https://arxiv.org/abs/2010.15149) 

The data set contains 2,050 global-warming-related sentences scraped from online news articles and labeled with {agree, disagree, neutral} with respect to the target opinion: "Climate change/global warming is a serious concern" (see Luo et al., 2020 for more details, such as distribution of news sources and methodology for labeling).


# Code

There are 2 notebooks, 1 for EDA (W266_finalProject_EDA_climatChangeText.ipynb) and 1 for modeling (W266_finalProject_Modeling_climateChangeText.ipynb). 

Run the EDA notebook first, which includes calculating sentiment scores and saving them to disk so they can be loaded in to use for the modeling notebook.
