# Salary-Estimator

### Project Overview
Created a tool for fictitious ABC company to estimate salaries (MSE of 356) while building offer letters for potential employees.
Built a Pipeline to sequentially OneHotEncode with a ColumnTransformer and fit to different models.
Used RandomizedSearchCV to optimize Random Forests, Gradient Boosting and used GridSearchCV to optimize n_estimators for XGBoost to reach the best model.

---
### Scenario
Imagine, you are a data scientist for ABC, a medium sized healthcare techonology company. Whose goal is to help people get fit and make healthy eating choices. ABC has had jobs posted online for many different roles; CEO, CTO, CFO, VPs, etc. For weeks you've seen people come and go for interviews, met many potential coworkers, went out for a lunch interview etc. You've given feedback to your manager about who you think they should hire to join the team. Offer letter after offer letter goes out but no new coworker has come in. Why? Why spend all the time in the 3 interviews to turn down the offer? Is the culture too friendly? Are we offering the correct salaries? The location too far from a public parking place? Does ABC need to pay for parking? Are currently employees even happy here? Are we still too much in the start-up phase?

During a meeting with your manager you ask if you can help. You ask what data source we are using to come up with the salaries that we are offering. You explain to your manager how you can use their data to build a regression model to help predict more of an accurate starting salary to offer. Maybe the issue is people get offended by the lower than expected salary and instantly decline.

At this point the company needs to fill some roles, so your manager hands over the data they use for determining the salaries for their intitial offer letters.

