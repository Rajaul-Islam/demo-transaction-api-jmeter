# Dmoney API Performance Test (Dmoney)

## About this project:
### This is A Simple API Load Testing Project Where I try to t find Out The Real capability of the server by giving load with some action like 5000 user try to register at the same time. After that, I have done all the assertion points to do the API Automation and then generate the HTML Report. Finally, I have generated report using Newman.

## Tools & Technology used:
- postman
- newman
- 
## Tools Used
- Jmeter


## How to run this project

- Clone This project
- Then run the following command 

```bash
 $ jmeter -n -t Jmeter Performance test using API Chaining.jmx -l Dmoney-Load-Test.csv -e -o Reports
```



## Test case
- https://docs.google.com/spreadsheets/d/1-j7Gq2wA5WnfXxYAsnuwEszlTsU2axlGQ035e_qcjM0/edit?usp=sharing
## Bug Report
- https://docs.google.com/spreadsheets/d/1Km-PmmRyOQA6TA2moEafreRc_uH-tyFVymFEspORhys/edit?usp=sharing
## d-money URL
- https://documenter.getpostman.com/view/22666982/2s9Y5WxipX

## Test Report
![report](https://github.com/Rajaul-Islam/API-Automation/assets/86623372/91f498e0-0409-4ea8-a29b-51049db2e215)


## Performance test have done based on following scenario.

1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)

## Request I have Covered

1. Login to user
2. Create a new agent/customer
3. Give balance to the newly created agent from system
4. Search the customer's current balance by using phone number
5. Withdraw money from customer to agent account.
6. Payment form customer account to merchant account.
7. Delete the user