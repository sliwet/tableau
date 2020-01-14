# Tableau Homework - Citi Bike Analytics

## Background

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Analysis

Due to the size of dataset, monthly data were loaded into PostgreSQL before cleaning up. Clean up and grouping has been done through Python and saved into csv files for loading into tableau.

1. Weekday and weekend usage by customers and subscribers are quite different. This can be found in popular start and end station maps.
2. Whether female or male, most active user is in their 30s.
3. Subscriber usage is greater during morning (going to work) and afternoon (coming back home) during weekdays, but has the same pattern as customer usage during weekdays.
4. Most usage occurs during May and September.

### Copyright

Data Boot Camp (C) 2019. All Rights Reserved.
