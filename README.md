# YouTube Video Sentiment Analysis

## Overview

This project is a sentiment analysis of youtube video based on the comments that people post under the video like good ,bad  by using `textblob` and `youtube-api`

## Working

- Fetches comments from a given YouTube video using the YouTube Data API.
- Cleans and preprocesses the text data to remove noise and unwanted characters.
- Analyzes the sentiment of each comment using the `textblob` library.
- Calculates the average sentiment polarity and subjectivity to generate an average rating for the video.

## Requirements

- Python 3.x
- Google API Key (YouTube Data API)
- Required Python packages: `google-auth`, `pandas`, `cleantext`, `textblob`

## How to Use

1. Create  a Google API Key by creating a project in the [Google Cloud Console](https://console.cloud.google.com/).
2. Replace the `developerKey` in the code with your API key.
3. Run the script and provide the URL of the YouTube video when prompted.
4. The script will use the url and get the comments and process it  

## Limitations

- Comments may contain non-English text, emojis, or slang, which could affect sentiment analysis results.
- The sentiment analysis is subjective 

## Acknowledgments

- This project uses the YouTube Data API provided by Google.
- The `textblob` library is used for sentiment analysis.

## License

This project is licensed under the [MIT License](LICENSE).
"""




