# Credit Risk - Logistic-Regression-Model

**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** The logistic regression model performs very well in predicting both the "0" (healthy loan) and "1" (high-risk loan) labels. Here are the key points:

For Label 0 (Healthy Loan):

-Precision: The model has a precision of 1.00, which means that when it predicts a loan as healthy, it is almost always correct.

-Recall: The model has a recall of 0.99, indicating that it correctly identifies 99% of the actual healthy loans.

-F1-Score: The F1-score is 1.00, which is the harmonic mean of precision and recall. It indicates excellent performance for Label 0.


For Label 1 (High-Risk Loan):

-Precision: The model has a precision of 0.85, which means that when it predicts a loan as high-risk, it is correct about 85% of the time.

-Recall: The model has a recall of 0.91, indicating that it correctly identifies 91% of the actual high-risk loans.

-F1-Score: The F1-score is 0.88, indicating good performance for Label 1.


Overall, the model is performing exceptionally well. It has a high accuracy (0.99), and it is particularly effective at identifying healthy loans. It also shows strong performance in identifying high-risk loans, though there is a slightly higher chance of false positives in this category compared to the false negatives in the healthy loan category. This suggests that the model might be a bit more conservative when predicting high-risk loans.
