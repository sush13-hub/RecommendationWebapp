# RecommendationWebapp

Overview
This project is a Flask-based anime recommendation system that fetches anime details and recommendations using the Jikan API. It processes anime data, extracts relevant details, and presents structured information such as titles, ratings, genres, and recommendations.

Key Features
Flask Web Application:

The script initializes a Flask app using create_app() and runs it in debug mode.

Anime Data Extraction:

Uses the Jikan API to fetch detailed information about a given anime ID.

Data Cleaning & Processing:

Cleans anime synopses by removing newlines and text inside square brackets.

Extracts ratings by removing trailing text after the last hyphen (-).

Fetching Recommendations:

Retrieves a list of recommended anime based on a given anime ID.

Parses details like titles, episodes, studios, genres, and scores.

Limits recommendations to the top 10 and avoids excessive API calls using time.sleep().

Technologies Used
Python (Flask, Requests, re)

Jikan API (For fetching anime data)

REST API Integration

How It Works
The script starts a Flask web server.

It calls fetch_anime_full(anime_id) to fetch anime details.

The function fetch_recommendation(anime_id) retrieves top 10 anime recommendations.

The parsed data is structured and returned.
