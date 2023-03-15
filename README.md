# Reducing-Cancellation-Rates-in-Hotel-Bookings-through-Predictive-Modeling

Table of Contents:

1. Introduction
2. Data
3. Analytics
4. Data Exploration
5. Modeling
6. Results
7. Conclusion

### Introduction:

Reducing cancellation rates in hotel bookings is essential for better revenue management and customer satisfaction. This project aims to develop a predictive model to help hotel managers in predicting the probability of booking cancellations.

### Data:

The dataset used in this project is obtained from Kaggle and contains information on hotel bookings from two hotels in Portugal, covering a period of about two years. The dataset includes a total of 32 variables, consisting of categorical, numerical, and date-time features. The dataset is preprocessed and cleaned for missing values and outliers.

### Analytics:

The Analytics folder contains the Jupyter notebook file, where exploratory data analysis (EDA) is performed to understand the characteristics of the data. The notebook also includes visualization of different features, correlation analysis, and feature engineering. This step is important to select the most important features and remove any irrelevant features.

### Data Exploration:
We started by exploring the dataset to get a better understanding of the variables and their relationships. We found that:

- The majority of bookings (about 63%) were for city hotels, while the rest were for resort hotels.
- About 37% of bookings were canceled, indicating a significant challenge for the hotel industry.
- Bookings made through travel agencies had a higher cancellation rate (about 45%) compared to those made directly with the hotel (about 28%). 
- A higher percentage of bookings were made for the months of May, June, July, August, and September, while the lowest percentage was for November, December, January, and February.
- Most bookings were for one or two nights, with a smaller percentage of bookings for longer stays.
- The cancellation rate was higher for bookings with special requests, such as a specific room type or bed type.
- The cancellation rate was also higher for bookings made by customers who had previously canceled a reservation.
- The distribution of cancellation rates varied by country of origin, with some countries having much higher rates than others.
- Customers who booked a non-refundable rate had a much lower cancellation rate compared to those who booked a flexible rate.
- The cancellation rate for group bookings was much higher compared to individual bookings.

### Modeling:

The Modeling folder contains the Jupyter notebook file, where predictive modeling is performed using different machine learning algorithms such as logistic regression, decision tree, and random forest. The performance of each model is evaluated using different metrics such as accuracy, precision, recall, and F1-score. The model with the best performance is selected and used for predictions.

### Results:
Hotel Cancellation Prediction Project Results:

- Logistic Regression: Achieved an accuracy score of 0.80, precision score of 0.68, and recall score of 0.49.

- Decision Tree: Achieved an accuracy score of 0.81, precision score of 0.64, and recall score of 0.65.

- Random Forests: Achieved an accuracy score of 0.84, precision score of 0.76, and recall score of 0.58.

These results suggest that Random Forests outperformed the other two models in terms of accuracy and precision, while Decision Tree had the highest recall score.

### Conclusion:

The final model developed through this project can help hotel managers to identify the probability of a booking cancellation in advance. By predicting which bookings are more likely to be canceled, managers can take appropriate measures such as adjusting their booking policies or offering incentives to prevent cancellations. This project demonstrates the importance of predictive modeling in improving revenue management and customer satisfaction in the hotel industry.
