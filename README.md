# Lyrics Sentiment Analysis Project

## Overview
This project uses Python to fetch song lyrics from the [lyrics.ovh API](https://lyricsovh.docs.apiary.io/) and perform sentiment analysis using `spaCyTextBlob`. The analysis helps determine the emotional tone of the lyrics based on a polarity score.

## Features
- Fetch song lyrics from an online API.
- Save lyrics data to JSON files.
- Perform sentiment analysis on the lyrics.
- Calculate and interpret polarity scores to understand the emotional sentiment of songs.

## Tools and Libraries
- **Python**: Core language used.
- **requests**: To make HTTP requests to the lyrics API.
- **spaCy**: For natural language processing.
- **spaCyTextBlob**: For sentiment analysis.
- **JSON**: To store and read lyrics data.

## How It Works
1. **Fetching Lyrics**: The project uses the `lyrics.ovh` API to get lyrics for songs and saves them as JSON files.
2. **Sentiment Analysis**: The lyrics are analyzed using `spaCyTextBlob` to generate a polarity score ranging from -1.0 (negative) to 1.0 (positive).

## Installation and Setup
1. Clone this repository to your local machine.
2. Install the required packages:
   ```bash
   pip install requests spacy spacytextblob
   python -m spacy download en_core_web_sm
