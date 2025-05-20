# 🎬 Movie Recommendation System

This project implements a **collaborative filtering-based movie recommendation system** using the MovieLens dataset. The system predicts user preferences for movies based on historical user-item interactions, utilizing user-based and item-based collaborative filtering techniques.

---

## 📁 Repository Contents

- `Recommendation System.ipynb`: Jupyter Notebook containing the implementation of the recommendation algorithms.
- `u.data`: User rating data from the MovieLens dataset.
- `Movie_Id_Titles.txt`: Mapping of movie IDs to movie titles.
- `README.md`: Project documentation.

---

## 🎯 Objectives

- Explore and preprocess the MovieLens dataset.
- Implement user-based and item-based collaborative filtering algorithms.
- Predict user ratings for movies they haven't rated yet.
- Recommend top-N movies to users based on predicted ratings.

---

## 🛠️ Tools & Libraries

- **Python 3.x**
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive computing environment.

---

## 📊 Methodology

1. **Data Loading & Preprocessing**:
   - Load user ratings and movie titles.
   - Merge datasets to create a comprehensive user-item matrix.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of ratings.
   - Identify the most rated and highest-rated movies.

3. **Collaborative Filtering**:
   - **User-Based Filtering**: Recommend movies by finding similar users based on rating patterns.
   - **Item-Based Filtering**: Recommend movies similar to those a user has liked.

4. **Prediction & Recommendation**:
   - Calculate similarity scores.
   - Predict ratings for unrated movies.
   - Recommend top-N movies with the highest predicted ratings.

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/achyuthkumarmiryala/Recommendation-System.git
   cd Recommendation-System
   ```

2. **Install Dependencies**:
   Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook "Recommendation System.ipynb"
   ```

---

## ✅ Results

The recommendation system successfully identifies movies that a user is likely to enjoy based on collaborative filtering techniques. The system demonstrates the effectiveness of using historical user behavior to predict future preferences.

---

## 📌 Dataset Source

The dataset used is the [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/100k/), which contains 100,000 ratings from 943 users on 1,682 movies.

---

## 👤 Author

**Achyuth Kumar Miryala**  
Master’s in Data Science | University of North Texas  
📍 Denton, TX  
📫 [achyuthkumar286@gmail.com](mailto:achyuthkumar286@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/) | [GitHub](https://github.com/achyuthkumarmiryala)

---

## 📄 License

This project is intended for academic and educational purposes. For any other use, please contact the author.

---

If you find this project insightful, feel free to ⭐ the repository or connect on [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/)!
