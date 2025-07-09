
# 📊 Flipkart Reviews Sentiment Analysis

This project performs exploratory data analysis (EDA), sentiment analysis, and classification on a dataset containing Flipkart customer support and delivery feedback data. It aims to understand customer behavior, satisfaction, and performance of support operations.

## 📁 Dataset

The dataset includes various features related to customer interactions with Flipkart, such as:

- **Customer Remarks** – Text feedback from customers
- **Customer City** – Location of the customer
- **Enquiry Category** – Type of customer query (e.g., return, delivery)
- **Sentiment Score** – Generated sentiment score from textual feedback
- **CSAT Score** – Customer Satisfaction score (usually between 1–5)
- **Delivery Slot** – Time of delivery (e.g., Morning, Evening)
- **Response Time** – Time taken to respond to the query
- And other relevant support-related columns.

## 🧪 Hypothesis Testing

Several hypotheses were tested, including:

1. Whether sentiment correlates with CSAT scores.
2. If response time significantly affects sentiment.
3. Whether delivery slot impacts CSAT scores.

Techniques like ANOVA and correlation analysis were used to validate these.

## 🔍 Key Findings

- **Customer-Initiated Interaction**: Most tickets were initiated by customers rather than Flipkart.
- **Top Enquiry Type**: Returns form the highest number of customer queries.
- **Sentiment Distribution**: Majority of the sentiment was neutral.
- **Sentiment vs. Response Time**: Negative correlation found – longer response time leads to lower sentiment.
- **Delivery Slot Analysis**: Morning deliveries resulted in higher positive feedback.

## 🤖 Machine Learning

A classification model was built to predict **CSAT scores** based on:

- Sentiment scores  
- Delivery slot  
- Enquiry category  
- Response time  

**Random Forest** and other models were tested. Evaluation was done using:
- Accuracy
- Confusion Matrix
- Feature Importance Charts

## 📈 Visualizations

Multiple plots were created:
- Distribution of CSAT scores
- Sentiment vs. Response Time
- Customer city-wise satisfaction levels
- Feature importance from ML models

## 🧰 Tools & Libraries

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn`, `plotly` – Visualization
- `scikit-learn` – Machine learning and model evaluation
- `nltk` / `TextBlob` – Sentiment analysis

## 📝 How to Run

1. Install the dependencies listed in `requirements.txt`.
2. Open the Jupyter notebook:  
   `Flipkart_Reviews_Sentiment_Analysis.ipynb`
3. Run all cells to reproduce the analysis, visualizations, and ML results.

## 📬 Contact

For questions or collaborations, reach out to:  
**Your Name** – [shirishsriv@gmail.com]
