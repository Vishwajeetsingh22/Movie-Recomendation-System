# 🎬 Movie Recommendation System

A **Machine Learning-based Movie Recommendation System** that recommends movies to users based on movie-related features and similarity. The project uses Python and Flask to provide an interactive recommendation experience.

---

## 📌 Project Overview

The **Movie Recommendation System** is designed to help users discover movies similar to their selected movie.

The system processes movie data, trains a recommendation model, and generates a list of movies that are most similar to the user's selected movie.

### 🎯 Objective

* Recommend movies based on user selection.
* Find movies with similar characteristics.
* Use Machine Learning techniques for recommendation.
* Provide a simple web-based interface using Flask.

---

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Machine Learning**
* **HTML/CSS** *(if used in the Flask interface)*

---

## 📂 Project Structure

```text
Movie-Recomendation-System/
│
├── app.py
├── train_model.py
├── movie_recommender.py
├── load_and_recommend (1).py
├── run bash.txt
└── README.md
```

### 📄 File Description

| File                        | Description                                           |
| --------------------------- | ----------------------------------------------------- |
| `app.py`                    | Runs the Flask web application                        |
| `train_model.py`            | Trains and prepares the recommendation model          |
| `movie_recommender.py`      | Contains the movie recommendation logic               |
| `load_and_recommend (1).py` | Loads the trained model and generates recommendations |
| `run bash.txt`              | Contains commands/instructions to run the project     |
| `README.md`                 | Project documentation                                 |

---

## ⚙️ How It Works

```text
User Selects a Movie
        ↓
Movie Data Processing
        ↓
Feature Extraction
        ↓
Similarity Calculation
        ↓
Recommendation Model
        ↓
Similar Movies
        ↓
Display Recommendations
```

The system analyzes movie features and calculates similarity between movies. Based on the selected movie, the system returns a list of similar movies.

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Vishwajeetsingh22/Movie-Recomendation-System.git
```

### 2. Navigate to the Project

```bash
cd Movie-Recomendation-System
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn flask
```

---

## ▶️ Running the Project

First, train the model:

```bash
python train_model.py
```

Then start the Flask application:

```bash
python app.py
```

Open the local URL shown in the terminal, usually:

```text
http://127.0.0.1:5000/
```

---

## 🎥 Features

* 🎬 Movie-based recommendations
* 🤖 Machine Learning-powered recommendation
* 🔎 Similar movie identification
* 🌐 Flask web application
* 🐍 Python implementation
* ⚡ Simple and user-friendly interface

---

## 📸 Screenshots

Add screenshots of your application here:

### Home Page

```markdown
![Home Page](screenshots/home.png)
```

### Movie Recommendations

```markdown
![Recommendations](screenshots/recommendations.png)
```

> Create a `screenshots` folder in the repository and upload your application screenshots.

---

## 🔮 Future Enhancements

Future improvements could include:

* User login and personalized profiles
* Rating-based recommendations
* Genre-based filtering
* Collaborative filtering
* Hybrid recommendation system
* Movie posters and trailers
* Search and autocomplete
* Recommendation history
* Deployment using cloud platforms

---

## 👨‍💻 Author

**Vishwajeet Singh  **

25MCAR0219

JAIN (DEEMED-TO-BE-UNIVERSITY)

MCA Student | Machine Learning & AI Enthusiast

---

## 🔗 Repository

**GitHub:** [Movie-Recomendation-System](https://github.com/Vishwajeetsingh22/Movie-Recomendation-System)

---

## 📜 License

This project is developed for **educational and academic purposes**.

---

### ⭐ If you find this project useful, consider giving the repository a star!
