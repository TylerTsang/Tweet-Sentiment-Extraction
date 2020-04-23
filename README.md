# Tweet-Sentiment-Extraction

*"My ridiculous dog is amazing."* [sentiment: positive]

With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description?

What words in tweets support a positive, negative, or neutral sentiment? How can you help make that determination using machine learning tools? Your objective is to construct a model that can look at the labeled sentiment for a given tweet and figure out what word or phrase best supports it. 

## Data Description

* **textID**: The ID assigned to the corresponding tweet
* **text**: The text of the tweet
* **selected_text**: Unique to the training set words/phrases that were used to define sentiment
* **sentiment**: The label (positive, negative, neutral)

## Project Goal
The goal of the project is to cut through the noise of the twitter text and find the key word(s)/phrases that defines the sentiment of the tweet. An example would be the **selected_text** in the training data. The resulting output should look like:

```
id, selected_text
```

## Repository Structure

This repository is organized so that folders contain key files under their category:

* **data**: external, processed, and raw datasets
* **model**: predict and training models
* **notebooks**: eda (exploratory data analysis), poc (proof of concept), modelling, and evaluation
* **predictions**: prediction csv for submission
* **src**: source code for preparation, processing, and modelling
* **tests**: unittests, pytests, testing files

## Project Source

* [Kaggle - Tweet Sentiment Extraction](https://www.kaggle.com/c/tweet-sentiment-extraction/overview) - The competition cited for this project

## External Sources
* TBA
