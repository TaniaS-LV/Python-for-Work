# Automating monthly KPI update

For one of the stakeholders I regularly needed to update a report on new free trial sign ups, paid subscriptions and cancellations to calculate Conversion and Churn Rate, and, just like in any SaaS solution, these numbers tend to change over time: a user who signed up in March, may pay for subscription in November and then cancel it in February and then subscribe again. All these changes need to be reflected in the main dashboard. 

![dashboard example](https://user-images.githubusercontent.com/91870217/210390040-86ecef8a-ddeb-4866-b7ed-8971c8ff6c1f.JPG)


To track all these changes in a Google Sheet Dashboard, I wrote a Python script which cleans the data from the database and creates a report for monthly cohorts. 

*Python packages used: pandas, datetime, time, gspread for communicating with Google Sheets API*
