🎬 Movie Recommendation System
📌 Project Overview
The Movie Recommendation System is designed to provide personalized movie suggestions using a hybrid approach that combines Collaborative Filtering and Content-Based Filtering. By leveraging Big Data Analytics tools like PySpark, this system efficiently processes large-scale movie datasets, enabling faster and more accurate recommendations. The primary goal of this project is to overcome the common limitations of traditional recommendation techniques, such as the cold start problem and data sparsity issues, by integrating multiple filtering methods. The hybrid approach ensures that users receive relevant, diverse, and engaging movie recommendations based on both their past interactions and the content similarities of movies.

🚀 Features
This project incorporates several advanced features to enhance the recommendation process. The Hybrid Recommendation System blends Collaborative Filtering, which understands user preferences based on interactions, with Content-Based Filtering, which analyzes movie metadata to identify similar films. It also utilizes Big Data Processing through PySpark, ensuring scalability for handling vast datasets. Movie Similarity Computation is achieved using TF-IDF and Cosine Similarity, allowing the system to generate meaningful content-based recommendations. Furthermore, Alternating Least Squares (ALS) is implemented to build a robust Collaborative Filtering model, improving the accuracy of suggestions. The entire system is structured as a Scalable Machine Learning Pipeline, making it adaptable for large-scale deployments.

🛠️ Tech Stack
The project is built using Python as the core programming language, with PySpark serving as the primary Big Data framework for handling large-scale computations efficiently. The machine learning models implemented include ALS for Collaborative Filtering and TF-IDF with CountVectorizer for Content-Based Filtering. Data processing is conducted using Pandas and NumPy, while Matplotlib and Seaborn are used for visualization purposes. Version control is managed through Git, ensuring seamless collaboration and code management. The system is designed with modularity, allowing easy integration with Flask or Streamlit for web-based deployment in the future.

📂 Dataset
The project utilizes data from the MovieLens dataset, which is widely used for recommendation system research. It consists of two key components: the Movies Dataset, containing attributes such as movieId, title, and genres, and the Ratings Dataset, which includes userId, movieId, and rating values. These datasets are preprocessed to remove inconsistencies, normalize text fields, and generate structured feature vectors for recommendation. The Movies Dataset helps extract content-based features like genres and TF-IDF scores, while the Ratings Dataset enables user preference modeling for collaborative filtering. By combining both datasets, the system ensures that recommendations are both personalized and diverse.

🔥 Model Performance
The Collaborative Filtering model, powered by ALS, predicts user preferences based on past ratings and similar user behaviors. The Content-Based Filtering approach utilizes TF-IDF and Cosine Similarity to recommend movies that share textual or categorical similarities. Finally, the Hybrid Model combines both methods, producing superior recommendations compared to standalone approaches. The system achieves high accuracy in ranking movie suggestions by adjusting the weight of collaborative and content-based scores. Additionally, evaluation metrics like Root Mean Square Error (RMSE) and correlation heatmaps are used to assess the model’s effectiveness, confirming its ability to provide highly relevant movie recommendations.

📊 Results and Observations
The hybrid approach significantly improves recommendation accuracy compared to traditional methods. The top 10 hybrid recommendations are displayed for each user, showcasing the combined effectiveness of collaborative and content-based techniques. Additionally, content-based recommendations provide a list of movies that closely match a given film’s genre, title, or description. A correlation heatmap is generated to compare actual vs. predicted ratings, revealing strong alignment in user preferences. The system’s RMSE score of 0.81267 indicates a high level of prediction accuracy. The most recommended movies include films with consistently high ratings across multiple users, demonstrating the model’s ability to capture popular and user-specific preferences effectively.


📌 Future Enhancements
The current system is designed for batch processing, but future enhancements can incorporate real-time recommendations by integrating Apache Kafka for streaming data. Additionally, Deep Learning techniques, such as Neural Collaborative Filtering (NCF), can further refine predictions. Deployment as a fully interactive web application using Flask or Streamlit is another goal, making the system accessible to users worldwide. Other improvements include API integration with real-time movie databases, such as IMDb or TMDb, to provide the latest movie recommendations.

🤝 Contributors
This project was developed by Amrit Raj and Snehasish Kabi, under the guidance of Dr. Lakshmi Shree K. Contributions from the open-source community are welcome to enhance the system further.

📝 License
This project is open-source and available under the MIT License. Feel free to modify, extend, and share it for academic or commercial use. For any contributions, submit a pull request on GitHub.

This README provides a detailed, structured, and engaging description of your Movie Recommendation System project. Let me know if you’d like any modifications or additions! 🚀
