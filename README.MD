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

## How to Run
1. Clone the repo:
   git clone https://github.com/<your-username>/<repo-name>.git
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn requests beautifulsoup4 sqlalchemy "psycopg[binary]"
3. Create a PostgreSQL database named `Customer_behavior`.
4. Set your connection string as an environment variable (don't hardcode it).
5. Run `Main.ipynb` to clean the data and load it into the `customer` table.
6. Run the queries in `sql/customer_behavior.sql`.

## License
MIT License

## Contact
Muhammed Ahmed Abd-Elghaney
LinkedIn: <link> · GitHub: <link>
