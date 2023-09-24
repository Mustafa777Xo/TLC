# TLC (New York City Taxi and Limousine Commission)

## Overview
New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. The agency want to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered. 

## Business Understanding
The New York City Taxi and Limousine Commission (TLC) is tasked with overseeing and regulating a massive transportation network that includes taxi cabs and for-hire vehicles. With over 200,000 licensees and approximately one million combined trips per day, managing and optimizing the fare estimation process is crucial.

The primary objective is to create a regression model capable of accurately estimating taxi fares in advance. This model will not only benefit passengers by providing more transparency in fare calculation but also help drivers and TLC in ensuring fair pricing across the city's extensive transportation network. By harnessing the power of data analysis and machine learning, this project aims to improve the overall taxi and limousine experience in New York City.

## Data Understanding
### DataFrame Shape:
- Number of Rows: 22,699
- Number of Columns: 18

### Column Information:
- Unnamed: 0: An integer column with no null values.
- VendorID: An integer column with no null values.
- tpep_pickup_datetime: A datetime column with no null values.
- tpep_dropoff_datetime: A datetime column with no null values.
- passenger_count: An integer column with no null values.
- trip_distance: A float column with no null values.
- RatecodeID: An integer column with no null values.
- store_and_fwd_flag: An object (string) column with no null values.
- PULocationID: An integer column with no null values.
- DOLocationID: An integer column with no null values.
- payment_type: An integer column with no null values.
- fare_amount: A float column with no null values.
- extra: A float column with no null values.
- mta_tax: A float column with no null values.
- tip_amount: A float column with no null values.
- tolls_amount: A float column with no null values.
- improvement_surcharge: A float column with no null values.
- total_amount: A float column with no null values.

### Data Types:
- There are three data types present in this DataFrame:
- Integer (int64): 7 columns
- Float (float64): 8 columns
- Object (string): 3 columns

## Modeling and Evaluation
...

## Conclusion
...