# Automating a Bank Reconciliation

## About this project
Every month, finance teams check that the company's cash book matches the bank statement.
Doing this by hand in Excel takes a long time and mistakes are easy to miss.

This project uses **Python (pandas)** to do the bank reconciliation automatically.

## What the program does
1. Reads the cash book and the bank statement (CSV files)
2. Matches transactions using the reference number
3. Finds items that do not match:
   - Payments and receipts in transit (timing differences)
   - Bank charges, interest and direct debits not yet in the cash book
   - Amount errors (for example, 604.00 recorded instead of 640.00)
4. Creates a bank reconciliation statement and saves it to Excel

## Files
| File | What it is |
|---|---|
| `cash_book.csv` | Company's cash book (sample data) |
| `bank_statement.csv` | Bank statement (sample data) |

## Tools
Python, pandas, Jupyter Notebook, GitHub Codespaces

## About me
I am a senior finance executive moving into data analytics.
I have hands-on experience in AP, AR, GL and bank reconciliation, and I am using Python to automate finance work.

LinkedIn: [linkedin.com/in/joannegohkp](https://www.linkedin.com/in/joannegohkp)

*Note: All data in this project is sample data made for practice. It is not real company data.*

*Status: In progress*
