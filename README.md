# sentiment_analysis-streaming_platform
## Structure of the Repository
- data_collection_exploration folder
  - Google_Play_Data_Acquisition.ipynb : Jupyter notebook to scrape and collect reviews of the streaming platform from Google Play
  - *_data_exploration.ipynb : text preprocessing and lemmatization; exploration of the lemmatized words, bigrams, trigrams; creation of Word2Vec (for each streaming platform)
- data_analysis_visualization folder:
  - *_time_series_plots.ipynb : plots about trends of score, reviews and subscribers
  - *_topic_modeling.ipynb : classification model to label the reviews depending on the topic and data visualization
