# a5treasurer
Script that automatically aggregates the right numbers from bank statements to help Action Five's treasurer create the year-end report. Also, it sorts them correctly so they can be used easily to produce donation receipts.

# Business Case:
Before I started this project, the bank statements have been processed by the treasurer using Excel which was very time consuming and left the treasurer with hours of work which made the position of being a treasurer unattractive to the volunteers of the association and diverted attention from more central activities pertaining to financing the associations development projects. This project aims to reduce this time being spent on the number-crunching for the year-end report and donation receipt creation from hours to minutes by automatically reading in, and aggregating the financial data from bank statements, as well as distributing the donation data to the donation receipts.

# Data:
The input data consists of bank statements produced by Action Five's bank, GLS Gemeinschaftsbank, in semicolon-delimited files, as well as a blank version of a donation receipt.

# Project Structure
1. Reading in Data Files
2. Merging Data Files
3. Sorting Data for Year-End-Report
4. Aggregating Data for Year-End-Report
5. Output Aggregated Data for Year-End-Report
6. Input Blank Version of Donation Receipt
7. Sorting Data for Donation Receipts
8. Aggregating Data for Donation Receipts
9. Write Sorted and Aggregated Data into Donation Receipt Files
