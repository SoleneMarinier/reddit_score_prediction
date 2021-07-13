# Reddit Score Prediction - Kaggle Competition
## M2 ECO-STAT 2020-2021 Final Project

Team members: TOURRET Alice, MARINIER Solène
Notes: The objective of this competition is to perform the prediction of Reddit comments popularity combining network and text mining techniques.

### ARCHITECTURE (.zip)

README.txt

#### Data:
Needed for training the model and evaluating its performance:
word_features.pkl
df_body_cleaned.pkl

#### Predictions:
submission.csv

#### Additional data sources:
comments_students.csv
df_inter.pkl
new_df.pkl

#### Notebooks:
01_data_cleansing.ipynb
02_text_preprocessing.ipynb
021_pre-trained_sentiment_analysis.ipynb
022_word_association.ipynb
03_tfidf_vectorizer.ipynb
04_modeling.ipynb

### EXECUTION

We have splitted our code into multiple python notebooks for clarity purposes. In order to run the model without running all preprocessing steps you only
need `df_body_cleaned` and `word_features` (from TF-IDF) which are included in the repository. Then you can launch the execution starting from the cell "To be executed" in notebook `04_modeling.ipynb`. 

If you want to execute all other notebooks, the additional data sources have been saved as pickle files and are available at this [link] (to avoid huge storage folder)(https://filesender.renater.fr/?s=download&token=8fdeec5c-b11b-4024-95bb-4c4f7870b578). You just have to follow the notebooks then. When the execution is very time consuming,
it is specified whithin the notebook.

You may have to install some libraries. The ones used in our code are specified in the `requirements.txt` file with their corresponding version.

Note that you also have to specify the path where you saved the data each time you want to execute the code in the notebooks. Just replace the path in object `repsource` by your path in the cell right after the imports ending with a slash.
    

