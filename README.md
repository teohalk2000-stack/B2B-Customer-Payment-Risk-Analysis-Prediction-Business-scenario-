B2B Customer Payment Risk Analysis & Prediction

Project Overview

This project explores whether historical customer, invoice, payment, and order data can be used to predict significant payment delinquency among B2B customers.

Using a synthetic dataset representing a fictional B2B commercial company, the project follows an end-to-end data analytics and machine learning workflow.

Tools & Technologies

Google Sheets: Initial data cleaning and quality checks.

SQL: Data integration, consistency checks, data transformations, and feature engineering.

KNIME: Data preparation, Logistic Regression and Random Forest modeling, and model evaluation.

Methodology

Data cleaning and quality assessment.

SQL-based data integration and customer-level feature engineering.

Definition of significant payment delinquency as the target variable.

Data preparation and multicollinearity assessment.

Development and evaluation of Logistic Regression and Random Forest models.

Key Findings

Both models achieved relatively low predictive performance:

Logistic Regression: AUC = 0.557

Random Forest: AUC = 0.513

The findings suggest that the synthetic dataset may not contain sufficiently strong or consistent relationships between historical customer behavior and future payment delinquency.

Despite the limited predictive performance, the project demonstrates a complete analytical workflow, from raw data preparation to predictive modeling and evaluation.

Project Documentation

Full Report: [https://drive.google.com/file/d/1R2d7MlI5U1jXY0ddamB4PUWRM4W-aDkJ/view?usp=drive_link]

Dashboard: [https://docs.google.com/spreadsheets/d/1y5LwcdDdAfOK1dsIu3VV0MCvGiBIrpTEMpevY-gJuGk/edit?usp=drive_link]

Dataset

The dataset is synthetic and was designed to simulate approximately 18 months of B2B business operations across four tables: Customers, Invoices, Payments, and Orders.
