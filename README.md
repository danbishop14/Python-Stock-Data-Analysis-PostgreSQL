README
# Introduction
This python script uses the pandas, yfinance, numpy, and psycopg2 libraries to pull data from Yahoo Finance for a given ticker, clean the data for compatibility with PostgreSQL, and create a local PostgreSQL database with the following tables:

- options_chain: contains option chain data
- hist_prices: contains historical stock prices for a given ticker
- instit_ownership: contains institutional ownership data
- earnings: contains earnings data
- info: contains information about the company associated with the given ticker

## Setup
1. Install the required libraries: pandas, yfinance, numpy, and psycopg2

2. Create a PostgreSQL database and user with the following credentials:

- user: postgres
- password: password
- host: localhost
- port: 5432
- database: postgres
