# Automated AI-Driven Content Posting on Twitter

This project aims to automate the process of generating and posting AI-curated content on Twitter. It utilizes natural language processing (NLP) and computer vision techniques to generate text and images, which are then posted to Twitter via the Twitter API.

## Overview

The system is designed to generate engaging text and images using pre-trained AI models. It automates the posting process on Twitter, reducing the need for manual intervention. The desired outcome is an efficient and effective system that can consistently generate high-quality content and engage with users on Twitter.

## Features

- Text and image generation using AI models
- Integration with the Twitter API for content posting
- Automated scheduling of content posting
- Minimal human intervention required


# Requirements

## Environment
- Python 3.x
- Google Colab (optional for development)
- Access to Twitter Developer Account

## Dependencies
- tweepy==4.14.0
- transformers==4.41.1
- torch==2.3.0+cu121

## Additional Notes
- This project was developed using Google Colab, but it can be adapted to other Python environments as well.
- Access to a Twitter Developer Account is required to obtain API tokens and secrets for posting content to Twitter.


## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
3. Install the necessary dependencies using `pip install -r requirements.txt`.
4. Set up your Twitter Developer Account and obtain the necessary API keys and access tokens.
5. Update the `config.yml` file with your Twitter API credentials.
6. Run the main script to start generating and posting content.

## Usage

To use the project, follow these steps:

1. Run the main script to generate and post content to Twitter.
2. Monitor the Twitter account for engagement metrics such as likes, retweets, and comments.
3. Adjust the content generation parameters as needed to optimize engagement.


