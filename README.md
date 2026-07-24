# n8n-invoice-automation
n8n workflow that extracts invoice data using regex and saves to "Google Sheets".
# Invoice Data Extraction Automation (n8n)

This workflow automatically extracts the following data from invoice text:
- Vendor name
- Amount
- Invoice date
- Due date

The extracted data is then saved to Google Sheets for tracking purposes.

## Tools Used
- n8n (workflow automation)
- JavaScript (Code node - regex pattern matching)
- Google Sheets API

## How It Works
1. Takes invoice text as input
2. Code node extracts key fields using regex
3. Appends a new row to Google Sheets with the extracted data

## Use Case
This automation is useful for freelancers, small businesses, or accounting teams who want to automatically track invoices without manual data entry.
