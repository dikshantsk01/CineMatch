# 🎬 CineMatch – Movie Recommendation System

CineMatch is a content-based movie recommendation system built using Python and Machine Learning techniques. The system recommends movies similar to a user's favorite movie by analyzing genres, keywords, cast, director, and taglines. It leverages TF-IDF Vectorization and Cosine Similarity to identify patterns and relationships between movies and generate accurate recommendations.

## 🚀 Features

- Content-based movie recommendation engine
- TF-IDF Vectorization for text feature extraction
- Cosine Similarity for similarity computation
- Fuzzy movie title matching using difflib
- Fast and lightweight recommendation system
- Beginner-friendly implementation using Python

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Difflib

## 📂 Dataset

The dataset contains movie information such as:

- Title
- Genres
- Keywords
- Tagline
- Cast
- Director

These attributes are combined into a single feature vector for recommendation generation.

## ⚙️ How It Works

1. Load and preprocess movie data.
2. Select important movie attributes.
3. Combine features into a single text column.
4. Convert text data into numerical vectors using TF-IDF.
5. Compute pairwise movie similarities using Cosine Similarity.
6. Accept a movie title from the user.
7. Find the closest matching movie title using difflib.
8. Recommend the most similar movies based on similarity scores.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/dikshantsk01/CineMatch.git
cd CineMatch
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Run the application:

```bash
python main.py
```

Example:

```text
Enter your favourite movie: Avatar

Movies suggested for you:

1. Guardians of the Galaxy
2. John Carter
3. Star Trek
4. The Fifth Element
5. Ender's Game
```

## 📁 Project Structure

```text
CineMatch/
│
├── data/
│   └── movies.csv
│
├── main.py
├── requirements.txt
└── README.md
```

## 🎯 Future Improvements

- Web interface using Flask or Streamlit
- Integration with TMDB API
- Movie poster support
- User authentication and watchlists
- Hybrid recommendation system
- Deployment on cloud platforms

## 📈 Learning Outcomes

This project demonstrates:

- Data Preprocessing
- Feature Engineering
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Recommendation Systems
- Machine Learning Fundamentals

## 🏆 Resume Highlights

- Developed a content-based movie recommendation system using Python and Scikit-learn.
- Applied TF-IDF Vectorization and Cosine Similarity to generate personalized movie recommendations.
- Implemented feature engineering on genres, keywords, cast, director, and taglines.
- Built a fuzzy matching system using difflib to handle user input errors.
- Designed an end-to-end recommendation pipeline capable of finding similar movies efficiently.

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

## 📜 License

This project is licensed under the MIT License.
