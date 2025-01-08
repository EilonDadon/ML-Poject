# ML Project: Donations To Israeli Associations From Foreign Entities

This project analyzes donation trends to Israel and predicts donation purposes using machine learning techniques. It also performs clustering to identify patterns with similar donation characteristics.

## Objectives

1. **Analyze donation trends** by years
2. **Predict donation purposes** based on donation details using supervised learning models.
3. **Identify clusters** with similar donation characteristics through unsupervised learning.

## Features

- **Data Preprocessing:** Handling missing values, encoding categorical variables, and cleaning data.
- **Feature Engineering:** Creating relevant features for analysis and prediction.
- **Supervised Learning Models:** Linear Regression, Random Forest, XGBoost, SVM, and KNN.
- **Unsupervised Learning:** K-means and DBSCAN clustering for grouping.
- **Visualization:** Donation trends, feature importance, and clustering results.

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    
3. Ensure you have the necessary API keys from the gov site. link : "https://data.gov.il/dataset/moj-amutot/resource/35cb40b5-3f13-4bca-9ce2-488085913107"

## Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook ML_Project.ipynb

2. Run the notebook cells step-by-step to:
- **Load and preprocess data.**
- **Train and evaluate models.**
- **Perform clustering and visualize results.**

## Project Structure
- **data:** 2 csv files: raw_data and processed_data
- **notebook/ML_Project.ipynb:** Main notebook containing the project code.
- **requirements.txt:** Python dependencies.
- **README.md:** Project documentation.
- **reports** : all the reports saved as images

## Dependencies
See requirements.txt for all dependencies.

## Results
1. **Trend Analysis:** Visualized trends in donation amounts over time.
2. **Prediction Performance:** Evaluated models using metrics like accuracy, precision, recall, F1-Score, and 5-Fold Cross Validation.
3. **Clustering:** Identified meaningful clusters based on donation characteristics.







