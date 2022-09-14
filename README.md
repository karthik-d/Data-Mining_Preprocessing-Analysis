# NYC-Taxi-Trip-Data-Analysis-Cleaning

Analysis, clearning, and transformation of the NYC Taxi Trip data (2018) as part of coursework for UCS1629 - Data Warehousing and Data Mining.

- [Python Notebook for Analysis](./Analysis-Cleaning-Transformation_Code.ipynb)
- [Sumary Report on the Analysis](./Analysis-Cleaning-Transformation_Report.pdf)

## Dataset

This data set is a subset of the Google BigQuery public datasets - Nyc yellow taxi cab trips data
set containing a random 10,000,000 rows of data. This dataset was extracted and uploaded for the
purpose of experimenting with and learning regression models for price prediction. There is also a
lot of room for data cleaning, outliers in the data, and plenty of data to work with for more realistic
model training, testing, and validation.


The analyzed subset of the data is publicly accessible through [Kaggle](https://www.kaggle.com/datasets/neilclack/nyc-taxi-trip-data-google-public-data).

### Data Attributes
| column            | type     | nullable | description                                                                                                                                                                                                                                          |
| ----------------- | -------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| vendor\_id        | text     | required | A code indicating the TPEP provider that provided the record. 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc                                                                                                                                  |
| pickup\_datetime  | datetime | nullable | The date and time when the meter was engaged.                                                                                                                                                                                                        |
| dropoff\_datetime | datetime | nullable | The date and time when the meter was disengaged.                                                                                                                                                                                                     |
| passenger\_count  | integer  | nullable | The number of passengers in the vehicle. This is a driver-entered value                                                                                                                                                                              |
| trip\_distance    | numeric  | nullable | The elapsed trip distance in miles reported by the taximeter.                                                                                                                                                                                        |
| rate\_code        | string   | nullable | The final rate code in effect at the end of the trip. 1= Standard rate 2=JFK 3=Newark 4=Nassau or Westchester 5=Negotiated fare 6=Group ride                                                                                                         |
| storeandfwd\_flag | string   | nullable | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server. Y= store and forward trip N= not a store and forward trip |
| payment\_type     | string   | nullable | A numeric code signifying how the passenger paid for the trip. 1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided trip                                                                                                              |
| fare\_amount      | numeric  | nullable | The time-and-distance fare calculated by the meter                                                                                                                                                                                                   |
| extra             | numeric  | nullable | Miscellaneous extras and surcharges. Currently, this only includes the \\$0.50 and \\$1 rush hour and overnight charges.                                                                                                                             |
| mta\_tax          | numeric  | nullable | \\$0.50 MTA tax that is automatically triggered based on the metered rate in use                                                                                                                                                                     |
| tip\_amount       | numeric  | nullable | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included                                                                                                                                                  |
| tolls\_amount     | numeric  | nullable | Total amount of all tolls paid in the trip.                                                                                                                                                                                                          |
| imp\_surcharge    | numeric  | nullable | \\$0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.                                                                                                                                 |
| total\_amount     | numeric  | nullable | The total amount charged to passengers. Does not include cash tips                                                                                                                                                                                   |
| pickuplocationid  | string   | nullable | TLC Taxi Zone in which the taximeter was engaged                                                                                                                                                                                                     |
| dropofflocationid | string   | nullable | TLC Taxi Zone in which the taximeter was disengaged                                                                                                                                                                                                  |


## Basic Analysis Steps

-


## Data Cleaning Steps

-


## Data Transformation Steps

- 

