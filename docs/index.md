# Data Analytics Portfolio

---

## Music Recommendation System

### Project Overview

The **Music Recommendation System** project focuses on providing personalized music recommendations based on user preferences. By utilizing **machine learning algorithms** and data from the **Spotify API**, the system recommends new songs based on a user’s listening history and favorite artists.

This project is part of my data analytics portfolio, where I apply various data science methodologies such as **data preprocessing**, **feature engineering**, and **model optimization** to build intelligent recommendation systems.

---

### Objective

The main goal of this project is to:
- Build a music recommendation model that suggests songs tailored to the user's taste.
- Analyze a **Spotify dataset** and use **machine learning algorithms** to improve recommendation accuracy.

---

### Key Features

1. **Spotify API Integration**:
   - Using **Spotipy**, a Python library for Spotify's Web API, I gathered data on songs, artists, and playlists.
   - Extracted song metadata like **audio features**, genres, and popularity scores to enrich the dataset.

2. **Data Preprocessing**:
   - Cleaned and transformed the data to ensure consistency across various features such as **tempo**, **danceability**, and **energy**.
   - Handled missing values and outliers for improved model performance.

3. **Feature Engineering**:
   - Engineered new features to improve recommendation accuracy based on song attributes.
   - Normalized numerical features to ensure all input data was on the same scale.

4. **Model Development**:
   - Implemented a **K-Nearest Neighbors (KNN)** algorithm to find similar tracks based on user preferences.
   - Used **hyperparameter optimization** to improve model precision and recall.

5. **Evaluation & Tuning**:
   - Evaluated the model’s precision, recall, and **F1-score** using various performance metrics.
   - Visualized performance using **learning curves** and confusion matrices to refine recommendations.

6. **Recommendation Output**:
   - Generated personalized playlists for users based on their favorite tracks.
   - Provided explanations for why certain songs were recommended, based on audio feature similarities.

---

### Project Details

- **Jupyter Notebook**: [Download the notebook here](./music-recommendation-system.ipynb).
- **Dataset**: [Download the dataset here](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks)

---

### Methodology

1. **Data Collection**:
   - Extracted song data using **Spotipy** from Spotify's API.
   - Collected important audio features such as:
     - Acousticness
     - Danceability
     - Energy
     - Instrumentalness
     - Tempo
     - Valence

2. **Exploratory Data Analysis (EDA)**:
   - Performed data analysis to identify patterns and trends in music preferences across genres.

3. **Modeling**:
   - Built a recommendation engine using a **KNN algorithm** for collaborative filtering.
   - Automated the recommendation pipeline for generating personalized playlists.

4. **Performance Evaluation**:
   - Assessed the model’s performance using **Precision-Recall Curves** to understand its accuracy.
   - Used confusion matrices to evaluate false positives and negatives in recommendations.

5. **Improvements**:
   - Refined the model based on insights from learning curves, making adjustments to handle overfitting.

---

### Tools & Technologies

- **Python**: For all aspects of data analysis, processing, and modeling.
- **Spotipy**: To interface with the Spotify Web API.
- **Pandas & NumPy**: For data wrangling and manipulation.
- **Scikit-learn**: For building and fine-tuning machine learning models.
- **Matplotlib & Seaborn**: For data visualization and insights.

---


### Results

- Achieved highly accurate music recommendations with strong **precision** and **recall** scores.
- Generated personalized playlists that closely matched the user’s preferences based on their prior music history.

---

### Future Enhancements

1. **Deep Learning**:
   - Experiment with **neural networks** to capture more complex patterns in the data and improve recommendations.
   - Explore **recurrent neural networks (RNNs)** to model time-series data for songs.

2. **Real-time Playlist Updates**:
   - Incorporate real-time updates, allowing the model to dynamically learn from user behavior and improve recommendations.

3. **User Interface Development**:
   - Build a web-based UI using **Flask** or **Streamlit** where users can input their preferences and receive recommendations instantly.

---

### Access the Project

- **View the Jupyter Notebook**: [music-recommendation-system.ipynb](./music-recommendation-system.ipynb)
- **HTML Version of the Project**: [music-recommendation-system.html](./music-recommendation-system.html)

---

### Other Projects in My Portfolio

- [Visit My GitHub Portfolio](https://github.com/reyhaanbinny)

---

### Contact

For any questions or collaboration inquiries, feel free to reach out:

- **Email**: reyhaanbinny97@gmail.com
- **LinkedIn**: [linkedin.com/in/reyhaanbinny](https://www.linkedin.com/in/reyhaanbinny)
