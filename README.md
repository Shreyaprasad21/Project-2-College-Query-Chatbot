![nexus_software_pvt_ltd_cover](https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system/assets/142075353/1e542e0d-2db0-41cb-99b7-d8f61c9da7cb)

# PROJECT 2 - COLLEGE QUERY CHATBOT
This project has been done as a part of my internship program at Nexus Info. This is the second project of my internship, where I utilized natural language processing and sentiment analysis to create a robust chatbot for answering college-related queries. The internship was conducted remotely, allowing me to collaborate with professionals and enhance my skills in a virtual environment.

## Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Deployment](#deployment)
7. [Notes](#notes)

## Introduction
The College Query Chatbot is designed to assist students by providing automated responses to common college-related queries. The chatbot leverages natural language processing (NLP) techniques to understand and respond to user queries effectively. The system aims to enhance the student experience by providing quick and accurate information about college admissions, courses, scholarships, and more. The project integrates sentiment analysis to gauge user sentiment and visualize word clouds to understand the frequent topics of queries and responses. The application is implemented in Python and can be extended to cover a wider range of queries.

## Features
- **Automated Responses:** Provides quick and accurate responses to common college-related queries.
- **Sentiment Analysis:** Uses VADER sentiment analysis to evaluate the sentiment of user queries.
- **Word Cloud Visualization:** Generates word clouds to visualize frequent words in user queries and responses.
- **TF-IDF Vectorization:** Implements TF-IDF vectorization for text data.
- **Chat History:** Maintains a chat history and displays relevant information.
- **User Greeting:** Greets users upon interaction.
- **Confidence Scores:** Provides confidence scores for the relevance of responses.

## Dependencies
- Python 3.9 or higher
- pandas
- nltk
- matplotlib
- wordcloud
- scikit-learn
- vaderSentiment

## Usage
1. Clone the repository:
   ```sh
   https://github.com/Shreyaprasad21/Project-2-College-Query-Chatbot.git

2. Run the chatbot script:
      ```sh
   Chatbot_project2.ipynb

3. Follow the prompts to interact with the chatbot. Type 'exit' to end the conversation.

## File Structure
- `chatbot_project2.ipynb`: Main script implementing the chatbot functionality.
- `dialogs_new.txt`: Dataset containing pre-stored college-related questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.
- `README.md`: Instructions and information about the project.

## Deployment

1. Start the chatbot by running:
  ```
  python college_query_chatbot.py
  ```

2. Interact with the chatbot in the console. Type 'exit' to end the conversation.

## Notes
- The project was developed using Python, with the main chatbot functionality implemented in `college_query_chatbot.py`.
- `nlp_utils.py` contains helper functions for text normalization.
- The dataset (`college_dialogs.txt`) is provided and contains sample questions and responses.
- Sentiment analysis and word cloud visualization are integrated into the chatbot.
- TF-IDF vectorization is used to match user queries with stored questions.
- The project can be extended to cover more queries and provide more detailed responses.
