# Meme-Sentiment-Analysis

## Overview
This project is a web-based application that performs sentiment analysis on memes. The application uses a Flask backend and machine learning models to classify the sentiment of a given meme image into categories like very positive, positive, neutral, negative, or very negative.

### Disclaimer
This was my first machine learning project, so the implementation might not be optimized and could be improved with more advanced techniques and optimizations.

## Features
- Upload and analyze meme images through a web interface.
- Uses multiple machine learning models to predict sentiment.
- Majority voting system to decide the final sentiment of the meme.

## Getting Started

### Prerequisites
- Python 3.x
- PIL
- NumPy
- Pickle

## How It Works
The application initializes three machine learning models (Decision Tree, K-Nearest Neighbors, and Random Forest) and uses them to predict the sentiment of the uploaded meme. The predictions from all models are then aggregated using a majority voting mechanism to determine the final sentiment.

## Models
- Decision Tree
- K-Nearest Neighbors
- Random Forest

These models are loaded from pre-trained `.pkl` files and used for making predictions.
