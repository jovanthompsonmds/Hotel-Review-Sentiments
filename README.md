# Hotel Review Sentiments

## Overview
This project analyzes sentiments in hotel reviews using natural language processing (NLP) techniques. By processing text data from multiple datasets, the project aims to uncover customer opinions, trends, and key drivers behind positive and negative reviews. It includes data cleaning, sentiment analysis, and visualization of the results.

## Features
- **Data Preprocessing**: Cleaning and formatting text data from multiple CSV files.
- **Sentiment Analysis**: Applying NLP methods to classify reviews as positive, negative, or neutral.
- **Visualization**: Generating charts and graphs to understand sentiment distribution and trends across datasets.
- **Key Insights**: Identifying major factors contributing to customer satisfaction or dissatisfaction.

## Files
### 1. `Hotel Review Sentiments.ipynb`
- A Jupyter Notebook that:
  - Loads and preprocesses the datasets.
  - Implements sentiment analysis using Python libraries.
  - Visualizes results with meaningful plots.

### 2. `DSC-570-R-hotel1.csv`, `DSC-570-R-hotel2.csv`, `DSC-570-R-hotel3.csv`
- CSV files containing hotel reviews.
- Each file includes columns for review text, ratings, and other metadata.

## Requirements
- Python 3.8 or higher
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `nltk` (for text processing)
  - `scikit-learn` (for sentiment classification)

Install the dependencies using:
pip install pandas numpy matplotlib seaborn nltk scikit-learn

Usage
1. Clone the repository and navigate to the project directory:
git clone https://github.com/yourusername/hotel-review-sentiments.git
cd hotel-review-sentiments

2. Open the Jupyter Notebook:
jupyter notebook "Hotel Review Sentiments.ipynb"

3.Run the notebook cells to:
Load and preprocess the data from the provided CSV files.
Perform sentiment analysis.
Generate visualizations and key insights.

Insights
This project provides valuable insights into:
Customer sentiment distribution across hotel reviews.
Common themes in positive and negative feedback.
Actionable recommendations for improving customer satisfaction.

Contributing
Contributions are welcome! If you'd like to improve the project or add new features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Developed by Jovan Thompson as part of a data science portfolio project.
