# Hotel Review Sentiments

## Overview
This project analyzes sentiments in hotel reviews using natural language processing (NLP) techniques in R. By processing text data from multiple datasets, the project aims to uncover customer opinions, trends, and key drivers behind positive and negative reviews. It includes data cleaning, sentiment analysis, and visualization of the results.

## Features
- **Data Preprocessing**: Cleaning and formatting text data from multiple CSV files.
- **Sentiment Analysis**: Applying NLP methods with the `syuzhet` package to classify reviews as positive, negative, or neutral.
- **Visualization**: Generating charts and graphs using `ggplot2` to understand sentiment distribution and trends across datasets.
- **Key Insights**: Identifying major factors contributing to customer satisfaction or dissatisfaction.

## Files
### 1. `Hotel Review Sentiments.ipynb`
- A notebook file that:
  - Loads and preprocesses the datasets using R.
  - Implements sentiment analysis with R packages like `syuzhet` and `dplyr`.
  - Visualizes results with `ggplot2`.

### 2. `R-hotel1.csv`, `R-hotel2.csv`, `R-hotel3.csv`
- CSV files containing hotel reviews.
- Each file includes columns for review text, ratings, and other metadata.

## Requirements
- R version 4.0 or higher
- Required R libraries:
  - `syuzhet`
  - `ggplot2`
  - `dplyr`
  - `zoo`
  - `lsa`
  - `text`

Install the libraries using:
install.packages(c("syuzhet", "ggplot2", "dplyr", "zoo", "lsa", "text"))

## Usage
1. Clone the repository and navigate to the project directory:
git clone https://github.com/yourusername/hotel-review-sentiments.git
cd hotel-review-sentiments

2. Open the R script in your preferred IDE (e.g., Jupyter Notebook, RStudio) and run the code to:
Run the notebook cells to:
Load and preprocess the data from the provided CSV files.
Perform sentiment analysis.
Generate visualizations and key insights.

## Insights
This project provides valuable insights into:
Customer sentiment distribution across hotel reviews.
Common themes in positive and negative feedback.
Actionable recommendations for improving customer satisfaction.

## Contributing
Contributions are welcome! If you'd like to improve the project or add new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
