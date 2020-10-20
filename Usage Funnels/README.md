Analyze Real Data with SQL

===1
Start by getting a feel for the survey_responses table.  
Select all columns for the first 10 records from survey_responses.  

===2
Count the number of distinct user_id who answered each question_text.
You can do this by using a simple GROUP BY command.
What is the number of responses for each question?

===3
Start by getting a feel for the onboarding_modals table.  
Select all columns for the first 10 records from onboarding_modals.  

===4
Delete your previous code.
Using GROUP BY, count the number of distinct user_id‘s for each value of modal_text. This will tell us the number of users completing each step of the funnel.
This time, sort modal_text so that your funnel is in order.

===5
Delete your previous code.  
The previous query combined both the control and variant groups.  
We can use a CASE statement within our COUNT() aggregate so that we only count user_ids whose ab_group is equal to ‘control’ 

===6
Add an additional column to your previous query that counts the number of clicks from the variant group and alias it as ‘variant_clicks’.  

===7
Let’s examine each table. Note that each user has multiple rows representing the different items that she has placed in her cart.

===8
Start by selecting all rows (*) from the LEFT JOIN of:
browse (aliased as b)
checkout (aliased as c)
purchase (aliased as p)

Be sure to use this order to make sure that we get all of the rows.
LIMIT your results to the first 50 so that it loads quickly.
