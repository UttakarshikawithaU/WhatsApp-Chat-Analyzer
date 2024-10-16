# WhatsApp Chat Analyser

## Overview

This project performs sentiment analysis on WhatsApp chat data using the DistilBERT model and provides insightful data visualizations, including word clouds, weekly activity heatmaps, and identification of the most active users.

## Features

1. Sentiment Analysis:
   - Utilizes the DistilBERT model (distillBERT base uncased finetuned sst english) for sentiment analysis.
   - Analyzes the sentiment of messages to determine if they are positive or negative by finding out the sentiment scores.

2. Data Visualization:
   - Generates various visualizations to provide a comprehensive overview of the chat data.
   - Includes word clouds, weekly activity heatmaps, identification of the most active users, weekly, monthly and daily activity graphs.
   - Inlcudes most commonly used emojis
   - Sentiment Scores are plotted against each message

## Requirements

- Python 3.x
- Required Python packages are listed in the `requirements.txt` file.

## Setup

1. Clone the repository:

    bash
    git clone https://github.com/your-username/whatsapp-chat-analysis.git

2. Install the required packages:

    bash
    pip install -r requirements.txt

3. Run the main script:

    bash
    python main.py

## Usage

1. Sentiment Analysis:
   - The `sentiment_analysis.py` script performs sentiment analysis on WhatsApp chat data.
   - Adjust the parameters, such as positive and negative thresholds, as needed by ###the user.

2. Data Visualization:
   - The `data_visualization.py` script generates various plots for better understanding of the chat data.
   - Customize the script to include or exclude specific visualizations based on your preferences.
