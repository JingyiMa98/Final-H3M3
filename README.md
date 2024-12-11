# Final-H3M3
Nexus - Chatbot with Restaurant Recommendation

Project Overview
Nexus is a Flask-based web application that integrates OpenAI and Yelp APIs to provide intelligent chatbot services and personalized restaurant recommendations. Users can input their preferences through the chatbot page, and the app will extract keywords and suggest nearby restaurants.

Key Features
Home Page:

Displays an introduction to the application.
Provides navigation to the chatbot page.
Chatbot Page:

Users can type their requests (e.g., "Recommend a sushi restaurant").
The app uses the OpenAI API to extract key information (e.g., "sushi," "near me").
The app calls the Yelp API to fetch relevant restaurant recommendations.
Results Page:

Displays recommended restaurants with details such as ratings, addresses, images, and links.


Here’s a suggested structure for the README file in English for your Flask project:

Nexus - Chatbot with Restaurant Recommendation
Project Overview
Nexus is a Flask-based web application that integrates OpenAI and Yelp APIs to provide intelligent chatbot services and personalized restaurant recommendations. Users can input their preferences through the chatbot page, and the app will extract keywords and suggest nearby restaurants.

Key Features
Home Page:

Displays an introduction to the application.
Provides navigation to the chatbot page.

Chatbot Page:

Users can type their requests (e.g., "Recommend a sushi restaurant").
The app uses the OpenAI API to extract key information (e.g., "sushi," "near me").
The app calls the Yelp API to fetch relevant restaurant recommendations.
Results Page:

Displays recommended restaurants with details such as ratings, addresses, images, and links.
Dependencies
The following libraries and tools are required to run the project:

Python Packages
Flask: Used for building the web service.
openai: For integrating with OpenAI's GPT API.
requests: To make HTTP requests to the Yelp API.
Bootstrap (via CDN): For responsive front-end design.
FontAwesome (via CDN): For icons on the front-end.
External APIs
OpenAI API:
Used for natural language understanding and information extraction.
Yelp API:
Used to fetch restaurant details based on the extracted information.
