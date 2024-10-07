# UTS Autumn 2023 Assessment: NBA Player Career Forecast

This project predicts whether a basketball player's career will last longer than 5 years based on performance stats, using **EDA**, **data preprocessing**, and **Scikit-learn** for classification.

### Steps:
1. **EDA**: Explored player stats such as points, rebounds, and assists.
2. **Data Preprocessing**: Cleaned data e.g. removing outliers.
3. **Modeling**: Utilized multiple classifiers to predict career longevity (>5 years) using player performance metrics.

### Models Used:
- **Random Forest**
- **SVM**
- **Decision Tree**
- **Neural Network**
- **KNN Classifiers**

The notebook compares model performances using **ROC curves** and **confusion matrices**.

### Main Dataset Attributes:
- **GP** (Games Played)
- **PTS** (Points Per Game)
- **AST** (Assists)
- **REB** (Rebounds)
- **TARGET_5Yrs** (1 if career >5 years, 0 otherwise)

**Results**: Check the competition leaderboard [here](https://www.kaggle.com/competitions/31250-uts-autumn-2023/leaderboard?tab=public)
