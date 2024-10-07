# Movie Recommender System

This project is a content-based movie recommendation system that suggests movies to users based on their preferences. It leverages movie data to calculate similarity between movies and recommends those with the highest relevance to the user's selection.

## Features

- **Content-based filtering:** Recommends movies based on similarities in features like genre, cast, crew, etc.
- **Vectorization Techniques:** Uses vectorization and `cosine_similarity` to calculate the similarity between movies.
- **Interactive search:** Users can input movie titles and get recommendations.
  
## Tech Stack

- **Frontend:** HTML, CSS
- **Backend:** Python
- **Libraries:** 
  - `NumPy`
  - `Pandas`
  - `scikit-learn` (for vectorization and cosine similarity)

## Project Setup

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-recommender.git
    ```

2. Navigate to the project directory:
    ```bash
    cd movie-recommender
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

