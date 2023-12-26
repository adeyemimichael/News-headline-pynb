# News Sentiment Analysis

## Overview
This project conducts sentiment analysis on news headlines fetched from a news API using Python. Its goal is to analyze the sentiment polarity of news headlines and visualize the distribution of sentiment scores.

## Contents
1. **Data Acquisition:** The code fetches real-time news headlines from a News API (NewsAPI.org) using an API key.
2. **Data Processing:** Utilizes the fetched headlines, applies sentiment analysis using the TextBlob library, and includes basic data cleaning techniques.
3. **Sentiment Analysis:** Determines polarity (positive, negative, or neutral) of each headline.
4. **Results Visualization:** Visualizes sentiment scores via a histogram to show sentiment distribution across news headlines.

## How to Use
1. **API Key:** Replace the placeholder API key in the code with a valid key from NewsAPI.org.
2. **Running the Code:** Execute the Python script in a Jupyter notebook or any Python environment.
3. **Requirements:** Ensure necessary libraries (`requests`, `textblob`, `matplotlib`) are installed using `pip install`.

## Project Structure
- `sentiment_analysis.ipynb`: Jupyter notebook containing Python code for sentiment analysis.
- `README.md`: This file providing project overview and usage instructions.

## Additional Notes
- **Limitations:** The free News API tier may have rate limitations. Check API documentation for usage limits.
- **Improvements:** Implement more advanced NLP techniques for better sentiment analysis accuracy.

