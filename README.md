# Best Cars Dealership - Full Stack Web Application

## Capstone Project Overview
Best Cars Dealership is a responsive national car retailer web application that allows users to browse dealership branches across the United States, view detailed customer reviews, and submit their own dealer reviews. 

The application is built using a modern microservices architecture comprising:
- **Frontend**: Responsive UI built with React, HTML5, CSS3, and Bootstrap.
- **Backend**: Python Django web framework handling user authentication, administration, and proxying microservice requests.
- **Dealership & Review Microservice**: Node.js and Express server interfacing with MongoDB to manage dealerships and customer reviews data.
- **Sentiment Analysis Microservice**: Python Flask application utilizing NLTK/VADER SentimentIntensityAnalyzer for real-time sentiment scoring of reviews.
- **Database**: SQLite3 for Django user accounts and car models; MongoDB for dealership and review collections.
- **CI/CD & Deployment**: GitHub Actions workflows for automated linting (flake8 and JSHint), containerized with Docker, and deployed via IBM Cloud Code Engine and Kubernetes.

## Features
- User registration, login, and session-based authentication.
- Filter dealerships by state dynamically.
- View individual dealership details and community reviews with visual sentiment indicators (Positive, Neutral, Negative).
- Authenticated user review submission form with car make and model dropdowns.
- Django Admin portal for managing Car Make and Car Model inventory.