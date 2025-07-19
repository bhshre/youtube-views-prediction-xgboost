# YouTube Video Performance Prediction 🎯

This project uses an XGBoost regression model to predict the number of views a YouTube video will get based on features like title length, likes, comments, and upload day.

## 🔍 Problem Statement
To predict YouTube video views using metadata and engagement metrics.

## 📂 Dataset
- Contains features such as `title`, `likes`, `comments`, `shares`, and `day`.
- Cleaned, preprocessed, and engineered for modeling.

## 📊 EDA
- Correlation heatmap to understand relationships between features
- Skewness analysis of views

## 🤖 Model Used
- XGBoost Regressor  
  - n_estimators = 100  
  - learning_rate = 0.1  
  - max_depth = 5

## 📈 Performance
- **RMSE**: 32.65 (Lower is better)
- **R² Score**: 0.99 (Very good fit)

## 🔍 Feature Importance
Likes and Comments are most predictive of view count.

## ✅ Conclusion
- XGBoost performs exceptionally well in predicting views.
- Feature engineering like extracting `day_of_week` improves accuracy.
- Model can help content creators estimate expected video performance.

## 🛠️ Tools Used
- Python, Pandas, Matplotlib, Seaborn, XGBoost, Scikit-learn, Google Colab

## 📌 How to Run
Clone this repo and open the `.ipynb` file in Google Colab.

## 📎 Author
[Your Name] | [LinkedIn](#) | [Portfolio](#)
