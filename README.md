# Music Genre Classification and Recommendation System

## Overview

This repository contains a Music Genre Classification and Recommendation System that utilizes machine learning and deep learning techniques to classify music genres and generate personalized song recommendations for users based on their preferences and feedback.

## Features

- **Music Genre Classification**: The system employs machine learning algorithms to classify music into different genres based on audio features such as tempo, rhythm, and spectral characteristics. Additionally, a deep learning model is utilized for enhanced accuracy in genre classification.

- **Recommendation Generation**: After classifying music genres, the system generates song recommendations for users based on their preferences and feedback. It employs collaborative filtering and content-based recommendation techniques to provide personalized recommendations.

- **User Feedback Integration**: Users can provide feedback on the recommended songs, such as liking or disliking a song. The system uses this feedback to update the recommendation list and create new generations of recommendations that better suit the user's preferences. The deep learning model is fine-tuned with user feedback to improve recommendation accuracy.

- **Scalability and Efficiency**: The system is designed to handle large music datasets efficiently, making it scalable for real-world applications with a large user base and diverse music libraries.

## Comparative Study Results

A comparative study was conducted to evaluate the performance of two approaches for generating song recommendations:

1. **Cosine Similarity Based Numpy Matrix**: This approach involved creating a numpy matrix based on cosine similarity between songs' audio features. The most relevant rows were then selected to generate recommendations. While this method provided reasonable recommendations, it was limited by the manual selection process and did not adapt well to user feedback.

2. **Deep Learning Model**: In contrast, the deep learning model utilized in the system learned intricate patterns and features from the audio data, leading to more accurate genre classification and recommendation. Additionally, the model was fine-tuned with user feedback, resulting in improved recommendation accuracy over time.

## Installation

To use the Music Genre Classification and Recommendation System, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Srinidhi-Krishnan30/Music-Genre-Classification.git
