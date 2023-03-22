# Prediction of Lead Score using Logistic Regression
This is a machine learning project in Python that aims to predict the lead score of potential students who may be interested in purchasing a study course. The prediction is based on various factors such as age, income, and education level.

# Project Objective
The objective of this project is to develop a logistic regression model that can accurately predict the lead score of potential students. This will help the study course provider to identify potential customers who are more likely to buy their course.

# Dataset
The dataset used in this project is a simulated dataset that consists of various attributes related to a student who is interested in buying a study course. The dataset contains the following columns:

Prospect ID: A unique identifier for each student.

Lead Number: A unique identifier assigned to each lead.

Lead Origin: The origin of the lead.

Lead Source: The source of the lead.

Do Not Email: A flag indicating whether the student has opted out of email communications.

Converted: A flag indicating whether the lead was converted to a customer or not.

TotalVisits: The total number of visits made by the student to the website.

Total Time Spent on Website: The total time spent by the student on the website.

Page Views Per Visit: The average number of pages viewed per visit.

Country: The country from which the student is accessing the website.

Specialization: The specialization that the student is interested in.

How did you hear about X Education: The source through which the student heard about the education company.

What is your current occupation: The occupation of the student.

Lead Quality: The quality of the lead.

Lead Profile: The profile of the lead.

# Tools and Technologies Used
Python 3.7
Pandas, NumPy, and Matplotlib libraries
Scikit-learn library for logistic regression

# Analysis
The analysis is done using visualization by creating various graphs from the data. Some of the graphs are:

![lead_score converted](https://user-images.githubusercontent.com/113959612/226966589-46ace7de-e671-4490-a5f8-e1b4bcdcac72.png)



![lead_score last activity](https://user-images.githubusercontent.com/113959612/226966675-55c722cc-a427-499e-b8c1-0392c1adab6e.png)



![lead_score heat_map](https://user-images.githubusercontent.com/113959612/226966758-a0b03ab5-059b-4961-9097-c990af86bd32.png)

# R.O.C Curve

![lead_score trade_off](https://user-images.githubusercontent.com/113959612/226967038-975abd65-6e0c-4353-96d8-ff9396613234.png)

# Threshold between accuracy,sensitivity,specificity.

![lead_score threshold](https://user-images.githubusercontent.com/113959612/226966931-011061e0-6b74-442f-a54b-9cdbf0358db2.png)

# Result

![lead_score summary](https://user-images.githubusercontent.com/113959612/226967157-4dd443a9-bc1e-46ef-bb82-20b3d005977f.PNG)

# Conclusion
This project demonstrates how logistic regression can be used to predict the lead score of potential customers for a study course provider. The model can help the provider to identify potential customers who are more likely to buy their course, and they can focus their marketing efforts accordingly.
