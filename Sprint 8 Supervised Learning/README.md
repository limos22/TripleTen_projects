# Supervised Learning

## Introduction

Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.

## Goal

Build a model with the maximum possible F1 score. The F1 scores should be at least 0.59.

## Description of the Data

Contents of the dataset `Churn`:

**Features**

- `RowNumber` — data string index
- `CustomerId` — unique customer identifier
- `Surname` — surname
- `CreditScore` — credit score
- `Geography` — country of residence
- `Gender` — gender
- `Age` — age
- `Tenure` — period of maturation for a customer’s fixed deposit (years)
- `Balance` — account balance
- `NumOfProducts` — number of banking products used by the customer
- `HasCrCard` — customer has a credit card
- `IsActiveMember` — customer’s activeness
- `EstimatedSalary` — estimated salary

**Target**

- `Exited` — сustomer has left

## Tools

- Python
  - Pandas
  - Matplotlib
  - SciKitLearn
  - Seaborn
  - Numpy
