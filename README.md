# **Analyzing Global Happiness:** A Data-Driven Approach to Understanding Contributing Factors

## Overview
This project analyzes the World Happiness Report dataset (2021) to identify factors contributing to happiness across countries. It features comprehensive Exploratory Data Analysis (EDA) and uses machine learning models to predict happiness scores ("Ladder Score") based on critical features.

## Dataset
The dataset, derived from the **World Happiness Report 2021**, includes variables such as:
- **Country name**: Name of the country.
- **Ladder score**: The happiness score for the country.
- **Logged GDP per capita**: Economic prosperity indicator.
- **Social support**: Perceived social support index.
- **Healthy life expectancy**: Average life expectancy in years.
- **Freedom to make life choices**: Index of perceived freedom.
- **Generosity**: Generosity index.
- **Perceptions of corruption**: Corruption perception index.
- Additional explanatory and regional indicators.

## Project Objectives
1. **Exploratory Data Analysis (EDA):**
   - Analyze distributions, relationships, and regional trends in happiness factors.
   - Create visualizations, such as boxplots, heatmaps, and scatter plots.

2. **Machine Learning Techniques:**
   - Predict happiness scores using regression models.
   - Evaluate model performance and interpret key insights.

3. **Insights and Recommendations:**
   - Identify significant happiness factors.
   - Provide actionable policy recommendations.

## Key Steps
### 1. Data Preprocessing
- **Missing Values:** Addressed missing data based on the context of each feature.
- **Feature Selection:** Retained highly correlated features with "Ladder Score" based on a correlation threshold.

### 2. Exploratory Data Analysis (EDA)
- Visualizations include:
  - Top 5 and Bottom 5 countries by Ladder Score.
  - Distributions of features like GDP, Social Support, and Life Expectancy.
  - Boxplots highlighting regional differences.
  - A heatmap for variable correlations.

### 3. Machine Learning
- **Models Used:**
  - **Linear Regression**
  - **Random Forest Regressor**
- **Performance Metrics:**
  - Mean Squared Error (MSE)
  - R-squared (R²)

### 4. Model Performance
- **Linear Regression:**
  - MSE: 0.41
  - R²: 0.60
- **Random Forest Regressor:**
  - MSE: 0.37
  - R²: 0.64

### 5. Insights
- **Significant Features Impacting Happiness:**
  - GDP per Capita
  - Social Support
  - Healthy Life Expectancy
  - Freedom to Make Life Choices
- **Model Comparison:** Random Forest Regressor showed better performance compared to Linear Regression.

### 6. Recommendations
- **Policy Suggestions:**
  - Strengthen social support systems.
  - Focus on economic development and healthcare improvements.
  - Promote transparency and reduce corruption perceptions.
- **Future Directions:**
  - Incorporate datasets on mental health and crime rates.
  - Conduct multi-year time-series analysis for trends in happiness.


```

## How to Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/world-happiness-analysis.git
   cd world-happiness-analysis
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Notebooks:**
   - Navigate to the `notebooks` folder and run `eda.ipynb` for EDA or `ml_modeling.ipynb` for machine learning.
4. **View Outputs:**
   - Visualizations and predictions are saved in the `outputs` folder.

## Tools and Libraries
- **Programming Language:** Python
- **Libraries:**
  - Pandas, NumPy: Data manipulation and analysis
  - Matplotlib, Seaborn: Visualization
  - Scikit-learn: Machine learning

