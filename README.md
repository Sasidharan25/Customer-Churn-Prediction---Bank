# Customer-Churn-Prediction---Bank


PROBLEM STATEMENT

Given the attributes of various customers of a bank, we need to build a model that can help predict if a customer's average balance will fall below minimum balance in the upcomimg quarter, based on current activity;

FEATURES IN DATASET

1. **Customer_ID** - ID of customer          
2. **Vintage** -  vintage of the customer with the bank, in number of days                            
3. **Age**  -  age of customer                            
4. **Gender** - gender of customer                            
5. **Dependents** - number of dependents
6. **Occupation** - occupation of customer
7. **City** - city of customer (integer coded) 
8. **customer_nw_category** -  net worth of customer (integer coded)
9. **branch code** - branch code for customer account
10. **days_since_last_transaction** - no of days since last credit in last 1 year
11. **current_balance** - balance as of today
12. **previous_month_end_balance** - end of balance previous month
13. **average_month_end_balance_prevQ** - average monthly balance in previous quarter
14. **average_month_end_balance_prevQ2** - average monthly balance in previous to previous quarter
15. **current_month_credit** - total credit amount current month
16. **previous_month_credit** - total credit amount previous month
17. **current_month_debit** - total debit amount current month
18. **previous_month_debit** - total debut amount previous month
19. **current_month_balance** - average balance of current month
20. **previous_month_balance** - average balance of previous month
21. **churn** - average balance of customer falls below minimum balance in next quarter (1 : yes, 0 : no)
