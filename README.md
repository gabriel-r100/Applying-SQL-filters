# Applying-SQL-filters

## Project description
Use various operators in combination to allow us to filter data more efficiently.

## Retrieve after hours failed login attempts
We filter with two conditions: times after 6PM (18:00:00 on database) and failed login attempts. (denoted by 0)
![After-Hours-Login-Attempts](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/e8190796-9cf0-4eb0-8a46-945611a5df78)

## Retrieve login attempts on specific dates
We retrieve login attempts on two dates by using the OR operator to provide data that meets either criteria, in this case May 9th or May 8th 2022. 
![Login-Attempts-Specific-Dates](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/32f9d9ff-9d72-4084-bbda-9b2d2017a4f8)

## Retrieve login attempts outside of Mexico
We retrieve login attempts outside of Mexico by using the LIKE and NOT operators and due to the fact that the database has two entries for Mexico: MEX and MEXICO. The % allows us to retrieve both MEX and MEXICO.
![Login-Attempts-Outside-Mexico](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/36d58706-1238-4d6c-92a2-b224f2941a5c)

## Retrieve employees in Marketing
We are tasked to retrieve employees in marketing that are also in the East offices.
We use the AND operator once more as well as the LIKE operator to show all offices in the East side.
![Marketing-Employees](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/6d9dde06-5a9a-4839-ac8f-92ae26d39960)

## Retrieve employees in Finance or Sales
We retrieve employees that are either in the Finance or Sales department using the OR operator to retrieve data where either condition is met.
![Finance-OR-Sales-Employees](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/ef908cdf-050c-4d10-ab6c-d7d658b4c9b9)

## Retrieve all employees not in IT
We are also able to retrieve information for employees excluding the IT department by utilizing the NOT command once more.
![Non-IT-Employees](https://github.com/gabriel-r100/Applying-SQL-filters/assets/55646808/cd0463ba-e5c6-41c3-b09e-9a54785fed53)

## Summary
We were able to filter out information from two databases based on different conditions we would like to meet. The ability to use operators in conjunction allows us to be a lot more specific in the data we are trying to retrieve. 

