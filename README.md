Business Case: OLA - Ensemble Learning

Problem Statement:
Recruiting and retaining drivers is seen by industry watchers as a tough battle for Ola. Churn among drivers is high and it’s very easy for drivers to stop working for the service on the fly or jump to Uber depending on the rates.
As the companies get bigger, the high churn could become a bigger problem. To find new drivers, Ola is casting a wide net, including people who don’t have cars for jobs. But this acquisition is really costly. Losing drivers frequently impacts the morale of the organization and acquiring new drivers is more expensive than retaining existing ones.
You are working as a data scientist with the Analytics Department of Ola, focused on driver team attrition. You are provided with the monthly information for a segment of drivers for 2019 and 2020 and tasked to predict whether a driver will be leaving the company or not based on their attributes like
•	Demographics (city, age, gender etc.)
•	Tenure information (joining date, Last Date)
•	Historical data regarding the performance of the driver (Quarterly rating, Monthly business acquired, grade, Income)

Dataset:
ola_driver.csv

Column Profiling:
1.	MMMM-YY : Reporting Date (Monthly)
2.	Driver_ID : Unique id for drivers
3.	Age : Age of the driver
4.	Gender : Gender of the driver – Male : 0, Female: 1
5.	City : City Code of the driver
6.	Education_Level : Education level – 0 for 10+ ,1 for 12+ ,2 for graduate
7.	Income : Monthly average Income of the driver
8.	Date Of Joining : Joining date for the driver
9.	LastWorkingDate : Last date of working for the driver
10.	Joining Designation : Designation of the driver at the time of joining
11.	Grade : Grade of the driver at the time of reporting
12.	Total Business Value : The total business value acquired by the driver in a month (negative business indicates cancellation/refund or car EMI adjustments)
13.	Quarterly Rating : Quarterly rating of the driver: 1,2,3,4,5 (higher is better)
