# Overview

Chat Analyzer is a Streamlit-based web application that allows users to analyze chat data efficiently. It preprocesses the chat data, extracts insights, and visualizes patterns using various data analysis techniques.

## Features

Preprocess chat data to make it analysis-ready.

Visualize chat patterns using Matplotlib and Seaborn.

Extract URLs, emojis, and banned words from messages.

Filter out unnecessary words for improved analysis.

Streamlit-powered UI for easy interaction

# Installation and Setup

### Prerequisites

Ensure you have Python 3.8+ installed.

Step 1: Clone the Repository

git clone https://github.com/priyeshr7/chat_analyzer.git

Step 2: Create a Virtual Environment 
					
python -m venv venv

source venv/bin/activate   # On macOS/Linux

venv\Scripts\activate      # On Windows

# Dependencies

The application uses the following Python libraries:

Streamlit - To create the web interface

Matplotlib - For data visualization

Seaborn - For enhanced statistical plots

Urlextract - To extract URLs from text

Wordcloud - To generate word cloud visualizations

Pandas - For data manipulation

Emoji - To handle and analyze emojis in messages

To install dependencies manually: 

pip install streamlit matplotlib seaborn urlextract wordcloud pandas emoji
