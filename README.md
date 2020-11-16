# spotify-mental-health
*By Matt Kenney and Soo Hwan Park*

Final project for "Data Science for Health" course at Dartmouth.
All notebooks are stored here. Note that data for the project is not tracked in Git, since file sizes are larger than GitHub's limit.


**Notebooks**:
1. `spotify_data`, `news_data`, and `trends_data` notebooks outline our process for obtaining each of our three datasets, and each explores the data breifly to show key characteristcs.
2. `combine_data` performs preprocessing steps on the data before it can be used for machine learning purposes.
3. `validation` defines our model architectures, conducts our 10-fold CV trials, and shows our results.
4. `model_gallery` shows work that is not direclty related to our publication. This notebook shows the ways in which we explored different models and datasets before arriving on our research problem.

From our abstract:
>Search term frequencies are updated in real time and can reveal people’s uncensored desire for information. These characteristics make search term frequencies a more temporally effective and less biased tool to gauge the state of public mental health than traditional mortality data and self-reported surveys. The digital age has also provided tools to gather and analyze data regarding consumed media that populations have daily interactions with. Specifically, music and news are two omnipresent sources of consumed media that shape and regulate people’s moods and mental health. Here, we aim to propose a novel way of forecasting the state of public mental health using two sets of data concerning consumed media in the United States. By using sonic features of daily Top 200 tracks from Spotify and linguistic features from daily article titles from the New York Times, we built Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN) models to predict the search term frequencies for the terms ‘anxiety’ and ‘depression’ that are provided by Google Trends. Across all the models taking in different combinations of data, the LSTM model taking in both Spotify and New York Times data predicted the search term frequencies for ‘anxiety’ and ‘depression’ the best, with the average mean absolute error (MAE) of 0.662 and 0.794 respectively. Overall, using any of the two sources of consumed media data was a better predictor than solely using Trends data (MAE of 3.023 and 3.454 respectively for the two search terms) and combining the two consumed media data together resulted in an even better performance. Our results highlight the potential of using  consumed media data in monitoring and predicting the state of public mental health, which can help create better public policies and timely interventions. Additionally, the results suggest that a similar approach can be applied at an individual level.
