# Movie Recommender System using NLTK and Cosine Similarity

This repository contains a **Content-Based Movie Recommender System** that suggests the top 5 movies similar to a selected movie. The system is built using **NLTK** for natural language processing and **cosine similarity** to find similarities between movie descriptions.

## Features

- **Top 5 Similar Movies**: Recommends 5 movies that are most similar to the input movie.
- **Content-Based Filtering**: The recommendation is based on movie descriptions and metadata.
- **Cosine Similarity**: Measures similarity between movie descriptions by comparing content vectors.

## Dataset

The dataset used for this project can be found on Kaggle:

- [Millions of Movies Dataset](https://www.kaggle.com/datasets/akshaypawar7/millions-of-movies)

This dataset contains movie titles, descriptions, and other relevant metadata, forming the basis for the recommender system.

## Tools & Libraries Used

- **Python**: Core language for the system.
- **NLTK**: To preprocess and tokenize movie descriptions.
- **Cosine Similarity**: Used to calculate the similarity between movies based on their descriptions.
- **Pandas**: For data manipulation.
- **Scikit-learn**: For vectorizing movie descriptions and computing cosine similarity.

## How the System Works

1. **Preprocessing**: Movie descriptions are cleaned and tokenized using NLTK.
2. **Vectorization**: Descriptions are converted to numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).
3. **Cosine Similarity**: The similarity score is calculated between the input movie and the rest of the movies.
4. **Recommendations**: The top 5 most similar movies are returned as recommendations.

## Getting Started

### Prerequisites

- Python 3.x
- nltk library

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
### recommend("Dune")

1. **Dune: Part Two**
2. **Dune**
3. **Hirokin: The Last Samurai**
4. **Frankenstein Must Be Destroyed**
5. **War for the Planet of the Apes**
