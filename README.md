# Automated AI-Driven Content Posting on Twitter

This project aims to automate the process of generating and posting AI-curated content on Twitter. It utilizes natural language processing (NLP) and computer vision techniques to generate text and images, which are then posted to Twitter via the Twitter API.

# Overview

The system is designed to generate engaging text and images using pre-trained AI models. It automates the posting process on Twitter, reducing the need for manual intervention. The desired outcome is an efficient and effective system that can consistently generate high-quality content and engage with users on Twitter.The project leverages the free-tier version of the Twitter Developer API, which imposes certain limitations on the available features.


# Features

- Text and image generation using AI models
- Integration with the Twitter API for content posting
- Automated scheduling of content posting
- Minimal human intervention required


# Requirements

## Environment
- Python 3.x
- Google Colab (optional for development)
- Access to Twitter Developer Account(free-tier version)
- Necessary Python libraries (see `requirements.txt`)

## Dependencies
- tweepy==4.14.0
- transformers==4.41.1
- torch==2.3.0+cu121


# Limitations of Free-Tier Twitter API

The free-tier version of the Twitter Developer API used in this project comes with the following limitations:

- **Posting Tweets**: Allowed
- **Deleting Tweets**: Allowed
- **Getting User Information**: Allowed
- **Access to Other Endpoints**: Requires Basic or Pro version

To access additional features or higher usage limits, it needs to upgrade to a paid version (Basic or Pro) of the Twitter Developer API.


# Testing Endpoints

## Using Postman Collection

To facilitate testing of the endpoints, a Postman collection is available that contains pre-configured requests for the following operations:

- Posting content to Twitter
- Deleting a tweet
- Retrieving user information

### Setup Instructions

1. Download the Twitter API v2 collection
2. Import the collection into Postman.
3. Replace the placeholder values in the requests (such as access tokens and secrets) with  actual credentials obtained from the Twitter Developer Account.
4. Test the endpoints by sending requests to the appropriate URLs.

#### Endpoint URLs

Here are the URLs for the endpoints:

- **Post a Tweet:** `https://api.twitter.com/2/tweets`
- **Delete a Tweet:** `https://api.twitter.com/2/tweets/:id`
- **Get User Information:** `https://api.twitter.com/2/users/me`


# Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Set up your Twitter Developer Account and obtain the necessary API keys and access tokens.
4. Update the `config.yml` file with your Twitter API credentials.
5. Run the main script to start generating and posting content.


# Usage

To use the project, follow these steps:

1. Run the main script to generate and post content to Twitter.
2. Monitor the Twitter account for engagement metrics such as likes, retweets, and comments.
3. Adjust the content generation parameters as needed to optimize engagement.


# Additional Notes
- This project was developed using Google Colab, but it can be adapted to other Python environments as well.
- Access to a Twitter Developer Account is required to obtain API tokens and secrets for posting content to Twitter.


