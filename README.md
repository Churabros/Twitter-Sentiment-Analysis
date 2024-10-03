# Moringa phase 4 project

## Business Understanding
In todays digital landscape,understanding customer feedback is a crucial step in maintaining brand reputation and enhancing customers reputation social media platforms like twitter provide an abundance of feedback where user express their opinions

## EDA

![image](https://github.com/user-attachments/assets/ec0ab063-c39a-49c8-bbce-6d94338011c2)
Neutral sentiments are the highest indicating that a large portion of the tweets are mostly informational about the products being reviewed. Positive sentiments outweighs negative sentiment by a significant difference which would indicate good performance and the clients are happy about the products that they own.

![image](https://github.com/user-attachments/assets/65a9fd7a-c9af-4ed4-a626-0e676e5b2d06)
This visualization offers the following several insights:

This visualization offers the following several insights:
1. Apple products (iPad, iPhone, Apple in general) consistently show high levels of positive sentiment, suggesting strong user satisfaction and excitement about these products.
2. The iPad stands out with the highest count of positive sentiment, which could indicate it was a major topic of interest, possibly due to a recent or anticipated release.
3. While Google also receives more positive than negative sentiment, the ratio isn't as favorable as Apple's. This could suggest a stronger brand affinity or product satisfaction among Apple users in this dataset.
4. Android has a relatively low count of mentions compared to iOS devices, but still maintains a positive skew. This might indicate less buzz around Android at this particular scenario, but still a generally positive perception.
5. Both "iPhone App" and "iPad or iPhone App" categories show strong positive sentiment, highlighting the importance of the app ecosystem in user satisfaction for these platforms.

![image](https://github.com/user-attachments/assets/5a629484-78a8-4ddc-9f37-ad626fd7b5e7)
The above box plot indicates that the average length of tweets is relatively similar across sentiments, with negative tweets being slightly longer on average which could indicate that users tend to provide more explanation or context when expressing criticism or dissatisfaction.

![image](https://github.com/user-attachments/assets/8598c1f9-cba1-478c-8f54-00356ea37a83)
The above bar graph shows the top 10 most commonly used words, with link appearing the most than others. This suggests that sharing links was a common practice during the discussions on rating Google and Apple products. The high frequency of rt which is presumably short for retweet indicates that content was shared and amplified widely. iPad and iPhone were the Apple products that were discudssed the most.

![image](https://github.com/user-attachments/assets/b6155770-1bff-4c0a-9fcd-cf6d3ab1125c)
While the bar graph gave us the top 10 common words, the word cloud shows us more words that were common during the opinion review of the products.
Upon further research The prominence of `Austin` and `SXSW` suggests that much of the opinions were centered around the South by Southwest (SXSW) conference, an annual event held in Austin, Texas that focuses on technology, film, and music. The large presence of terms like `app`, `Google`, `iPad`, `iPhone`, `launch`, `new` and `party`indicates that the technology aspect of the SXSW conference was the major focus with the discussion being around cutting-edge innovations on Google and Apple products.


## Best Logestic regression
# Model Evaluation Summary

**Tuned Logistic Regression Model Accuracy:** 68.23%

The model achieved an accuracy of 68.23%, meaning it correctly predicted the outcome for 68.23% of the test cases.

## Best Hyperparameters:

- **Solver:** lbfgs
- **Class Weight:** None
- **C:** 1

## Classification Report:

### False Class (Negative):

- **Precision:** 58% – The model correctly identified 58% of negative instances.
- **Recall:** 6% – It detected only 6% of actual negative cases.
- **F1-Score:** 10% – Indicates poor performance in predicting negative customers.

### True Class (Neutral):

- **Precision:** 70% – The model correctly identified 70% of neutral instances.
- **Recall:** 87% – It detected 87% of actual neutral cases.
- **F1-Score:** 78% – Shows good performance in predicting neutral customers.

### True Class (Positive):

- **Precision:** 62% – The model correctly identified 62% of positive instances.
- **Recall:** 45% – It detected 45% of actual positive cases.
- **F1-Score:** 52% – Indicates moderate performance in predicting positive customers.

## Best Random forest

# Model Evaluation Summary

**Best Random Forest Model Accuracy:** 64.32%

The model achieved an accuracy of 64.32%, meaning it correctly predicted the outcome for 64.32% of the test cases.

## Classification Report:

### False Class (Negative):

- **Precision:** 34% – The model correctly identified 34% of negative instances.
- **Recall:** 30% – It detected 30% of actual negative cases.
- **F1-Score:** 32% – Indicates poor performance in predicting negative customers.

### True Class (Neutral):

- **Precision:** 74% – The model correctly identified 74% of neutral instances.
- **Recall:** 72% – It detected 72% of actual neutral cases.
- **F1-Score:** 73% – Shows good performance in predicting neutral customers.

### True Class (Positive):

- **Precision:** 53% – The model correctly identified 53% of positive instances.
- **Recall:** 57% – It detected 57% of actual positive cases.
- **F1-Score:** 55% – Indicates moderate performance in predicting positive customers.



