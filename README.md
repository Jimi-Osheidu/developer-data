# developer-data
An exploratory analysis of Stack Overflow's 2022 Developer Survey. Using pandas in Python, I explored median pay across various countries and dropped some columns, then exported a new csv file for visualisation with Tableau.
The dataset surveys 73,268 software developers from 180 countries around the world, the questions asked ranged from years of coding experience, what technologies used, to ethnicity, sexuality and pay.
I mainly focused on how much developers from different countries earned and compared that to their educational status to see if higher educational qualifications correlated with higher median pay. The salary question, like most on the survey, was optional. There were 38,071 respondents who provided salary data.
These salaries were converted from the user’s currency to USD using the exchange rate on May 24, 2022, and also converted to annual salaries assuming 12 working months and 50 working weeks.
