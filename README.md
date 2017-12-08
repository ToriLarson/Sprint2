### SQLite & SQLite Studio

11/28/2017 - 12/7/2017

**Author:** Victoria Larson


__*Project Description:*__ Exploring the basics of SQLite & SQLiteStudio by importing a simple excel spreadsheet.

I began this project with an excel spreadsheet which, displayed general information about parking stalls in Honolulu. I wanted to be able to filter or manipulate the data using SQLite.

### SQLite3

I started by calling SQLite in the command line to import the parking spot data.
Here is my code:

- sqlite> .mode csv
- sqlite> .import /Users/victorialarson/Desktop/Dev\ League/Repos/Sprint2/City_Public_Parking_Stalls.csv
 "/Users/victorialarson/Desktop/Dev\"
- sqlite> .import Users/victorialarson/Desktop/City_Public_Parking_Stalls.csv city_parking
  - As shown above I named this table "city_parking"
I then ran a schema to see how my table would be constructed  
- sqlite> .schema

Below is the actual code that I wrote:

[SQL_Code](SQLcode.jpeg)

I ran a Query in SQLite3 using the SELECT and FROM functions - I also learned that the ";" is very important in SQLite
My First Query:
[Command Line Query Code](CL_qry.jpeg)

### SQLite Studio

After trying a few queries in SQLite and after some research I downloaded SQLite Studio.

I began by creating a new database. I then created a graph from scratch to upload my table into -  
