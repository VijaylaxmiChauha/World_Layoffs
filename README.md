# World_Layoffs
This project focuses on tracking and analyzing global layoffs across various industries, using SQL to store, query, and analyze data. The goal is to provide insights into trends, patterns, and factors influencing job cuts across companies worldwide.

Features :-
1. Layoff Data Collection: Database schema to store detailed information about layoffs globally.
2. Company & Layoff Information: Track company names, industries, layoff dates, employee numbers, and reasons.
3. Trend Analysis: SQL queries to Clean the raw data then perform EDA and then identify trends in layoffs by company, industry, or region.
4. Data Insights: Generate reports on the most affected sectors and predict future layoffs based on existing data.

The database contains the following tables:-
1. Companies: Information about the companies involved in layoffs.
 Columns: company_name, industry, location, date_established, stage, country, fund_raised etc.
 
2. Layoffs: Records of layoffs by each company.
 Columns: layoff_id, total_laid_off, percentage_laid_off, layoff_date, num_employees, region, etc
