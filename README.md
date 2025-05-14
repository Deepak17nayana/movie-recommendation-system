# 🎬 Movie Recommendation System

A hybrid movie recommendation system built using Collaborative Filtering (SVD), Content-Based Filtering (TF-IDF & Cosine Similarity), and a simple user interface. This project demonstrates how machine learning can be used to build intelligent systems that understand user preferences and suggest relevant movies.

---

## 🚀 Features

- ✅ Collaborative Filtering using SVD (Surprise Library)
- ✅ Content-Based Filtering using TF-IDF & Cosine Similarity
- ✅ Hybrid Recommendations
- ✅ User-friendly command-line interactions
- ✅ Clean and modular codebase

---

## 📁 Project Structure

movie_recommendation_project/
│
├── data/ # Movie and rating datasets (movies.csv, ratings.csv)
├── models/ # Recommendation algorithms (SVD model, TF-IDF)
├── scripts/ # Data preprocessing and evaluation scripts
├── README.md # Project documentation
└── main.py # Main execution script

---

## 🛠️ Installation

 Clone the repository:

```bash
git clone https://github.com/Deepak17nayana/movie-recommendation-system.git
cd movie-recommendation-system

Install the required libraries:

pip install -r requirements.txt

🔧 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Surprise (SVD)

Matplotlib (for evaluation, if needed)

💡 How It Works

Collaborative Filtering: Learns from user-item interactions to predict ratings.

Content-Based Filtering: Uses genres/titles/descriptions to find similar movies.

Hybrid Model: Combines both for better accuracy.

📊 Sample Output

Top 10 Recommended Movies for User 1:
1. Inception
2. The Dark Knight
3. Interstellar


👨‍💻 Author
Deepak Reddy
Gitam University


📃 License
This project is open-source and free to use under the MIT License.