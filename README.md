# Rule Based Classification and Lead Calculation with Python


## Business Problem

A game company wants to create level-based new customer definitions (personas) by using some features of its customers, and to create segments according to these new customer definitions and to estimate how much the new customers can earn on average according to these segments.

E.g: It is desired to determine how much a 25-year-old male user from the Turkey, who is an IOS user, can earn on average.

## Dataset Story

The Persona.csv dataset contains the prices of the products sold by an international game company and some demographic information of the users who buy these products. The data set consists of records created in each sales transaction. This means the table "is not deduplicated". In other words, a user with certain demographic characteristics may have made more than one purchase.

## Variables (Features)
- PRICE: Customer spend amount,
- SOURCE: The type of device the customer is connecting to (IOS/Android),
- SEX: Gender of the customer,
- COUNTRY: Country of the customer,
- AGE: Age of the customer.
