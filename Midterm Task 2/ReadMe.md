
## Midterm Lab Task 2 -  Data Cleaning and Preparation using POWER QUERY
* Task Description:
Company X would like to extract some useful information from the UnclenedDSJObs csv taken
from a Job Posting site available in Kaggle. There are a lot of columns available but focus only
on generating insights that will answer the ff: questions
1. exWhich Job Roles pay the highest and least
2. What size companies pay the best
3. Where Job Roles or Job Titles pay the best and least in a specific state
   
# Data Cleaning process
* Salary Estimate Column – Remove All the characters after the ( open  parentheses) by GOING to
* Create 2 New Columns (From the Salary Estimate) Min Sal and Max Sal
* ADD COLUMN – Role Type
* SPLIT COLUMNS by Delimeter
* Select Location column (SPLIT columns by , Delimeter)
* Copy the APPLIED steps as proof of your Data Cleaning Activities
* Create a duplicate of the raw data Right Click Unclean DS Jobs select  
duplicate (Queries pane)
* Rename the duplicate with “Sal By Role Type dup”
* Create a reference of the raw data Right Click Unclean DS Jobs  choose reference (Queries pane)
* Rename the reference with “Sal By Role Size ref”
* Mapping Other Files and include in the current queries
* Create a reference of the raw data Right Click Unclean DS Jobs  choose reference (Queries pane)
* Rename the reference with “Sal By State ref”
* o view dependencies and References of the QUERIES
* You Final Queries should include the ff: (Sal by Role type – dupl, Sla By size ref, state, Sal by State ref  and Uncleaned DS Jobs

# Normalization
* Dependencies and References of the QUERIES
![Sample Output](image/Uncleaned.png)

# Here's the screenshot of my output before I started data cleaning
![Sample Output](image/Uncleaned.png)
# Here's the screenshot of my output after I started data cleaning 
![Sample Output](image/cleaned.png)

# Here's the Physical Data Model
![Sample Output](image/Erd.png)
