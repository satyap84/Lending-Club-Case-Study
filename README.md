# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#Contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending club is a consumer finance company which specializes in lending various types of loans to urban customers.
- Company has to make a decision for loan approval based on the applicant’s profile.
- The objective of analysis is to find the risks using the past data so that lending company can minimize the risk of loosing money  while lending to the customers.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Charged Off
- It is observed  that irrespective of loan amount, the customer is more likely to default if the interest rate is higher.
- Customers are more likely to default whose debt to income ratio is more than 25 or the loan amount is more than 25000(Irrespective of DTI value). Lending club should consider DTI metric to be less than 25 while issuing the loans.
- Grades and sub-grades are good metric for detecting defaulters. B grade loans have highest probability of defaulting followed by grades C and D. Sub-grades B5, B3 and C1 have highest probability of defaulting.
- Lending Club should consider giving lesser loan amount for customers with 2 bankruptcy public records. It has been observed that almost all the customers with 2 bankruptcy cases have defaulted and their median loan amount has been around 13000.
- To predict any upcoming default, lending company can use below indicators:
    - Customers has made 8 inquiries and has a loan amount greater than 15000.
    - Customer has 2 bankruptcy records and has a loan amount greater than 10000.

### Fully Paid
- A4, A5 and B3 sub grade loans have highest probability of being fully paid off. So, lending club can consider issuing more of these.
- Looking at the data it is strongly evident that any customer with more than 2 public records will not default irrespective of the loan amount. Lending club can use this information to grant loans with confidence.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.11.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contributors

- Satya Prakash
- Mythili Kandula


## Contact
Created by [@satyap84] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->