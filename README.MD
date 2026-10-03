# 🛍️ Customer Shopping Behavior Analysis

## About
An end-to-end data analysis project exploring how ~3,900 customers shop:
what they buy, how much they spend, and how discounts, subscriptions,
and shipping types affect their behavior. The data is cleaned with
Python, stored in PostgreSQL, and analyzed using SQL.

## Key Questions Answered
- Revenue split between male and female customers
- Do discounted purchases still exceed the average spend?
- Top-rated products and top products per category
- Average spend by shipping type (Standard vs. Express)
- Subscribers vs. non-subscribers: spend and revenue
- Customer segments: New / Returning / Loyal
- Revenue contribution by age group

## Features
- Data cleaning: missing values, column standardization, duplicate checks
- Feature engineering: age groups, USD → EGP conversion (live rate)
- Loading data into PostgreSQL with SQLAlchemy
- SQL analysis with aggregations, subqueries, and window functions

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · BeautifulSoup · SQLAlchemy · PostgreSQL

## Project Structure
├── data/customer_shopping_behavior.csv
├── notebooks/Main.ipynb
├── sql/customer_behavior.sql
└── README.md
