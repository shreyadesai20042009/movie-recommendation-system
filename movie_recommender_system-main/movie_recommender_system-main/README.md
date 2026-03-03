# 🎬 Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

An intelligent Movie Recommendation System built in Python using machine learning techniques.  
This system suggests movies similar to a selected title based on features such as movie metadata and similarity scores.

---

## 🧠 Project Overview

Recommender systems are widely used in modern apps like Netflix, Amazon, and YouTube to suggest relevant content.  
This system uses **content-based filtering**, where movies are compared using feature similarity to generate meaningful recommendations.

📌 Recommended movies are based on similarity scores calculated between movie features.

---

## 🚀 Features

✨ Takes a movie title as input  
✨ Recommends similar movies  
✨ Uses cosine similarity or other similarity metrics  
✨ Simple and interactive UI (if using Streamlit)  
✨ Can be extended to include posters, genre filters, or external API integration :contentReference[oaicite:0]{index=0}

---

## 📁 Project Structure


movie_recommender_system-main/
├── data/
│ ├── movies.csv
│ ├── credits.csv
│ └── ...
├── model/
│ └── similarity.pkl
├── main.py
├── app.py
├── utils.py
├── requirements.txt
└── README.md


---

## 🛠 Tech Stack

- 🐍 Python  
- 📊 pandas & numpy  
- 🧠 Scikit-learn (cosine similarity, TF-IDF / vectorization)  
- 🎯 Streamlit for UI (optional)  
- 🏷️ Dataset: Movie metadata (could be TMDB / IMDb)

---

## 💻 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/shreyadesai20042009/movie-recommendation-system.git
cd movie-recommender_system-main/movie_recommender_system-main
2️⃣ Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
3️⃣ Install dependencies
pip install -r requirements.txt
▶️ Usage
🧠 Basic Python script

Run the main recommendation script:

python main.py

Follow the instructions on screen to input a movie title and get similar movie suggestions.

🌐 If your repo has a Streamlit app

Run:

streamlit run app.py

Open a web browser and go to:

http://localhost:8501

You can select a movie and view recommendations interactively.

📊 Example Output
Enter a movie title: The Dark Knight
Getting recommendations...
1. Batman Begins
2. The Dark Knight Rises
3. Joker
