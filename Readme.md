Simple Data Pipeline design to process data from various sources.

# Requirements

Must have Python to run the scripts and installed following dependencies

pip install pandas sqlalchemy psycopg2


# Sample Data

The scripts are designed to run on the sample files and data shown as below:

Flat Files: 'sales-data.csv'
Database: 'products.csv' , 'transactions.csv'
Sample Customer API data:
    [
        {
            "Customer_ID": 1,
            "Customer_Name": "John Doe",
            "Age": 95,
            "Gender": "",
            "Location": "Unknown",
            "Date_Joined": "2020-07-04"
        },
        {
            "Customer_ID": 2,
            "Customer_Name": "Charlie Brown",
            "Age": 43,
            "Gender": "",
            "Location": "Texas",
            "Date_Joined": "2020-02-04"
        },
    ] 
Sample Exchange Rate API data:
    [
    {
        "Currency_Code": "AUD",
        "Exchange_Rate": 1.0467,
        "Date": "2022-10-10"
    },
    {
        "Currency_Code": "EUR",
        "Exchange_Rate": 0.8946,
        "Date": "2022-01-21"
    },
    ]


The mock server can be setup using Postman tool for testing data from APIs.
Also, environment variables can be used to provide URLs, credentials and tokens for hiding sensitive data.

Note: Further enhancements and feature engineering can be done to process data that slightly deviate from the sample data used. 


