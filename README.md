# Employee Retention Predictor

## Employee Retention Predictive Modelling Project

![Employee Retention Predictor](assets/employee_photo.jpg)

## **Project Background** 

Salifort Motors is a fictional France-based vehicle manufacturer specialising in alternative energy vehicles. With a global workforce exceeding 100,000 employees, the company excels in researching, designing, manufacturing, validating, and distributing electric, solar, algae, and hydrogen-powered vehicles. Salifort's fully integrated vertical operations have established it as a global leader at the crossroads of alternative energy and the automotive industry.

### **Business Case**

Salifort Motors is experiencing a high rate of employee turnover. This turnover includes both voluntary resignations and terminations, and it poses significant challenges for the company. High turnover impacts Salifort's corporate culture, disrupts operations, and leads to financial losses due to the substantial investments required for recruiting, training, and upskilling employees. Understanding the factors driving employee departures is critical for improving retention, fostering job satisfaction, and minimising costs.

This project involves analysing employee survey data to uncover actionable insights and building a predictive model to assess the likelihood of employee attrition. By identifying patterns and trends, the company aims to proactively address underlying issues and implement targeted solutions to support employee success and professional development.

The model will be designed to predict whether an employee is likely to leave the company based on factors such as job title, department, number of projects, average monthly hours, and other relevant variables. A well-performing model will enable Salifort to:

- Identify employees at risk of leaving.
- Develop strategies to enhance job satisfaction and retention.
- Optimise resources by reducing the costs associated with turnover and new employee onboarding.

This project represents a critical step in strengthening Salifort Motors' workforce stability and maintaining its position as a leader in alternative energy innovation.

### **The Dataset**

The dataset that I'll be using for this project contains 15,000 rows and 10 columns for the variables listed below. The data is from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction/code)

| Variable                | Description                                                         |
| ----------------------- |:-------------------------------------------------------------------:|
| satisfaction_level      |  Employee-reported job satisfaction level [0–1]                     |
| last_evaluation         |  Score of employee's last performance review [0–1]                  |
| number_project          |  Number of projects emp                                             |
| average_monthly_hours   |  Average number of hours employee worked per month                  |
| time_spend_company      |  How long the employee has been with the company (years)            |
| Work_accident           |  Whether or not the employee experienced an accident while at work  |
| left                    |  Whether or not the employee left the company                       |
| promotion_last_5years   |  Whether or not the employee was promoted in the last 5 years       |
| Department              |  The employee's department                                          |
| salary                  |  The employee's salary (U.S. dollars)                               |
