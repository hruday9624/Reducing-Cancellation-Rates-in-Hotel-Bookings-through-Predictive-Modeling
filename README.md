# Reducing-Cancellation-Rates-in-Hotel-Bookings-through-Predictive-Modeling

Table of Contents:

1. Introduction
2. Data
3. Analytics
4. Data Exploration & Key Insights
6. Modeling
7. Results
8. Hyperparameter Tuning
8. Conclusion

### Introduction:

Reducing cancellation rates in hotel bookings is essential for better revenue management and customer satisfaction. This project aims to develop a predictive model to help hotel managers in predicting the probability of booking cancellations.

### Data:

The dataset used in this project is obtained from Kaggle and contains information on hotel bookings from two hotels in Portugal, covering a period of about two years. The dataset includes a total of 32 variables, consisting of categorical, numerical, and date-time features. The dataset is preprocessed and cleaned for missing values and outliers.

### Analytics:

The Analytics folder contains the Jupyter notebook file, where exploratory data analysis (EDA) is performed to understand the characteristics of the data. The notebook also includes visualization of different features, correlation analysis, and feature engineering. This step is important to select the most important features and remove any irrelevant features.

### Data Exploration & & Key Insights: 
We started by exploring the dataset to get a better understanding of the variables and their relationships. We found that:

- Most bookings are made relatively close to the check-in date, and the distribution is positively skewed, indicating that the hotel should consider offering incentives or discounts to customers who book further in advance, to encourage more of them to do so.
- The hotel should implement policies that allow customers to cancel or change their reservations more easily, as this could improve customer satisfaction and loyalty, given the high cancellation rates.
- Revenue management strategies that take into account the lead time of bookings should be implemented to optimize pricing and maximize revenue.
- Since most bookings are made close to the check-in date, the hotel should consider implementing policies that allow customers to cancel or change their reservations more easily, as this could improve customer satisfaction and loyalty.
- The hotel should take into account the seasonal variation in bookings and cancellation rates and adjust their strategies accordingly. April to August have more cancellation rates compared to other months, and July and August have the highest number of bookings.
- The hotel should focus their marketing efforts towards customers who book far in advance, as they are likely to be a smaller but more committed group of customers.
- The hotel should also consider diversifying their customer base and not solely rely on customers from Portugal, which accounts for 40% of the bookings.
- The hotel should consider partnering with offline TA/TO to tap into their 20% market share, as they are the second-largest market segment.
- Since more than 75% of the customers are transient type, the hotel should focus on offering personalized experiences to retain these customers.
- The hotel should pay close attention to the meal preferences of their customers, as 77.31% of them preferred Bread & Breakfast, and only 0.66% preferred FB.
- The hotel should encourage customers to make special requests and personalize their experiences, given that more than 58% of customers have not made any special requests to the hotels.
- The hotel should closely monitor and manage the high cancellation rates, especially for Resort Hotel, which had a cancellation rate of 23%. This could be done by offering flexible cancellation policies or incentivizing customers to not cancel their bookings.
- The hotel should also consider offering promotions or discounts during the off-peak season to increase bookings and revenue.
- The data shows that corporate customers hold only 4% of the market share, indicating that the hotel should focus on improving their corporate sales strategies to attract more corporate customers.
- The hotel should also consider expanding their market segment to include the Aviation market, which only accounts for 0.19% of the bookings.
- Since customers with NO Deposite are less likely to cancel their bookings, the hotel should consider offering this option to incentivize more customers to book.
- The hotel should consider using data analytics to identify trends and patterns in customer behavior, such as booking patterns, preferred room types, or meal preferences, to personalize the customer experience and improve customer satisfaction.
- The hotel should also consider investing in technology solutions such as a customer relationship management (CRM) system or a mobile app to improve the customer experience and increase customer loyalty.
- Finally, the hotel should pay close attention to customer feedback and use it to improve their services and offerings. This can be done by conducting regular surveys or implementing a feedback system to capture customer feedback in real-time.

### Modeling:

The Modeling folder contains the Jupyter notebook file, where predictive modeling is performed using different machine learning algorithms such as logistic regression, decision tree, and random forest. The performance of each model is evaluated using different metrics such as accuracy, precision, recall, and F1-score. The model with the best performance is selected and used for predictions.

### Results:

In this project, four different machine learning models were evaluated based on their accuracy, precision, and recall scores:

- Logistic Regression: Achieved an accuracy score of 0.79, precision score of 0.83, and recall score of 0.91.

- Decision Tree: Achieved an accuracy score of 0.80, precision score of 0.87, and recall score of 0.86.

- Random Forests: Achieved an accuracy score of 0.83, precision score of 0.86, and recall score of 0.93.

- Support Vector Machine: Achieved an accuracy score of 0.80, precision score of 0.82 and high recall score of 0.92. 

Based on these scores, it can be concluded that all four models performed well in identifying the target variable. Random Forests achieved the highest accuracy score, with a particularly high recall score, indicating that it is a good choice for this specific use case. However, the other models also performed well, with high precision and recall scores, indicating that they can also be good choices depending on the specific needs of the project.

Therefore, it's important to consider the specific needs of the project and the characteristics of the data when selecting a machine learning model. Additionally, further evaluation and tuning of the models may be necessary to improve their performance and achieve better accuracy, precision, and recall scores.

### Hyperparameter Tuning: 

Based on the initial results and the scores, I have chosen the Random Forest model for further analysis as it performed well compared to other models.

Comparing the original and hyperparameter tuned random forest models, we see that the hyperparameter tuned model has a slightly higher accuracy score (0.851 vs 0.83), but a lower precision score (0.783 vs 0.86) and a much lower recall score (0.626 vs 0.93). This suggests that while the hyperparameter tuned model may have a higher overall accuracy, it is not as effective at correctly identifying true positives as the original model. Therefore, depending on the specific needs of the task, it may be more beneficial to use the original model with a higher precision and recall score, or the hyperparameter tuned model with a higher accuracy score but lower precision and recall scores.

### Conclusion:

The final model developed through this project can help hotel managers to identify the probability of a booking cancellation in advance. By predicting which bookings are more likely to be canceled, managers can take appropriate measures such as adjusting their booking policies or offering incentives to prevent cancellations. This project demonstrates the importance of predictive modeling in improving revenue management and customer satisfaction in the hotel industry.
