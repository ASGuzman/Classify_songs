# Music Genre Classification Project

## Introduction

Have you ever wondered how streaming services recommend music that seems tailor-made for your tastes? The key lies in the analysis of vast amounts of music data to provide personalized recommendations. In this project, we delve into the realm of music genre classification using data compiled by The Echo Nest, a research group specializing in music information retrieval.

## Project Overview

Over the past few years, streaming services have revolutionized the way people discover and listen to music. However, with an extensive catalog of songs available, users can often feel overwhelmed when trying to find new music that aligns with their preferences.

To address this challenge, streaming services employ advanced techniques for categorizing music and generating personalized recommendations. One such technique involves analyzing raw audio data to extract various metrics, which are then used to classify songs into different genres.

In this project, our goal is to classify songs as either 'Hip-Hop' or 'Rock' solely based on their musical features, without actually listening to the songs ourselves. To achieve this, we will:

1. Clean and preprocess the data.
2. Perform exploratory data visualization.
3. Utilize feature reduction techniques.
4. Implement simple machine learning algorithms, such as decision trees and logistic regression.

## Data Description

The primary datasets used in this project include:
- **Metadata about tracks**: Contains information such as the title, artist, and number of listens.
- **Track metrics compiled by The Echo Nest**: Provides musical features of each track, such as danceability and acousticness, on a scale from -1 to 1. These features are essential for our classification task and are stored in a JSON format.

Both datasets offer valuable insights into the characteristics of songs, allowing us to build a robust classification model.

## Project Structure

The project is structured as follows:
1. **Data Loading and Preprocessing**: We start by loading the metadata and track metrics datasets, and then preprocess the data to ensure compatibility for analysis.
2. **Exploratory Data Visualization**: We visualize the data to gain insights into the distribution of musical features and explore potential patterns.
3. **Feature Reduction**: We employ techniques to reduce the dimensionality of the feature space, making it more manageable for our machine learning algorithms.
4. **Model Building and Evaluation**: We train various classification models, such as decision trees and logistic regression, and evaluate their performance using appropriate metrics.
5. **Conclusion**: We conclude the project by summarizing our findings and discussing potential areas for further exploration.

By the end of this project, we aim to gain a deeper understanding of music genre classification and develop a reliable model for predicting the genres of songs based on their musical features.

Let's dive into the fascinating world of music data analysis and classification! 🎵📊
