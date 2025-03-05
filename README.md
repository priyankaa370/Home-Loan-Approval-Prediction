# Home Loan Approval Prediction 
 The Dream Housing Finance company wants to automate the home-loan eligibility process based on the details provided by the customers while filling out the application form. This will significantly reduce the time taken to assess each application and enable the company to save time on decision making. The company also wants to determine the factors influencing the loan approval so that the marketing team can focus on targeting desirable customers. 
  
  Here is a sample link to demonstrate how this automation will help the Mortgage Underwriter team to decide whether to approve or reject the home application -
 
 [https://finance-loan-approval-prediction.onrender.com](https://finance-loan-approval-prediction.onrender.com)


# Data structure 
Dream Housing Finance company’s data structure consists of four tables – Applicant, Co-applicant, Loan, and Property. The company allows each applicant to apply for many loans. Additionally, only one co-applicant is considered during this process. 

Below is the Entity-Relationship Diagram for the Dream Housing Finance comapany data.

![Home Loan ERD drawio](https://github.com/user-attachments/assets/d1279ceb-8cc8-4509-9d01-96638ed67664)

# Executive Summary

A dataset collected from the application form containing applicant information was analyzed. A logistic regression model was employed to predict loan approval outcomes based on key features. 

The classification model achieved an overall accuracy of 90% on the test dataset, demonstrating moderate reliability in predicting loan approval outcomes.
The findings show that **credit history** is the most influential factor in determining loan approval with an importance score of 0.24. Following credit history, **the applicant's income and the loan amount** are the second and third most critical factors influencing loan approval decisions. 

# Recommendations

•	**Target customers with stronger credit history.** The marketing teams should focus on attracting customers with good credit scores. Tailoring marketing campaigns with such emphasis will improve the loan approval rates and reduce any financial risks for the company. 

•	**Introduce personalized loan offers based on the income and loan amount.** The lending team should consider segmentation of the customers based on their income and loan amounts. Then they can propose unique loan offerings. For example, individuals with higher incomes and moderate loan amounts could be offered more favorable terms, increasing approval chances while maintaining profitability.

•	**Automate the data collection procedure and pre-processing.** To further reduce processing times, the Mortgage Underwriter team can implement an automated pre-screening tool. This could provide customers with an instant eligibility estimate, streamlining the application process and reducing the burden on loan officers.





