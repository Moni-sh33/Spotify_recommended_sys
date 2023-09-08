# Spotify_recommended_sys


It is  recommendation system based on the spotify dataset of kaggle

Creating a music recommender system  involves using Natural Language Processing (NLP) techniques to analyze the text descriptions and recommend music based on the content. Here's a high-level overview of how you could approach building such a system using Python:

1. *Data Collection:*
   - Dataset Link: https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset

2. *Text Preprocessing:*
   - Clean and preprocess the text by removing special characters, punctuation, and converting all letters to lowercase.
   - Tokenize the descriptions into individual words or phrases.
   - Remove stopwords (common words like "and," "the," "is," etc.) that don't provide much context.

3. *Feature Extraction:*
   - Convert the tokenized descriptions into numerical representations that can be used by machine learning models. You can use techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings (Word2Vec, GloVe) for this purpose.

4. *Building a Recommender Model:*
   - Choose a recommendation algorithm. Collaborative Filtering and Content-Based Filtering are two common approaches.
   
   *Content-Based Filtering:*
   - In your case, content-based filtering might be more suitable since you're focusing on analyzing the video descriptions. This approach recommends items similar to those the user has shown interest in.
   - Calculate similarity scores between videos based on their preprocessed descriptions and feature representations.
   - Recommend videos that have similar descriptions to the ones the user has liked or interacted with in the past.

5. *User Interaction and Recommendations:*
   - Allow users to input their preferences, e.g., by providing a sample video URL or keywords related to their interests.
   - Use the selected video's description for recommendation.
   - Rank the videos based on similarity scores and present the top recommendations to the user.
  





two pickle files are created after the execution of a .ipynb file where 
1. df.pkl
2. similarity.pkl

After that executing the .ipynb file execute app.py and run the program it includes user interface which recommends the preffered song  

