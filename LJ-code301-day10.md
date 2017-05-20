# Said Abdou Mattar code fellows 301 coding journey..  
Day 9:  
Today I have learned about Data, in the real world Data is often broken down into pieces and stored across multiple orthogonal tables using a process known as normalization.  
Database normalization is useful because it minimizes duplicate data in any single table, and allows for data in the database to grow independently of each other.  
Tables that share information about a single entity need to have a primary key that identifies that entity uniquely across the database. One common primary key type is an auto-incrementing integer (because they are space efficient), but it can also be a string, hashed value, so long as it is unique.  
Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key. The first of the joins that we will introduce is the INNER JOIN.  
The INNER JOIN is a process that matches rows from the first table and the second table which have the same key (as defined by the ON constraint) to create a result row with the combined columns from both tables. After the tables are joined, the other clauses we learned previously are then applied.  
If the two tables have asymmetric data, which can easily happen when data is entered in different stages, then we would have to use a LEFT JOIN, RIGHT JOIN or FULL JOIN instead to ensure that the data we need is not left out of the results.  

Day 10:  
Today I have learned that There are three techniques that we can use to help users to find the content they are looking for:  
1.Filtering: let us, reduce a set of values and create a subset of data that meets certain criteria.  
2.Search.  
3.Sorting.  
An array is a kind of object. All arrays have properties and methods that help when working with a sequence of items in an array, such as.  

The sort() method reorder items in an array.  
The length property counts the number of items in an array.  
Higher-order functions that somehow apply a function to the elements of an array are widely used in JavaScript. The forEach method is the most primitive such function.  

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been “mapped” to a new form by the function.  
