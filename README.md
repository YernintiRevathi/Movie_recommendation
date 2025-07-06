# Movie Recommendation System

**An intelligent, content-based movie recommendation system built using Python and machine learning techniques.**

---

## 🎬 Project Overview

This project simulates a **personal AI movie curator**. By analyzing plot descriptions of movies, it recommends titles that share narrative similarity with a given input movie using a content-based filtering approach.

The system relies on **TF-IDF vectorization** and **cosine similarity** to compare the storyline of movies and generate recommendations based purely on the content — not user ratings or behavior.

---

## 👥 User Experience

* **Enter a movie title** you like.
* The system analyzes its description and compares it with the rest of the dataset.
* It returns a list of **similar movies** based on content relevance.

No login, setup, or internet access required — just run and get personalized results.

---

## 🧠 Technologies & Skills Used

### 💻 Machine Learning & NLP:

* **TF-IDF (Term Frequency–Inverse Document Frequency)**
* **Cosine Similarity** for distance measurement between movies

### 📊 Data Handling:

* **Pandas** for data manipulation
* **Scikit-learn** for feature extraction and similarity computation

### 🐍 Python:

* Efficient and readable scripting
* Modular logic in a clean, functional format

---

## 📂 File Structure

* `movie.py`: Main file with recommendation logic
* `movies.csv`: Dataset containing movie titles and plot descriptions

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YernintiRevathi/Movie_recommendation.git
   cd Movie_recommendation
   ```
2. Install dependencies:

   ```bash
   pip install pandas scikit-learn
   ```
3. Run the script:

   ```bash
   python movie.py
   ```
4. Input your favorite movie name when prompted and enjoy your curated list!

---

## ✨ Highlights

* Fast and lightweight — no need for deep learning or GPUs
* Easy to understand and extend
* Great for learning about content-based recommendation systems

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

**Built with 🎥 and 💻 by [Revathi Yerninti](https://github.com/YernintiRevathi)**
