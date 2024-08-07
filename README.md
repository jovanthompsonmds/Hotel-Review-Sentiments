# Natural Language Processing (NLP) To Assess Hotel Review Sentiments

## Overview
This project analyzes sentiments in hotel reviews using natural language processing (NLP) techniques in R. By processing text data from multiple datasets, the project aims to uncover customer opinions, trends, and key drivers behind positive and negative reviews. It includes data cleaning, sentiment analysis, and visualization of the results.

## Features
- **Data Preprocessing**: Cleaning and formatting text data from multiple CSV files.
- **Sentiment Analysis**: Applying NLP methods with the `syuzhet` package to classify reviews as positive, negative, or neutral.
- **Visualization**: Generating charts and graphs using `ggplot2` to understand sentiment distribution and trends across datasets.
- **Key Insights**: Identifying major factors contributing to customer satisfaction or dissatisfaction.

## Files
### 1. `Natural Language Processing (NLP) To Assess Hotel Review Sentiments.ipynb`
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
- git clone https://github.com/jovanthompsonmds/Natural-Language-Processing-NLP-To-Assess-Hotel-Review-Sentiments.git

2. Open the R script in your preferred IDE (e.g., Jupyter Notebook, RStudio) and run the code to:
Run the notebook cells to:
- Load and preprocess the data from the provided CSV files.
- Perform sentiment analysis.
- Generate visualizations and key insights.

## Insights & Conclusions

This project provides valuable insights into:
- Customer sentiment distribution across hotel reviews.
- Common themes in positive and negative feedback.
- Actionable recommendations for improving customer satisfaction.

### **1. Sentiment Analysis of Hotel Reviews**
- The sentiment analysis of customer reviews across three hotels (**40 Berkeley Hostel, A Bed & Breakfast In Cambridge, and Ambassadors Inn and Suites**) provides key insights into guest satisfaction.
- **Hotel 1 (40 Berkeley Hostel)** showed the **widest range** of sentiment values (-4.00 to 4.15), indicating **strongly mixed reviews**, with an overall **slightly positive** mean sentiment (0.4689).
- **Hotel 2 (A Bed & Breakfast In Cambridge)** exhibited **the highest overall positivity** (mean: 0.6461), suggesting a generally **better guest experience**.
- **Hotel 3 (Ambassadors Inn and Suites)** had the **lowest mean sentiment (0.2888)**, indicating **lower customer satisfaction** compared to the other two hotels.

### **2. Visualization & Sentiment Trends**
- The **trend analysis** shows fluctuations in sentiment over time, with **Hotel 1 and Hotel 3 experiencing significant dips**, suggesting inconsistencies in service quality.
- **Hotel 2 had more stable sentiment trends**, reinforcing its **higher guest satisfaction**.
- **DCT Smoothing & Normalized Sentiment Curves** revealed that while all hotels have variations, **Hotel 2 consistently outperforms in sentiment trends**.

### **3. Cosine Similarity & Correlation Analysis**
- **Hotel 1 & Hotel 2**: Strong **negative** correlation (-0.719 cosine similarity, -0.696 correlation), indicating **opposing guest experiences**.
- **Hotel 1 & Hotel 3**: Even **stronger negative relationship** (-0.868 cosine similarity, -0.876 correlation), suggesting **significant differences in customer sentiment**.
- **Hotel 2 & Hotel 3**: Moderate **positive** correlation (0.451 cosine similarity, 0.453 correlation), implying **similar service strengths and weaknesses**.

### **4. Managerial Implications**
- **Hotel 1**: Needs to **investigate the causes of negative sentiment spikes** and **improve service consistency**.
- **Hotel 2**: Should leverage **positive reviews for marketing strategies** and **continue high service standards**.
- **Hotel 3**: Should focus on **addressing negative feedback**, as lower sentiment scores indicate **guest dissatisfaction**.

### **5. Ethical Considerations**
- **Algorithmic Bias**: The sentiment model may **misinterpret informal language** or **cultural expressions**, leading to inaccurate results.
- **Marketing Risks**: Hotels must be cautious when using sentiment results for advertising, ensuring **expectations match reality**.
- **Data Privacy**: Proper anonymization of review data is crucial to avoid **violating customer trust**.

### **6. Future Enhancements**
✔ Improve sentiment classification to **differentiate between strong/weak positivity and negativity**.  
✔ Implement a **more advanced sentiment model** (e.g., LSTM-based NLP) for **greater accuracy**.  
✔ Expand analysis to include **additional hotel features like amenities, pricing, and customer demographics**.  
✔ Deploy an **interactive dashboard** to visualize trends in real-time.  

## Contributing

Contributions are welcome! If you'd like to improve the project or add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

Developed by Jovan Thompson as part of a data science portfolio project.
