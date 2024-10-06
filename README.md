# Twitter Sentiment Analysis

## Overview
- **Project Goal:**  
  The primary goal of this project is to analyze customer sentiment towards various products based on tweets sourced from social media platforms. This analysis aims to build a sentiment classifier to better understand public opinion and provide actionable insights for businesses.

- **Focus:**  
  The project focuses on utilizing machine learning techniques to classify tweet sentiments into positive, negative, and neutral categories, helping stakeholders gauge customer satisfaction and identify potential areas for improvement.

## Business Understanding
### Stakeholders
- Product Managers
- Marketing Teams
- Brand Analysts
- Customer Support Teams

### Key Business Questions
1. What themes or issues are associated with negative sentiment?
2. Which products or brands receive the most positive or negative feedback?

## Data Understanding
### Source of Data
- The dataset is sourced from [CrowdFlower](https://data.world/crowdflower/brands-and-product-emotions), which contains tweets about various products along with their labeled sentiments.

### Description of Data
- The dataset includes columns such as:
  - `tweet_text`: The raw text of the tweet.
  - `motion_in_tweet_is_directed_at`: Specifies the product or brand the tweet refers to.
  - `emotion_in_tweet_is_directed_at`: Labels the sentiment associated with the tweet (positive, neutral, negative).
  
## Exploratory Data Analysis
Visualizations Conducted:
1. Count of Sentiments: Distribution of sentiment types in the dataset to gauge overall public opinion.
2. Sentiment Distribution by Product: Insights into how sentiments differ across products, revealing brand-specific perceptions.
3. Average Tweet Length by Sentiment: Analyzed tweet lengths to identify potential patterns in sentiment expression.
4. Most Common Tokens: Identified frequently used words to uncover prevalent themes in customer feedback.
5. Word Cloud: Visual representation of common terms, emphasizing significant keywords in tweets.


## Modelling
- Multiple machine learning models are implemented, including Logistic Regression, Random Forest, and Neural Networks, to evaluate their performance in predicting tweet sentiment. Hyperparameter tuning and model optimization techniques are also applied.

## Evaluation
- Model Performance - Achieved an F1-score of approximately 0.6602, indicating solid predictive capability.

- Validation Approach - Utilized stratified train-test splits to maintain class distributions and ensure robust evaluation.

- Conclusion - The Logistic Regression model, after tuning, is superior in terms of compared to all other models explored. It offers a more reliable approach for accurately  classifying the tweets.


## How to Use the Project
1. Clone the repository to your local machine:  
   ```bash
   git clone <repo_url>
   ```
2. Install dependencies by running:  
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the project directory.
4. Launch Jupyter Notebook by running:  
   ```bash
   jupyter notebook
   ```
5. Open the `website_phishing.ipynb` notebook.
6. Follow the instructions and execute the cells in the notebook to replicate the analysis steps.

---

## Requirements

To run this project, the following Python packages are required:

```plaintext
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
tensorflow
jupyter
```

Ensure you have Python (preferably 3.6 or higher) installed on your machine before proceeding with the installation of the above dependencies.

---
