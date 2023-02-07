# Lending Club Data Analysis
> Lending Club data analysis involves exploring and analyzing data from the peer-to-peer lending platform, 
Lending Club. The data can be used to understand trends in loan applications, borrower behavior, loan performance, 
and risk analysis. Analysts can use various statistical and machine learning techniques to gain insights,
 such as borrower credit score distribution, loan default rate, and loan grade. The results of the analysis can 
be used by investors to make informed investment decisions and by Lending Club to improve loan underwriting,
 portfolio management and risk management. By understanding the key drivers of loan performance and default risk, 
the platform can improve loan origination, reduce loan losses and increase returns for investors

# Business Objectives
This company is an online loan marketplace, offering personal, business and medical financing loans with low interest
 rates through a quick online platform. However, lending loans to high-risk applicants is the major cause of financial loss,
 referred to as credit loss. The aim of this study is to identify these high-risk applicants through exploratory data 
analysis (EDA) to reduce credit loss. The company's goal is to understand the key factors behind loan default and use 
this knowledge for portfolio and risk assessment. To enhance your understanding, you're encouraged to research the basics 
of risk analytics.When a loan application is submitted, the company can either accept or reject it. If the loan is accepted, 
there are three outcomes: fully paid, current (ongoing payment), or charged-off (defaulted). On the other hand, if the loan 
is rejected, there is no transaction history with the company and therefore not included in the available data.

# Loan Consideration
overdue when no payment has been received for a period of 16 to 120 days. A default on a LendingClub loan occurs when no payment 
has been received for over 120 days, approximately four months. A charge-off by LendingClub occurs when the
company does not anticipate receiving any further payments. This usually happens within 30 days of the loan entering a default state.

## Table of Contents

* General Information
  The Lending Club Data Analysis project is a comprehensive examination of data from the Lending Club, a peer-to-peer lending platform.
  The focus of the analysis is to identify the key factors that influence loan default. The methodology involved in this project includes
  importing the relevant Python libraries, conducting univariate analysis for both categorical and numerical data, creating a correlation
  matrix, and performing a deeper analysis of sub-grades and other factors. By using these techniques, the project aimed to gain a deeper
  understanding of the relationships between various factors and loan default. The insights gained from this analysis can be used to
  improve the lending process, minimize risk, and maximize returns for both borrowers and investors.

* Technologies Used
  1- Pandas
  2- Numpy 
  3- matplotlib
  4- seaborn 
  
  
* [Conclusions



* Acknowledgements
"I would like to express my heartfelt gratitude to Chris Flood, my project partner, for his unwavering support and invaluable contributions
 throughout this project. I would also like to extend my gratitude to the developers and contributors of Github previous projects that 
 served as a reference for my work. The solutions I found on Stack Overflow were instrumental in overcoming the challenges I faced during
 the project.I am deeply thankful for all the support and resources
 that made this project a success. Thank you all."




Analysis 
## General Information
1-The major loan grades are B, A, and C.
2-The majority of loan status is "Fully Paid" at 83%.
3-Grade B and C have the largest number of charge-offs, while grade F has the highest percentage of charge-offs compared to the loans issued under this grade.
4-The information obtained from the home ownership shows a useful result but there is no strong correlation between home ownership and charge-off. It was found that homeowners with a "free and clear" status have a very low probability of borrowing or being charged off.
5-The results from the verification status indicate that the company needs to change their verification process.
6-There is a strong correlation between the purpose of the loan and charge-off, with borrowers who borrowed money for debt consolidation or credit card having a high likelihood of being charged off.
7-The loan amount has a positive correlation of 0.88% with charge-off.
8-The installment to loan ratio also has a positive correlation.
9-Strong Relation Observed between Loan Amount Requested and Approved Loan Amount
Increase in Charge Off for Borrowers Receiving a Lower Counter Offer than Requested




## Conclusions








## Contact
Created by https://github.com/hermesresearch - feel free to contact me!


