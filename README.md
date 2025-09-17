Banking Transaction Management System
A MySQL-based Banking Transaction Management System showcasing database design, stored procedures, transactions, access control, and auditing for banking operations.

Features
Account Management: Store and manage account balances.
Fund Transfers: Secure fund transfers with balance validation.
Transaction Logs: Record deposits and withdrawals with timestamps.
Batch Processing: Execute multiple transfers using cursors.
Access Control: Manage multiple users with specific privileges.
Reports: Generate reports for deposits, withdrawals, and recalculated balances.
Project Files
account.csv: Sample dataset for accounts.
trnx.csv: Sample transfer instructions.
week14.sql: SQL script containing schema, stored procedures, and reports.
week14.pdf: Reference documentation.
How to Run
Create the Database:
CREATE DATABASE Bank;
USE Bank;
Run the SQL Script:
SOURCE week14.sql;
Load CSV Data:

Import account.csv into the account table.
Import trnx.csv into the move_funds table.
Use Stored Procedures:

transfer_funds_1: Perform a single transfer.
transfer_funds_2: Perform a transfer with enhanced validation rules.
main_transfer_2: Process multiple transfers in batch.
Generate Reports:

Deposits per account.
Withdrawals per account.
Final recalculated balances.
Skills Demonstrated
Database Design (MySQL)
Stored Procedures & Transactions
ACID Properties (Commit/Rollback)
User Privileges & Access Control
Cursors for Batch Processing
Data Integrity & Auditing
Future Enhancements
Interest calculation and monthly statements.
Role-based access control (Admin vs. Cashier).
Fraud detection triggers.
Dashboard for data visualization.
