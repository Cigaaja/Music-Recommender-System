# Music Recommendation System

This project implements a Music Recommendation System using audio features from a dataset of songs. It analyzes and recommends music based on genre and other feature similarities.

## Table of Contents
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The system uses a dataset containing 1000 audio samples from 10 different genres. The dataset can be accessed here https://www.kaggle.com/code/imsparsh/gtzan-genre-classification-deep-learning-val-92-4  :
- **Genres**: Blues, Classical, Country, Disco, Hiphop, Jazz, Metal, Pop, Reggae, Rock
- **Data**: Each genre has 100 samples.
- **File**: `features_30_sec.csv` (contains extracted audio features for each sample)

The dataset should be placed in the specified path (`/content/drive/MyDrive/kaggle/Data/features_30_sec.csv`) for the notebook to function properly.

## Features

This Music Recommendation System includes:
- **Data Preprocessing**: Prepares the data by loading and organizing audio feature datasets.
- **Visualization**: Uses Matplotlib and Seaborn to plot data distributions and visual insights.
- **Similarity Computation**: Leverages cosine similarity for recommending songs based on their feature vectors.
- **Metrics Calculation**: Evaluates recommendation accuracy with metrics such as precision, recall, F1-score, and nDCG (Normalized Discounted Cumulative Gain).

## Installation

To run this notebook, you need the following libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn librosa
