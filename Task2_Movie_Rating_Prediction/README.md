# 🎬 Task 2 - Movie Rating Prediction

### 📌 Problem Statement
The goal is to build a regression model that predicts the **IMDB rating of a movie** based on available features.  
For simplicity (to ensure fast training in Colab), we used **Votes** as the main predictor of `Rating`.  

---

### 📊 Dataset
- Source: [IMDB India Movies Dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)
- File used: `IMDb India Movies.csv`

---

### 🛠️ Steps Performed
1. **Data Cleaning**
   - Removed rows with missing ratings.  
   - Converted `Votes` column to numeric and filled missing values with median.  

2. **Feature Selection**
   - Used `Votes` as the predictor feature.  
   - Target variable = `Rating`.  

3. **Model Training**
   - Applied **Linear Regression** from scikit-learn.  

4. **Evaluation**
   - Metrics used: **Mean Squared Error (MSE)** and **R² Score**.  

---

### ✅ Results
- Model successfully predicts ratings with a reasonable accuracy.  
- Since Votes are strongly related to Ratings, the model shows a positive relationship.  
- (Your R² score may vary slightly depending on dataset split).  

---

### 📂 Files
- `CODSOFT_Task2_Movie_Rating_Prediction.ipynb` → Colab Notebook with code  
- `README.md` → Documentation  

---

### 🚀 Author
- Jahnvi Khurana
