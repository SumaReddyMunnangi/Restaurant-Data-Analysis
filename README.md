# Restaurant Data Analysis

## Project Overview
This project focuses on analyzing restaurant data using machine learning techniques. The main objectives include:
- **Predicting Restaurant Ratings** using regression models.
- **Recommending Restaurants** based on user preferences using content-based filtering.
- **Classifying Cuisines** with machine learning classification algorithms.
- **Performing Location-Based Analysis** to visualize restaurant distribution and city-wise insights.

## Dataset
The dataset contains information about restaurants, including:
- Restaurant name, city, address, and geographical coordinates.
- Cuisines offered and price range.
- Aggregate ratings, number of votes, and availability of online services.

## Tasks & Implementation

### 1. Restaurant Rating Prediction
**Goal:** Build a machine learning model to predict restaurant ratings based on various features.
- Preprocessed data by handling missing values and encoding categorical variables.
- Used regression models (e.g., Linear Regression, Decision Tree) to predict ratings.
- Evaluated model performance using metrics like Mean Squared Error and R-squared.

### 2. Restaurant Recommendation System
**Goal:** Recommend restaurants to users based on their preferences.
- Implemented a content-based filtering approach.
- Used cosine similarity to find restaurants with similar cuisines, price ranges, and ratings.
- Provided personalized recommendations based on user preferences.

### 3. Cuisine Classification
**Goal:** Classify restaurants based on their cuisines using machine learning.
- Vectorized cuisine data using TF-IDF (Term Frequency-Inverse Document Frequency).
- Trained a Random Forest Classifier for multi-class classification.
- Evaluated model performance using accuracy, precision, and recall.

### 4. Location-Based Analysis
**Goal:** Analyze restaurant distribution geographically.
- Visualized restaurant locations using latitude and longitude scatter plots.
- Grouped restaurants by city to calculate average ratings, price ranges, and vote counts.
- Created an interactive map using Folium to visualize restaurant locations dynamically.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Folium, TfidfVectorizer

## How to Run the Project
1. Install required dependencies using:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn folium
   ```
2. Load the dataset (`Dataset.csv`).
3. Run the Python script to execute all tasks.
4. Check the results for rating predictions, recommendations, classification reports, and interactive maps.

## Results & Insights
- Machine learning models successfully predicted restaurant ratings with good accuracy.
- The recommendation system provided relevant suggestions based on user preferences.
- Cuisine classification effectively categorized restaurants into different cuisine types.
- Location-based analysis revealed interesting geographical trends in restaurant distribution.

## Future Improvements
- Enhance the recommendation system using collaborative filtering.
- Improve cuisine classification with deep learning models.
- Add real-time data updates and dynamic restaurant insights.

## Author
This project was developed as part of an internship program.
Munnangi Suma Reddy

