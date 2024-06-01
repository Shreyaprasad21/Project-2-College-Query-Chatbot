![nexus_software_pvt_ltd_cover](https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system/assets/142075353/1e542e0d-2db0-41cb-99b7-d8f61c9da7cb)

# PROJECT 3 - MULTIPLE DISEASE DETECTION SYSTEM
This project has been done as a part of my internship program at Nexus Info. This is the third and final project of my internship, where I utilized machine learning and Streamlit to create a robust disease detection system. The internship was conducted remotely, allowing me to collaborate with professionals and enhance my skills in a virtual environment.

## Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Deployment](#deployment)
7. [Notes](#notes)

## Introduction
The Multiple Disease Detection System is designed to detect Parkinson's disease, diabetes, and heart disease from medical images using advanced deep learning techniques. The system aims to assist healthcare professionals by providing an automated tool that can quickly and accurately diagnose these conditions, thereby improving the efficiency and effectiveness of medical diagnoses. The project leverages state-of-the-art machine learning algorithms to analyze medical data and identify potential diseases, offering a reliable solution for early detection and treatment planning. The application was deployed using Streamlit, an open-source app framework, which allows for the creation of interactive and shareable web applications for machine learning and data science.

## Features
- **Multi-Disease Detection:** Capable of predicting Parkinson's disease, diabetes, and heart disease from medical images.
- **Deep Learning Integration:** Utilizes advanced deep learning techniques to analyze medical images and make accurate predictions.
- **User-Friendly Interface:** Provides a simple and intuitive interface for users to upload medical images and receive disease predictions.
- **Real-Time Prediction:** Offers real-time prediction of diseases, enabling quick decision-making for healthcare professionals.
- **Scalability:** Designed to handle large volumes of medical data and can be easily scaled to include additional diseases in the future.
- **Streamlit Deployment:** Deployed using Streamlit, allowing for easy sharing and access to the disease detection system through a web browser.
- **Interpretability:** Provides explanations or visualizations to help users understand how predictions are made, increasing trust and transparency.
- **Model Performance Metrics:** Reports performance metrics such as accuracy, precision, recall, and F1-score to evaluate the reliability of predictions.
- **Continuous Improvement:** Allows for continuous improvement through feedback mechanisms, ensuring the system stays up-to-date with the latest medical research and advancements.

## Dependencies
- Python 3.9 or higher
- NumPy
- pandas
- scikit-learn

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system.git

2. Install dependencies:
   ```sh
   pip install -r requirements.txt

3. Run the desired disease prediction script:
- For Parkinson's Disease:
  ```
  parkinsons.ipynb
  ```
- For Diabetes:
  ```
  diabetes.ipynb
  ```
- For Heart Disease:
  ```
  heart.ipynb
  ```
  
4. Follow the prompts to input data for prediction.

## File Structure
- `parkinsons.ipynb`: Script for predicting Parkinson's Disease.
- `diabetes.ipynb`: Script for predicting Diabetes.
- `heart.ipynb`: Script for predicting Heart Disease.
- `Dataset/`: Directory containing the datasets for each disease.
- `parkinsons.csv`: Dataset for Parkinson's Disease.
- `diabetes.csv`: Dataset for Diabetes.
- `heart.csv`: Dataset for Heart Disease.
- `README.md`: Instructions and information about the project.

## Deployment
The project was deployed using Streamlit. To deploy the application locally:

1. Ensure Streamlit is installed:
  ```
  pip install streamlit
  ```

2. Run the Streamlit app:
  ```
  streamlit run app.py
  ```

3. Open your web browser and go to `http://localhost:8501`.

## Notes
- The project was developed using Jupyter Notebook, with separate notebooks (`parkinsons_detection.ipynb`, `diabetes_detection.ipynb`, `heart_disease_detection.ipynb`) for each disease.
- Each notebook contains the code for data preprocessing, model training, and evaluation specific to the respective disease.
- The datasets (`parkinsons.csv`, `diabetes.csv`, `heart_disease.csv`) are provided in the `Dataset/` directory.
- Model deployment, user interface, and interaction were implemented using Streamlit, providing an intuitive web interface for disease prediction.












































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
