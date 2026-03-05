🎬 Movie Recommendation System
📌 Project Overview

The Movie Recommendation System is a machine learning–based web application that suggests movies similar to the movie selected by the user. The system analyzes movie metadata such as genre, cast, and keywords to find similarities between movies and recommend relevant titles.

The application is built using Python, Machine Learning techniques, and Streamlit to provide an interactive web interface. It helps users easily discover movies they may enjoy based on their preferences.

🚀 Features

🎥 Recommend movies similar to the selected movie

🔍 Search functionality to find movies quickly

🤖 Machine Learning based recommendation engine

📊 Uses movie metadata for similarity calculation

🌐 Interactive web interface using Streamlit

⚡ Fast recommendations using pre-trained models

Recommendation systems typically analyze movie features and compute similarity scores between movies to suggest relevant titles.

🛠️ Technologies Used

Python

Streamlit

Pandas

NumPy

Scikit-learn

Pickle

TMDB Movie Dataset

📂 Project Structure
movie-recommendation-system
│
├── app.py                     # Main Streamlit application
├── movies.pkl                 # Processed movie dataset
├── similarity.pkl             # Movie similarity matrix
├── tmdb_5000_movies.csv       # Movie dataset
├── tmdb_5000_credits.csv      # Credits dataset
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
📊 Dataset

This project uses the TMDB 5000 Movie Dataset, which includes:

Movie titles

Genres

Cast and crew information

Keywords

Movie descriptions

The dataset helps generate recommendations based on movie similarity.

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/shreyadesai20042009/movie-recommendation-system.git
cd movie-recommendation-system
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the application
streamlit run app.py
4️⃣ Open in browser
http://localhost:8501
💡 How It Works

The dataset is preprocessed to extract important movie features.

Text features such as genres, cast, and keywords are combined.

A vectorization technique is applied to convert text into numerical vectors.

Cosine similarity is used to calculate similarity between movies.

When a user selects a movie, the system recommends the most similar movies.

📸 Application Workflow

1️⃣ User selects a movie from the dropdown
2️⃣ Clicks the Recommend button
3️⃣ System calculates similarity
4️⃣ Top recommended movies are displayed
