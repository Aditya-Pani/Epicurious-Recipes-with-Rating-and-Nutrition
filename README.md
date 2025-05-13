# 🍽️ Epicurious Recipes – Rating, Nutrition, and Category Analysis
## 📊 Project Overview
This project analyzes a dataset of over 20,000 recipes from Epicurious, exploring how nutritional content, categories, and other features relate to recipe ratings. The goal is to identify what influences people's preferences for recipes and understand culinary patterns from a data-driven perspective.

## 📁 Dataset Information
### Source: 
- Epicurious.com

### Files used:

- full_format_recipes.json – Complete dataset with ingredients and directions

- epi_r.csv – Pre-processed version (used in this notebook) containing:


## 🔍 Objectives
- Understand how different nutritional components affect recipe ratings

- Analyze trends across food categories (e.g., desserts, main courses, vegetarian dishes)

- Visualize patterns in recipe popularity

- Generate insights for healthy and popular food choices

## 🛠️ Tools & Libraries Used
- Python

- pandas

- numpy

- matplotlib

- seaborn

- plotly

- scikit-learn (if modeling included)

## 🔬 Notebook Highlights
### Data Cleaning:

- Handled missing and duplicate entries

- Converted categories into dummy variables (one-hot encoding)

### Exploratory Data Analysis (EDA):

- Rating distributions

- Correlation between nutrition metrics and ratings

- Category-based recipe trends

### Visualizations:

- Heatmaps

- Histograms and boxplots

- Category comparisons


## 🧠 Insights & Takeaways
- Recipes with balanced fat and protein tend to receive higher ratings

- Certain categories like dessert or weeknight are consistently rated higher

- Recipes low in calories or low fat do not necessarily get lower ratings, but extremes may affect preferences

## 🚀 Future Improvements
- Include ingredient-level analysis

- Add recipe creation dates to explore temporal food trends

- Build a recommendation system based on nutrition and ratings

- Most of the recipe are considerd healthy, which is good for anyone considering following this data.

🙏 Acknowledgments
- Data Downloaded from: Kaggle

- Dataset creator: HugoDarwood

