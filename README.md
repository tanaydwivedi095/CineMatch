# CineMatch: AI-Powered Movie Recommendation System

## Overview
CineMatch is an **AI-powered movie recommendation system** that provides personalized movie suggestions based on user preferences. Using **content-based filtering** and **cosine similarity**, CineMatch analyzes movie metadata (genres, keywords, cast, director, etc.) to suggest similar films to the user’s favorite movie.

This intelligent recommendation system helps movie enthusiasts discover new films by analyzing textual movie features and recommending the most relevant matches.

## Features
### ✅ Intelligent Movie Recommendations
- Generates personalized movie recommendations based on user input.

### ✅ Content-Based Filtering
- Uses **genres, keywords, tagline, cast, and director** to match similar movies.

### ✅ Cosine Similarity Matching
- Computes similarity scores between movies using **TF-IDF vectorization**.

### ✅ Efficient Searching & Ranking
- Finds the closest matching movie title and recommends **top 30** most similar films.

## How It Works
1. **User Input**
   - The user enters their favorite movie title.
2. **Text Feature Extraction**
   - Extracts key textual features (genres, keywords, tagline, cast, director) from the movie dataset.
3. **TF-IDF Vectorization**
   - Converts text features into numerical vectors using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
4. **Similarity Computation**
   - Computes the similarity between movies using **cosine similarity**.
5. **Recommendation Output**
   - Returns the **top 30 most similar movies** based on feature similarity.

## Technologies Used
- **Python** – Core programming language for implementation.
- **Pandas** – Data manipulation and CSV handling.
- **NumPy** – Numerical computations.
- **scikit-learn** – Machine learning toolkit for **TF-IDF vectorization** and **cosine similarity**.
- **difflib** – Finds closest movie title matches.

## Installation
### Step 1: Clone the Repository
```bash
git clone https://github.com/tanaydwivedi095/CineMatch.git
cd CineMatch
```

### Step 2: Install Dependencies
Ensure you have **Python 3.8+** installed, then run:
```bash
pip install numpy pandas scikit-learn
```

### Step 3: Run the Application
To start the recommender system, execute:
```bash
python cine_match.py
```

## Usage
1. **Run the script** and enter your favorite movie name.
2. The system will find the closest matching movie title.
3. It will then recommend **30 similar movies** based on metadata similarity.
4. The program allows multiple queries in a loop until the user exits.

### Example Interaction
#### **User Input:**
```
Enter your favorite movie name: Inception
```
#### **Recommended Movies:**
```
Movies suggested for you:
1. Interstellar
2. The Prestige
3. Shutter Island
4. Memento
5. The Matrix
...
```

## Future Enhancements
- **Hybrid Filtering**: Combining content-based and collaborative filtering for better recommendations.
- **Real-Time Movie API Integration**: Fetching updated movie data from IMDB or TMDB.
- **Web Interface**: Creating a user-friendly web-based recommendation platform.
- **Deep Learning Models**: Exploring NLP-based movie recommendation using transformers.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit and push your changes (`git push origin feature-branch`).
4. Open a pull request for review.

## License
This project is licensed under the **MIT License**, allowing for open-source contributions and modifications.

---
**CineMatch** is designed to provide **intelligent movie recommendations** and enhance the way users discover films. 🎬✨

