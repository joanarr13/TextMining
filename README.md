
# Decoding the Rhythms of Emotion: A Sentimental Journey through Music Genres
## Text Mining Project

## Project Description
The aim of the project was to use the power of text mining techniques to discover the emotional background of songs through their lyrics, as well as develop a classification model to identify the genre of a song based on key words from the lyrics.

## Project Objective
As mentioned above, the project was divided into two main tasks:
- **Genre Identification**: training machine-learning models on a dataset containing song lyrics and their corresponding genres to accurately predict the song genre on unknown data.
- **Sentiment Analysis**: explore the emotional undertones of the songs of the dataset, in order to try to identify patterns (for example, predominant sentiments) in specific song genres. This part was more flexible and was guided with open-ended questions.

This project also had a competitive side, since the team had to submit the results of the machine-learning model into a Kaggle competition for posterior evaluation [Kaggle Competition](https://www.kaggle.com/competitions/decoding-emotion-from-music).

## Improvements

Although our study was able to reach enlightening conclusions, some further recommendations and improvements could be taking into account in the future: 
- **Expansion of Musical Genres**: the current dataset only includes a limited amount of musical genres (7). However, in music streaming services such as Spotify there are more than 1300 different genres and subgenres that could reveal further insights and patterns in the data;
- **Addition of Non-English Lyrics**: the used data only contained lyrics which were in English; hence, this could be slightly restricting in terms of conclusions on which keywords best define each genre.

## Dataset Details
The dataset used was divided into train (used to build the machine-learning models) and testing sets (goal is to predict the musical genre of the song lyrics and access if the model is performing well). 

- **id**: unique identifier
- **title**: song title
- **artist**: main artist of the song
- **year**: year the song was launched in
- **views**: number of views the song has on an online music service
- **features**: includes names of collaborating artists (will be EMPTY otherwise)
- **lyrics**: lyrics of the song - include tags for specific sections 
- **tag**: main musical  genre of the song

## Repository Description
This repository contains all the final files created during the development of our project. Hence, the following list contains a short description of how this repository is organized and what each file contains:
- [README](README.md): file which contains all the basic information on the project (objectives, motivations, features and improvements);
- [Project Report](Text_Mining_Group03_Report.pdf): this is a pdf file of the project report where all the steps of development of the project; reasoning behind every decision and key findings/achievements are summarized;
- [Vocabulary Folder](vocabulary): this folder contains several sets of words that were selected through slightly different pre-processing techniques;
- [Results Output](Group03_Version46.csv): csv file which contains the final results of the model - which were then submitted into the kaggle competition (Group 3) [Kaggle Competition](https://www.kaggle.com/competitions/decoding-emotion-from-music);
- [Preprocessing of Data](Preprocessing.ipynb): jupyter notebook which contains the whole EDA process for the data of this project;
- [Log Ratio Analysis](Log_Ratio_Analysis.ipynb): jupyter notebook which contains a Log-Ratio analysis which was used as a way to reduce the size of the dataset and find a set of most important words for each genre - vocabulary;
- [Modeling](Modeling.ipynb): jupyter notebook which includes all of the modelling phase of the project;
- [Sentiment Analysis](Sentiment_analysis.ipynb): jupyter notebook that has the whole process of the sentiment analysis of the project (pre-processing, modelling, visualization of results);
- [Functions](functions.py): python file that contains functions crucial for the development of the project but that would be more beneficial in terms of organization to be on a separate file and then be imported when needed;


## Project Developed by:
- Catarina Oliveira | [LinkedIn](https://www.linkedin.com/in/cjoliveira96/)
- Daniel Kruk | [LinkedIn](https://www.linkedin.com/in/daniel-kruk-/)
- Joana Rosa | [LinkedIn](https://www.linkedin.com/in/joanarrosa/) 
- Marcelo Júnior | [LinkedIn](https://www.linkedin.com/in/marceloptajunior/)
- Martim Serra | [LinkedIn](https://www.linkedin.com/in/martim-cserra/)
##
