# Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach

![image](https://github.com/AkshayRamakrishnann/Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach/assets/111365771/8cf8df1b-e58d-47e7-99c3-30399d7b97e1)


## Introduction

This machine learning project focuses on predicting hotel booking cancellations. We use a dataset from '/content/Hotel Reservations.csv' to explore, preprocess, and build predictive models. The primary objectives of this project are to analyze booking trends, develop accurate cancellation prediction models, and compare the performance of different classifiers.

## Preprocessing

We began by importing necessary libraries for data manipulation and visualization, loading the dataset, and performing initial data exploration:

- Imported libraries like Pandas, NumPy, Matplotlib, and Seaborn.
- Loaded the dataset and displayed its initial information.
- Checked for missing values and removed rows with missing data.
- Visualized the distribution of booking statuses using a count plot.
- Created a correlation heatmap to visualize relationships between numerical variables.
- Compared room types based on the average price per room using a box plot.
- Mapped string values to numerical representations for specific columns to prepare the data for modeling.

## Models Used

We implemented three different machine learning models to predict booking cancellations:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

For handling class imbalance, we performed oversampling on the minority class in the training dataset.

## Results

We evaluated the models' performance using accuracy scores and classification reports. Here are the actual results:

**Logistic Regression:**

- Accuracy: 0.7921433494141971

**Decision Tree:**

- Accuracy: 0.8690558235699517


**Random Forest:**

- Accuracy: 0.9032391454169538



We also created a bar chart to compare the accuracy of these models visually.

![1](https://github.com/AkshayRamakrishnann/Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach/assets/111365771/316a5670-8602-45a8-ab22-bf8a44025464)

## Conclusion

In conclusion, this machine learning project explored hotel booking data, preprocessed it, and built predictive models to predict booking cancellations. The results of the models were evaluated, and [mention any insights or conclusions drawn].

Feel free to explore the code in this repository to gain a deeper understanding of the project. If you have any questions or feedback, please don't hesitate to reach out.

Thank you for your interest in our machine learning project!

