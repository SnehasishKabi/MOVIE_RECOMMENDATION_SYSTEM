

# 🎬 Movie Recommendation System

## 📌 Overview

The **Movie Recommendation System** is a hybrid recommendation engine that provides personalized movie suggestions by combining **Collaborative Filtering** and **Content-Based Filtering**. Designed with scalability in mind, the system leverages **Big Data Analytics tools** like **PySpark** to process large-scale datasets efficiently. Its primary objective is to overcome the limitations of traditional recommendation methods—such as the cold start problem and data sparsity—by integrating multiple filtering techniques. The result is a recommendation engine that delivers relevant, diverse, and engaging suggestions.

---

## 🚀 Features

* **Hybrid Recommendation Engine**
  Blends Collaborative Filtering (user-item interactions) and Content-Based Filtering (movie metadata analysis) for more robust recommendations.

* **Big Data Processing with PySpark**
  Ensures scalable performance on large datasets.

* **Movie Similarity Calculation**
  Uses **TF-IDF** and **Cosine Similarity** for meaningful content-based recommendations.

* **Collaborative Filtering using ALS**
  Implements the **Alternating Least Squares** algorithm to model user preferences and enhance suggestion accuracy.

* **Scalable Machine Learning Pipeline**
  Designed to support modular, large-scale deployments with ease.

---

## 🛠️ Tech Stack

* **Languages & Libraries**: Python, NumPy, Pandas
* **Big Data Framework**: PySpark
* **Machine Learning Models**: ALS (Collaborative Filtering), TF-IDF + CountVectorizer (Content-Based)
* **Visualization**: Matplotlib, Seaborn
* **Version Control**: Git
* **Web Integration (Planned)**: Flask / Streamlit for future deployment

---

## 📂 Dataset

The system uses the [**MovieLens**](https://grouplens.org/datasets/movielens/) dataset, a benchmark dataset for movie recommendation systems.

* **Movies Dataset**
  Contains `movieId`, `title`, and `genres` used for metadata and content-based filtering.

* **Ratings Dataset**
  Contains `userId`, `movieId`, and `rating`, essential for collaborative filtering.

Data preprocessing includes:

* Removing inconsistencies
* Normalizing text fields
* Generating structured feature vectors for modeling

---

## 🔥 Model Performance

* **Collaborative Filtering** (ALS): Learns user preferences from rating patterns.
* **Content-Based Filtering**: Recommends similar movies based on metadata using TF-IDF + Cosine Similarity.
* **Hybrid Model**: Combines both approaches for superior results.

**Evaluation Metrics**:

* **Root Mean Square Error (RMSE)**: Achieved a score of **0.81267**, indicating high prediction accuracy.
* **Correlation Heatmap**: Shows strong alignment between actual and predicted ratings.

---

## 📊 Results and Observations

* The hybrid approach significantly improves accuracy over standalone models.
* **Top 10 personalized recommendations** are generated for each user.
* Content-based filtering provides movie suggestions similar to a selected film by genre or title.
* Heatmaps and RMSE scores validate the system's performance.
* Highly recommended movies often have high ratings across diverse users, showing both popularity and personalization.

---

## 📌 Future Enhancements

* **Real-Time Recommendations**
  Integrate **Apache Kafka** to handle streaming data.

* **Deep Learning Integration**
  Incorporate models like **Neural Collaborative Filtering (NCF)**.

* **Web Deployment**
  Launch as an interactive web app using **Flask** or **Streamlit**.

* **API Integration**
  Connect with **IMDb** or **TMDb** APIs for real-time movie metadata.

---

## 🤝 Contributors

Developed by:

* **Amrit Raj**
* **Snehasish Kabi**
  Under the guidance of **Dr. Lakshmi Shree K.**

*Open-source contributors are welcome! Feel free to fork, enhance, and submit pull requests.*

---

## 📝 License

This project is released under the **[MIT License](LICENSE)**.
Use it freely for academic or commercial purposes. Contributions and improvements are highly encouraged!

---

Would you like a version formatted as a Markdown file (`README.md`) for GitHub?
