# Project-2-AIML-Project-Series-
# College Query Chatbot

## Overview
This Python script creates a specialized chatbot designed for answering college-related queries from students. It employs sentiment analysis, TF-IDF word embedding, and visualizes word clouds for enhanced user interaction. The chatbot maintains a chat history, greets users, and provides confidence scores for responses.

## Features
- **Data Handling:** Loads and analyzes a dataset containing pre-stored college-related questions and responses.
- **Data Cleaning:** Applies text normalization techniques to clean and preprocess the dataset.
- **Sentiment Analysis:** Uses the VADER sentiment analyzer to evaluate the sentiment of user queries.
- **Word Cloud Visualization:** Generates word clouds to visualize frequent words in user queries and responses.
- **TF-IDF Word Embedding:** Implements TF-IDF vectorization for word embedding.
- **Chatbot Functionality:** Provides a chatbot interface that matches student queries with stored questions and returns informative responses.
- **Chat History:** Maintains a chat history and displays relevant information.
- **Greeting Functionality:** Greets users upon interaction.
- **Confidence Scores:** Provides confidence scores for the relevance of responses.

## How to Use
1. **Installation:** Install required libraries using `pip install -r requirements.txt`.
2. **Run the Script:** Execute the script `college_query_chatbot.py` in a Python environment.
3. **Chat with the Bot:** Enter college-related queries to interact with the chatbot. Type 'exit' to end the conversation.

## Dependencies
- pandas
- nltk
- matplotlib
- wordcloud
- scikit-learn

## Files
- `college_query_chatbot.py`: Main script implementing the chatbot functionality.
- `college_dialogs.txt`: Dataset containing pre-stored college-related questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.

## Author
Shreya Prasad

Feel free to enhance and customize the code based on your needs. Happy college query-solving!
