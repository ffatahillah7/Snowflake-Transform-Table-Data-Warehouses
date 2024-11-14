# Snowflake-Transform-Table-Data-Warehouses
Welcome to the Powered by Tasty Bytes - Zero to Snowflake Quickstart focused on Transformation!  Within this Quickstart we will walk through a large set of Snowflake functionality covering key features like Zero Copy Cloning and Time-Travel to deliver on a Tasty Bytes business requirement.

# Prerequisites
Before beginning, please make sure you have completed the Introduction to Tasty Bytes Quickstart which provides a walkthrough on setting up a trial account and deploying the Tasty Bytes Foundation required to complete this Quickstart.
link quickstart : https://quickstarts.snowflake.com/guide/tasty_bytes_zero_to_snowflake_transformation/index.html?index=..%2F..index#0

# What You Will Learn
1.  How to Clone a Table
2.  How to Use Snowflake's Result Set Cache
3.  How to Add a Column to a Table
4.  How to Update Data in a Column
5.  How to Use Time-Travel
6.  How to Swap, Drop and Undrop a Table
   
# What You Will Build
1.  An Understanding of Important Snowflake Transformation Functionality
2.  A Development Table Clone of a Production Table
3.  A New Column in a Table Complete with Calculated Food Truck Ages in Years

# Lesson Result
1.   Cloning one table to another table using Clone function. For example, clone table truck_food to truck_food_dev.
2.   Update the Table with alter table, add or drop column. Add new column with concat query from another column. It's convenient way to merge or combine more than one column.
3.   It's Convenient for rollback from a mistake on the Update statement earlier (update or delete). The way is check query_id from information schema. Replace the table with previous data using query replace before statement query_id.
4.   Table swap , drop and undrop table if we made a drop mistake.

