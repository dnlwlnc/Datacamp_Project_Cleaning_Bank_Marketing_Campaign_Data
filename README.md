# Cleaning Bank Marketing Campaign Data
[DataCamp Project URL](https://projects.datacamp.com/projects/1613)
## Project Overview
This project involves cleaning and processing bank marketing campaign data to prepare it for a PostgreSQL database. The data relates to a personal loan marketing campaign conducted by a bank, with the goal of getting customers to take out personal loans.

## Data Processing
The project transforms a single input file (`bank_marketing.csv`) into three cleaned and formatted output files:

### Output Files:
1. `client.csv` - Contains client demographic information
   - Client ID, age, job type, marital status, education level
   - Boolean indicators for credit default and mortgage status

2. `campaign.csv` - Contains campaign-specific data
   - Contact attempts and duration
   - Previous and current campaign outcomes
   - Last contact date information

3. `economics.csv` - Contains economic indicators
   - Consumer price index
   - EURIBOR three-month rate

## Data Cleaning Requirements
- Date formatting to YYYY-MM-DD
- Boolean conversion for various fields
- Text standardization (replacing "." with "_")
- Handling of unknown values
- Data type standardization for database compatibility

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Project Structure
```
├── bank_marketing.csv    # Input data file
├── campaign.csv         # Cleaned campaign data
├── client.csv          # Cleaned client data
├── economics.csv       # Cleaned economic indicators
├── notebook.ipynb      # Data cleaning implementation
└── README.md
```

## Purpose
The cleaned data will be used to:
1. Set up a PostgreSQL database
2. Enable easy import of future campaign data
3. Maintain consistent data structure for analysis

## Dataset Context
The personal loan market represents a significant revenue stream for banks, with typical interest rates around 10% in the UK market. This data cleaning project supports the bank's broader marketing and analysis efforts in this sector.