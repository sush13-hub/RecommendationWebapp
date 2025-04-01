# RecommendationWebapp

## Overview
-This project is a Flask-based recommendation system that fetches and processes data from an external API. It structures relevant details such as titles, descriptions, ratings, and recommendations.

## Key Features
-Flask Web Application:

-The script initializes a Flask app using create_app() and runs it in debug mode.

-Data Cleaning & Processing:

-Cleans text descriptions by removing unnecessary characters.

-Extracts ratings by processing and filtering raw data.

-Fetching Recommendations:

-Retrieves a list of top recommended items based on a given identifier.

-Parses details like titles, categories, and scores.

-Limits recommendations to the top 10 and optimizes API calls using time.sleep().

## Technologies Used
-Python (Flask, Requests, re)

-REST API Integration

-Data Processing

## How It Works
-The script starts a Flask web server.

-It fetches detailed information about a given entity.

-The function retrieves top 10 recommendations based on a given identifier.

-The parsed data is structured and returned.




