# HR-Analytics

## Background:
Client service is all about the quality of the people involved in delivering business. However, one of the major challenges for any company revolved around managing a quality workforce. Organizations spend tremendous amount of time and energy to create a homogenous environment where people thrive and succeed. Despite all the efforts to maintain an environment that is conducive, people leave organizations in search of better opportunities. In order to fill the vacuum, HR is bound to recruit new talent, thus forming a vicious circle in between attrition and recruitment; and in order to mitigate this, organizations keep trying to bridge the gap by strengthening their recruitment processes and creating a culture of inclusivity.

## Problem of Renege:
A significant proportion of the candidates do not join the company that has made an offer. In a typical IT services company, the number of people not joining the company varied anywhere between 15% and 35% of all the people who accepted the offer. The impact may seem minimal if the number of offers rolled out to candidates revolved around hundreds in a year. However, if the offers rolled out surpassed the thousands mark, the magnitude of impact increased exponentially. 

For a client where 12,000 offers were rolled out every year. At 30% renege rate, about 3,600 candidates would accept the offer and then not join the company. Even with the most conservative estimates, on average, organizations would have spent 15 man hours per candidate in the recruitment lifecycle, effectively indicating a humongous loss of 54,000 man hours wasted by one client alone. This involves the time spent by the company in interviewing the candidate whose value is more than the mere numbers of hours.

Renege has greater impact on the cost of talent acquisition. The entire recruitment lifecycle starting from sourcing resumes until candidate is deemed fit for recruitment, involves various agencies. These agencies work in tandem with the talent team to screen for candidates who would fit the profile. A payout is provided to these agencies for their involvement in the recruitment cycle. It was estimated that owing to the renege candidates, the cost of hiring increased anywhere between 10% and 15%.

## Objective:
1. What are the key drivers that influence the candidate joining/not-joining a company?
2. Devising a predictive algorithm to calculate the probability of acceptance of an offer and joining the company after offer acceptance stage.

## Findings and Conclusion:
The top 5 key drivers that influence the candidate's joining of a company are:
* Notice Period
* Candidate Source 
* Line of Business
* Offered Band
* Age

The Logistic Regression Model was built to predict the candidates probability of acceptance of an offer. 
The Code and analysis of the Model are available in the [R-Notebook](https://github.com/devashishpatel/HR-Analytics/blob/master/HR%20Analytics.ipynb)

## Data-set:
The Data-set comprised of around 9000 observations and 16 Variables.

1 Candidate reference number
  Unique number to identify the candidate
  
2 DOJ extended
  Binary variable identifying whether candidate asked for date of joining extension (Yes/No)
  
3 Duration to accept the offer
  Number of days taken by the candidate to accept the offer (continuous variable)
  
4 Notice period
  Notice period to be served in the parting company before candidate can join this company (continuous variable)
  
5 Offered band 
  Band offered to the candidate based on experience and performance in interview rounds (categorical variable labelled C0/C1/C2/C3/C4/C5/C6)
  
6 Percentage hike (CTC) expected
  Percentage hike expected by the candidate (continuous variable)
  
7 Percentage hike offered (CTC)
  Percentage hike offered by the company (continuous variable)
  
8 Joining bonus
  Binary variable indicating if joining bonus was given or not (Yes/No)
  
9 Gender
  Gender of the candidate (Male/Female)
  
10 Candidate source
  Source from which resume of the candidate was obtained (categorical variables with categories: Employee referral/Agency/Direct)
  
11 REX (in years)
  Relevant years of experience of the candidate for the position offered (continuous variable)
  
12 LOB
  Line of business for which offer was rolled out (categorical variable)
  
13 DOB
  Date of birth of the candidate
  
14 Joining location
  Company location for which offer was rolled out for candidate to join (categorical variable)
  
15 Candidate relocation status
  Binary variable indicating whether candidate has to relocate from one city to another city for joining (Yes/No)
  
16 HR status
  Final joining status of candidate (Joined/Not-Joined)
  
