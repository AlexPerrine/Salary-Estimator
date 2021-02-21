# Salary-Estimator

### Project Overview
Modeling
Intro parahgraph about purpose of project
- Created a baseline model to predict MAE by predicting set values of 50k, 100k, the mean, 150k and 200k. 
- Demonstrated different ways to reduce model complexity of Linear Regression, Lasso Regression and Gradient Boosting while reducing the Mean Absolute Error.
- The best model reduced the MAE to 15.33.
---
### Mean Absolute Error
Mathematically, the mean absolute error is the average of the absolute errors or average amount of distance between the measured value and the 'true' value. 

Think of it this way, imagine you are trying to predict salaries. The MAE says, on average the salary will be mis-preducted by $x, where x is the MAE. Albeit, knowing the MAE does not mean you know which direction. Thus we could predict $x over or $x under, on average.

---
### Model Building
To feed the models the data, I built a pipeline which used a column transformer to one hot encode the categorical features and passed the numerical features through. 

Using a baseline model
- ### Linear Regression

---
- ### Lasso Regression

---
- ### Gradient Boosting

---
### Scenario
Imagine you're the data scientist at company ABC that is in the beginning stages of a growth spurt.

Imagine, you are a data scientist for ABC, a medium sized healthcare techonology company. Whose goal is to help people get fit and make healthy eating choices. ABC has had jobs posted online for many different roles; CEO, CTO, CFO, VPs, etc. For weeks you've seen people come and go for interviews, met many potential coworkers, went out for a lunch interview etc. You've given feedback to your manager about who you think they should hire to join the team. Offer letter after offer letter goes out but no new coworker has come in. Why? Why spend all the time in the 3 interviews to turn down the offer? Is the culture too friendly? Are we offering the correct salaries? The location too far from a public parking place? Does ABC need to pay for parking? Are currently employees even happy here? Are we still too much in the start-up phase?
=======
- Created a tool for fictitious ABC company to estimate salaries (insert the MAE) while building offer letters for potential employees.
- Built a Pipeline to sequentially OneHotEncode with a ColumnTransformer and fit to different models.
- Used RandomizedSearchCV to optimize Random Forests, Gradient Boosting and used GridSearchCV to optimize n_estimators for XGBoost to reach the best model.

---
### Scenario
Imagine, you are a data scientist for ABC, a medium sized healthcare techonology company. Whose goal is to help people get fit and make healthy eating choices. ABC has had jobs posted online for many different roles; CEO, CTO, CFO, VPs, etc. For weeks you've seen people come and go for interviews, met many potential coworkers, went out for a lunch interview etc. You've given feedback to your manager about who you think they should hire to join the team. Offer letter after offer letter goes out but no new coworker has come in.

Why? Why spend all the time in the 3 interviews to turn down the offer? Is the culture too friendly? Are we offering the correct salaries? The location too far from a public parking place? Does ABC need to pay for parking? Are currently employees even happy here? Are we still too much in the start-up phase?
 main

During a meeting with your manager you ask if you can help. You ask what data source we are using to come up with the salaries that we are offering. You explain to your manager how you can use their data to build a regression model to help predict more of an accurate starting salary to offer. Maybe the issue is people get offended by the lower than expected salary and instantly decline.

At this point the company needs to fill some roles, so your manager hands over the data they use for determining the salaries for their intitial offer letters. To show how much the predicted value is from the actual value, I will use Mean Absolute Error. This will allow me to describe to my manager the actual dollar amount error the model has.

### Code & Resources