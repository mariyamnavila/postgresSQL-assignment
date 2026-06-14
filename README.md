# Football Ticket Booking Database Assignment

## Project Overview
This repository has a project about a football ticket booking system that uses SQL. The main file is called `QUERY.sql`. This file sets up the database adds some sample data and shows some examples of queries. These query examples show how to get information, from the football ticket booking system.

## Query Examples Included
The `QUERY.sql` file includes example SELECT statements for:

1. Retrieving available Champions League matches.
2. Searching users by name using case-insensitive partial matching.
3. Identifying bookings with missing payment status and labeling them `Action Required`.
4. Joining bookings with users and matches to list full booking details.
5. Using a left join to show all users and their bookings, including users without bookings.
6. Finding bookings whose total cost is higher than the average booking cost.
7. Retrieving top 2 matches ordered by ticket price, skipping the highest one.

## How to Use
1. Open a program that can run SQL commands, like PostgreSQL.
2. Run the `QUERY.sql` script to create the database and add some sample information.
3. Run the example queries at the end of the SQL file to see the results.
