# Amazon Alexa Sentiment Analysis

## Overview
Amazon Alexa Sentiment Analysis is a project designed to analyze user feedback, reviews, and voice interaction data to determine their sentiment (positive, negative). By applying Natural Language Processing (NLP) techniques and machine learning models, this project aims to provide insights into user satisfaction and areas for improvement, ultimately enhancing the Alexa user experience.

## Features
- Text preprocessing: Tokenization, stemming, and stopword removal.
- Sentiment classification using machine learning models.
- Probabilistic predictions with confidence scores.
- Interactive interface for inputting and analyzing text feedback.

## Project Structure
```
Amazon-Alexa-Sentiment-Analysis/
├── data/                # Dataset used for training and testing
├── models/              # Trained machine learning models
├── notebooks/           # Jupyter notebooks for exploration and development
├── src/                 # Source code for preprocessing, training, and inference
├── app.py               # Flask/Streamlit app for user interaction
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/username/Amazon-Alexa-Sentiment-Analysis.git
   cd Amazon-Alexa-Sentiment-Analysis
   ```

2. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Ensure the necessary dataset is placed in the `data/` directory or downloaded as required.

## Usage
1. **Train the Model**:
   Run the training script to train the sentiment analysis model on the dataset.
   ```bash
   python src/train.py
   ```

2. **Run the Application**:
   Launch the Flask/Streamlit application to analyze user input.
   ```bash
   python app.py
   ```
   Navigate to `http://127.0.0.1:5000` (or the specified port) in your browser.

3. **Test Sentiment Analysis**:
   Use the interface to input feedback text and view the sentiment prediction.

## Dependencies
- Python 3.7+
- scikit-learn
- pandas
- numpy
- Flask or Streamlit
- nltk

Install all dependencies using the `requirements.txt` file.

## Example
Input:
```
"I love using Alexa, it makes my life so much easier!"
```
Output:
```
Sentiment: Positive

```

## Acknowledgments
- [nltk](https://www.nltk.org/) for text preprocessing.
- [scikit-learn](https://scikit-learn.org/) for machine learning.
- Datasets sourced from user reviews and public sentiment analysis datasets.
