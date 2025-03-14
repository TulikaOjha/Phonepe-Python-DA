# PythonCaseStudy
This case study focuses on analyzing transaction data from the financial application PhonePe, along with demographic data across various states and districts in India. The primary goal is to uncover insights into transaction trends, user behavior, device usage, and demographic correlations while ensuring data consistency. 

The dataset spans multiple years (2018-2021) and quarters, providing a comprehensive view of transactions, user activity, and demographic patterns. The case study demonstrates Python skills for data loading, preprocessing, exploration, and visualization to generate meaningful insights.

# Dataset Details
State_Txn_and_Users – Contains state-level transaction and user data, including transaction count, total and average transaction value, registered users, and app opens.
State_TxnSplit – Breaks down transactions by type, providing transaction count, total amount, and average value for each type.
State_DeviceData – Lists registered users by device brand at the state level, showing user distribution across different brands.
District_Txn_and_Users – Includes district-level transaction data similar to the state dataset, covering transaction count, values, registered users, and app opens.
District_Demographics – Provides demographic details for each district, including population, area, density, and headquarters.

# Data Dictonaries

# 1. State_Txn_and_Users
State: Name of the state
Year: Year of the data
Quarter: Quarter of the year
Transactions: Number of transactions
Amount (INR): Total amount of transactions in INR
ATV (INR): Average transaction value in INR
Registered Users: Number of registered users
App Opens: Number of app opens

# 2. State_TxnSplit
State: Name of the state
Year: Year of the data
Quarter: Quarter of the year
Transaction Type: Type of transaction (e.g., Recharge & bill payments, Peer-to-peer payments)
Transactions: Number of transactions
Amount (INR): Total amount of transactions in INR
ATV (INR): Average transaction value in INR

# 3. State_DeviceData
State: Name of the state
Year: Year of the data
Quarter: Quarter of the year
Brand: Brand of the device
Registered Users: Number of registered users using the brand
Percentage: Percentage of registered users using the brand

# 4. District_Txn_and_Users
State: Name of the state
Year: Year of the data
Quarter: Quarter of the year
District: Name of the district
Code: District code
Transactions: Number of transactions
Amount (INR): Total amount of transactions in INR
ATV (INR): Average transaction value in INR
Registered Users: Number of registered users
App Opens: Number of app opens

# 5. District Demographics
State: Name of the state
District: Name of the district
Headquarters: District headquarters
Population: Population of the district
Area (sq km): Area of the district in square kilometers
Density: Population density
Code: District code
Alternate Name: Alternate name of the district
