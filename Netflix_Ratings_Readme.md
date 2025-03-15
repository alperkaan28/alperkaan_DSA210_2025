# Netflix Ratings Analysis

## **Description**

This project explores Netflix movie and TV show ratings to uncover trends in viewer preferences. Instead of simple comparisons, we will apply **statistical tests and machine learning models** to analyze key patterns in audience ratings. By studying factors such as genre, release year, and country of production, we aim to uncover deeper insights into what influences a movie's rating.

## **Dataset**

- **Source:** Publicly available datasets from Kaggle.
- **Data Fields:**
  - Movie/Show Title
  - Genre(s)
  - Release Year
  - Rating Score
  - Netflix Original (Yes/No)
  - Country of Origin
  - Duration (Minutes)

## **Project Goals**

1. **Find Deeper Trends in Ratings:**
   - Identify which genres tend to receive more extreme ratings (very high or very low) and whether this is statistically significant.
   - Use clustering techniques to group movies based on rating behavior.
   
2. **Statistical Analysis of Netflix Originals:**
   - Instead of a simple Netflix Original vs. Non-Original comparison, perform **hypothesis testing** to check whether the difference in ratings is significant.
   - Examine the distribution of ratings to see if Netflix Originals tend to be more polarizing (i.e., receive more extreme ratings).
   
3. **Country & Release Year Influence on Ratings:**
   - Use **correlation analysis** to check if movies from specific countries consistently receive higher/lower ratings.
   - Perform **trend analysis** on rating changes over the years.
   
4. **Predicting Movie Ratings with Machine Learning:**
   - Develop a regression model to estimate ratings based on metadata (genre, country, runtime, etc.).
   - Use feature importance analysis to determine which factors contribute most to high ratings.

## **Plan**

### **Data Collection & Cleaning**

- Load Netflix dataset from Kaggle.
- Remove missing or inconsistent values.

### **Exploratory Data Analysis (EDA)**

- Analyze the distribution of ratings across different **genres**.
- Identify **rating trends over time**.
- Use clustering techniques to explore patterns in audience preferences.

### **Feature Engineering**

- Convert categorical features (genre, country) into numerical representations.
- Create new features such as "polarity score" to measure rating consistency.

### **Modeling & Predictions**

- **Regression Models:** Predict the exact rating score using metadata.
- **Clustering:** Group movies based on audience rating behavior.
- **Hypothesis Testing:** Verify if trends in ratings are statistically significant.
- **Evaluation Metrics:** Use RMSE for regression models and silhouette scores for clustering.

### **Visualization**

- Heatmaps for correlation analysis between different movie attributes and ratings.
- Distribution plots to analyze rating polarization.
- Feature importance graphs to highlight key rating predictors.

### **Documentation**

- Summarize insights and present findings in a structured report.
