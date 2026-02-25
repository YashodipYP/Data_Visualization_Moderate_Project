# Data_Visualization_Moderate_Project
Exploratory Data Analysis (EDA) of Bangalore's Zomato restaurants, uncovering pricing trends, market leaders, and customer engagement using Python.Analyzing 40,000+ restaurant records to discover business insights and pricing sweet spots in the Bangalore food industry.

# 🍽️ Bangalore Zomato Data Analysis

## 📌 Project Overview
This project is a comprehensive Exploratory Data Analysis (EDA) of the Bangalore Zomato restaurant dataset. The goal of this analysis is to uncover business intelligence, customer preferences, and pricing strategies in one of India's most competitive food markets.

The raw dataset containing over 50,000+ records was rigorously cleaned (handling missing values, data type conversions, and text parsing) before generating statistical visualizations to answer key business hypotheses.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Key Business Insights Discovered
Through univariate and bivariate analysis, several key trends were identified:
1. **The "Social Hub" Effect:** Microbreweries and Pubs generate significantly more customer engagement (votes) than standard dining options, proving that customers vote heavily for *experiences*.
2. **The Pricing "Sweet Spot":** The optimal price-to-rating ratio exists between ₹1500–₹2000 (for two people). Prices beyond this point see diminishing returns in customer satisfaction.
3. **Table Booking vs. Quality:** Restaurants that offer table booking have a notably higher median rating (approx. 4.1) compared to those that do not, indicating a correlation between premium service and customer perception.
4. **Cost vs. Rating:** A moderate positive correlation (~0.38) exists between cost and rating, meaning "expensive food is generally better," but popularity (votes) is an even stronger predictor of quality.

## 🧹 Data Cleaning & Feature Engineering
* Handled missing values (NaN) across critical columns (`rate`, `cost`, `cuisines`).
* Cleaned and converted string representations of currency (e.g., "1,200") into numeric floats.
* Parsed complex rating strings (e.g., "4.1/5" and "NEW") into clean numeric formats for statistical analysis.
* Segmented and binned pricing into categorical ranges for deeper market analysis.

## 🚀 How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed: `pip install -r requirements.txt`
3. Download the `zomato.csv` dataset from Kaggle and place it in the same directory.
4. Run the `zomato_eda.ipynb` notebook to view the analysis and graphs.
