# Lending Club Case Study
> The main objective of this case study is to be to identify the risky loan applicants, where there is a tendency of a default, so that the loans can be reduced thereby cutting down the amount of credit loss.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)



## General Information
- LendingClub is a peer-to-peer lending platform that connects borrowers and investors. It offers personal loans, business loans, and student loans, providing a streamlined and transparent borrowing process. Borrowers can access funds at competitive rates, while investors can diversify their portfolios by funding fractional loans and earning attractive returns.

- To identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- We used 'loan.csv' which contains the complete loan data for all loans issued through the time period 2007 t0 2011.



## Conclusions
- If the term of the loan is higher, (Ex. 60months) the default rate is more likely to increase. The company should be careful while approving loans with higher terms.
- The default rate will increase if we go down the grade. The default rate is lowest for grade A and the highest for grade G. Similar results are seen for the subgrades. 
- For smalll business the default rate is the highest. If a person is applying for a loan for a small busniess then that person is more likely to default.
- Default rate is increasing with the decrease in annual income. People with less annual income are more likely to default.
- Default rate is increasing with increase in loan amount. Amounts greater than 15000 are facing the highest defaults.
- Higher interet rates will alwayts increas the defaults.
- Issuing loans in state NE can be risky.
- Higher installments will increase the defaults.
- Default rate increases with increase in dti ratio.



## Technologies Used
- Python NumPy 1.23.2
- Python Pandas 1.4.4
- Python Matplotlib 
- Python Seaborn 0.12.2



## Contact
Created by 
Sumeetkumar Tripathi and Harish Dambalkar
[@philipfranklin] [@harishdambalkar2020]
