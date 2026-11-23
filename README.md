# VELOOP Rewards – Product Analytics & Data Quality Audit

## Project Overview

This project analyses simulated VELOOP Rewards data to understand user behaviour, product engagement, retention, task activity, XP balance and data quality.

The project demonstrates a practical data analytics workflow, from raw data inspection and cleaning to Python analysis and Power BI dashboard development.

**Data disclaimer:** All datasets and findings are simulated for learning and portfolio purposes. They do not represent actual VELOOP company performance.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Microsoft Excel
- Google Colab
- Power BI

## Project Objectives

- Inspect user, session, event and task datasets.
- Identify missing values and duplicate records.
- Clean and standardise data.
- Analyse user activity and task performance.
- Calculate D1, D7 and D14 retention.
- Analyse XP balance distribution.
- Audit wallet data availability.
- Build an interactive Power BI dashboard.

## Analysis Performed

### 1. Data Quality Audit
Checked missing values, duplicate identifiers, inconsistent text values, data types and date consistency.

### 2. User Behaviour Analysis
Reviewed user records, sessions, feature events and daily activity.

### 3. Task Performance
Examined task statuses and completion information.

### 4. Retention Analysis
Calculated D1, D7 and D14 retention using registration dates and daily activity.

### 5. XP Balance Analysis
Reviewed the distribution of simulated XP points.

### 6. Wallet Data Availability
Reviewed the availability of wallet-related fields. A complete transaction-level wallet ledger was not identified, so full wallet reconciliation could not be verified.

## Key Data Quality Findings

- 8 repeated user IDs in the messy user audit dataset.
- 8 repeated referral codes in the messy user audit dataset.
- 10 repeated event IDs in the event data quality audit.
- 4 event status values contained trailing whitespace.
- Missing values were identified in selected user, session and task fields.
- Basic session timestamp checks found no negative durations or end times earlier than start times.

## Power BI Dashboard

The dashboard includes:

- Total Users
- Total Sessions
- User Retention Analysis
- XP Balance Distribution
- Missing Values by Dataset
- Duplicate Records by Dataset
- Task Status Distribution
- Feature Event Status Distribution
- Wallet Data Availability Audit
- Key Insights

## Project Files

- Final Project Report (PDF)
- Python Analytics Results (Excel)
- Cleaned Analytics Workbook (Excel)
- Google Colab Notebook
- Power BI Dashboard (PBIX, where file size permits)
- Power BI Dashboard Export (PDF)
- Python Analytics Report (TXT)
- Dashboard Screenshots

## Conclusion

This project demonstrates practical skills in data inspection, data cleaning, exploratory analysis, retention measurement, data quality auditing and dashboard development.

It shows how raw simulated data can be transformed into structured analytical outputs for reporting and decision-making.

**Project Type:** Simulated Data Analytics Portfolio Project.
