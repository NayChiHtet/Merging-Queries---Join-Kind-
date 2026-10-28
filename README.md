# Merging-Queries-Join-Kind
Merging Queries - Join Kind Theory

# Power Query Basics: Merge Queries and the Differences of Join Types
Now we will go into the different types of join functions Power Query has made available to us.

**Inner Join**
- Only matching rows from both tables
- The table resulting from an inner join contains a row for each pair of rows from the specified tables that were determined to match based on the specified key columns.

**Full Outer Join**
- All rows from Both tables
- A full outer join ensures that all rows of both tables appear in the result. Rows that did not have a match in the other table are joined with a default row containing null values for all of its columns.

**Left Outer Join**
- All from first, matching from second
- All rows from the left table, matching rows from the right table
- A left outer join ensures that all rows of the first table appear in the result.

**Left Anti Join** 
- Rows only in First
- Only rows from the left table
- A left anti join returns all rows from the first table that do not have a match in the second table.

**Right Outer Join**
- All rows from the right table, matching rows from the left table
- All from second, matching from first
- A right outer join ensures that all rows of the second table appear in the result.

**Right Anti Join** 
- Only rows from the right table
- Rows only in second
- A right anti join returns all rows from the second table that do not have a match in the first table.

# Conclusion
Joins are powerful functions used in data analytics every day. The concept behind the different join types in Power Query are similar to SQL based join functions and are incredibly powerful tools. Understanding the differences opens many possibilities for manipulating tables to suit your needs.

# References 

https://learn.microsoft.com/en-us/powerquery-m/joinkind-type

https://iterationinsights.com/article/power-query-basics-merge-queries-and-the-differences-of-join-types/

https://learn.microsoft.com/en-us/power-query/merge-queries-overview
