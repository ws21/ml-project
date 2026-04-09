Task 1: 

The column `repeat_purchase_flag` is the label because it indicates whether the customer made a repeat purchase within 30 days, which is the outcome we want to predict. The column `discount_used_on_repeat_order` would introduce data leakage if used as a feature, because it contains information about the repeat purchase itself. This information would not be available at the time of prediction, making the model unrealistically accurate.


Task 2: 

Before training any model, it is important to explore the data. EDA helps in understanding the distribution of variables, identifying missing values, detecting outliers, and finding relationships between features. This step ensures the data is clean and ready for modeling. It includes handling missing values, scaling numerical features, and creating useful new features if needed. Proper preprocessing improves model performance and reliability.