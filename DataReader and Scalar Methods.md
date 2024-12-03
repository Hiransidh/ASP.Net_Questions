# DataReader and Scalar Methods in ADO.NET - MCQs

## DataReader

1. **Which ADO.NET object is used to retrieve data in a forward-only, read-only manner?**  
   a) DataSet  
   b) DataAdapter  
   c) DataReader  
   d) DataTable  
   **Answer:** c) DataReader

2. **Which class is used to retrieve data from SQL Server in ADO.NET?**  
   a) SqlDataReader  
   b) SqlConnection  
   c) SqlCommand  
   d) SqlAdapter  
   **Answer:** a) SqlDataReader

3. **What is the main feature of the DataReader in ADO.NET?**  
   a) It supports both forward and backward navigation of data  
   b) It stores data in memory  
   c) It provides a way to work with data in a disconnected mode  
   d) It retrieves data in a forward-only, read-only manner  
   **Answer:** d) It retrieves data in a forward-only, read-only manner

4. **Which method of DataReader is used to fetch the next row of data?**  
   a) Read()  
   b) Next()  
   c) Fetch()  
   d) MoveNext()  
   **Answer:** a) Read()

5. **What does the `IsDBNull()` method of DataReader do?**  
   a) It checks if a DataReader is empty  
   b) It checks if a column value is null in the current row  
   c) It checks if the connection is open  
   d) It validates the data type of the column  
   **Answer:** b) It checks if a column value is null in the current row

6. **Which method is used to close a DataReader in ADO.NET?**  
   a) Close()  
   b) Dispose()  
   c) End()  
   d) Stop()  
   **Answer:** a) Close()

7. **What will happen if you try to use a DataReader after closing it?**  
   a) It will throw an exception  
   b) It will return null  
   c) It will continue to read the data  
   d) It will reset the DataReader to the first row  
   **Answer:** a) It will throw an exception

8. **Which method is used to retrieve the value of a column in the current row of DataReader by column name?**  
   a) GetValue()  
   b) GetColumn()  
   c) GetString()  
   d) GetOrdinal()  
   **Answer:** a) GetValue()

9. **Which DataReader method is used to get the value of a column by column index?**  
   a) GetValue()  
   b) GetData()  
   c) GetInt32()  
   d) GetByte()  
   **Answer:** a) GetValue()

10. **What does the `NextResult()` method of DataReader do?**  
    a) Moves to the next row of the result set  
    b) Moves to the next result set in the batch query  
    c) Moves to the next column of the result set  
    d) Moves to the next record of the database  
    **Answer:** b) Moves to the next result set in the batch query

11. **Which of the following is a limitation of DataReader in ADO.NET?**  
    a) It cannot handle multiple result sets  
    b) It cannot work with large data sets  
    c) It requires a persistent connection to the database  
    d) It is used for disconnected operations  
    **Answer:** c) It requires a persistent connection to the database

12. **Which method would you use to get the string value from the first column of the current row in DataReader?**  
    a) GetString()  
    b) GetData()  
    c) GetValue()  
    d) GetColumnData()  
    **Answer:** a) GetString()

13. **Which class in ADO.NET provides the method `ExecuteReader()` to return a DataReader object?**  
    a) SqlConnection  
    b) SqlDataReader  
    c) SqlCommand  
    d) SqlAdapter  
    **Answer:** c) SqlCommand

14. **What is the primary advantage of using a DataReader over a DataSet?**  
    a) DataReader is faster and more memory-efficient for reading large datasets  
    b) DataReader can work in a disconnected mode  
    c) DataReader supports multiple result sets  
    d) DataReader supports data modification  
    **Answer:** a) DataReader is faster and more memory-efficient for reading large datasets

---

## Scalar Methods

15. **Which ADO.NET method is used to execute a query that returns a single value?**  
    a) ExecuteNonQuery()  
    b) ExecuteScalar()  
    c) ExecuteReader()  
    d) ExecuteQuery()  
    **Answer:** b) ExecuteScalar()

16. **What type of value does `ExecuteScalar()` return?**  
    a) A single row  
    b) A DataSet  
    c) A single value  
    d) A DataTable  
    **Answer:** c) A single value

17. **What does the `ExecuteScalar()` method return if the result of the query is null?**  
    a) 0  
    b) DBNull  
    c) Empty string  
    d) Null  
    **Answer:** d) Null

18. **Which of the following is true about the `ExecuteScalar()` method in ADO.NET?**  
    a) It is used for executing SQL commands that return multiple rows  
    b) It returns the first column of the first row in the result set  
    c) It returns a DataReader object  
    d) It can execute insert, update, and delete commands  
    **Answer:** b) It returns the first column of the first row in the result set

19. **In which scenario would you use the `ExecuteScalar()` method?**  
    a) When you want to execute a query and get a single value, such as a count or sum  
    b) When you need to retrieve all rows of a table  
    c) When you need to update the database  
    d) When you need to perform a stored procedure  
    **Answer:** a) When you want to execute a query and get a single value, such as a count or sum

20. **Which of the following is a common use case for the `ExecuteScalar()` method?**  
    a) Retrieving a total count of records in a table  
    b) Retrieving all columns for a specific row  
    c) Executing a query that returns multiple rows  
    d) Fetching multiple rows from different tables  
    **Answer:** a) Retrieving a total count of records in a table

21. **Which of the following is a disadvantage of `ExecuteScalar()`?**  
    a) It can only return a single value from a query  
    b) It cannot be used with SQL statements  
    c) It requires a large amount of memory  
    d) It cannot be used for retrieving values of multiple columns  
    **Answer:** a) It can only return a single value from a query

22. **Which of the following methods is most appropriate for performing aggregate functions like COUNT, SUM, AVG in SQL queries?**  
    a) ExecuteReader()  
    b) ExecuteNonQuery()  
    c) ExecuteScalar()  
    d) ExecuteXmlReader()  
    **Answer:** c) ExecuteScalar()

23. **Which of the following is true about `ExecuteScalar()`?**  
    a) It executes a query and returns a DataTable  
    b) It is used for executing queries that return a single value  
    c) It cannot be used with SELECT queries  
    d) It is used for executing non-query SQL commands  
    **Answer:** b) It is used for executing queries that return a single value

24. **Which of the following is a suitable use case for `ExecuteScalar()`?**  
    a) Counting the number of rows in a table  
    b) Retrieving all the rows from a table  
    c) Fetching data for multiple columns  
    d) Inserting new data into a table  
    **Answer:** a) Counting the number of rows in a table

25. **Which ADO.NET object provides the `ExecuteScalar()` method?**  
    a) SqlDataReader  
    b) SqlCommand  
    c) SqlConnection  
    d) SqlDataAdapter  
    **Answer:** b) SqlCommand

26. **How does `ExecuteScalar()` handle queries that return more than one value?**  
    a) It throws an exception  
    b) It returns the first value of the first column  
    c) It returns all values in a list  
    d) It returns the last value of the result set  
    **Answer:** b) It returns the first value of the first column

27. **Which method would you use to get the number of rows affected by an SQL query?**  
    a) ExecuteScalar()  
    b) ExecuteNonQuery()  
    c) ExecuteReader()  
    d) ExecuteQuery()  
    **Answer:** b) ExecuteNonQuery()

28. **What will the `ExecuteScalar()` method return when the query result is a large dataset?**  
    a) A DataReader object  
    b) The first column of the first row  
    c) A DataTable  
    d) A single integer value  
    **Answer:** b) The first column of the first row

29. **Which SQL command is typically executed using `ExecuteScalar()`?**  
    a) SELECT COUNT(*)  
    b) SELECT * FROM Employees  
    c) INSERT INTO Users VALUES ('A')  
    d) UPDATE Employees SET Salary = 1000  
    **Answer:** a) SELECT COUNT(*)

30. **Can `ExecuteScalar()` be used to execute an INSERT statement?**  
    a) Yes, if you want to return the inserted value  
    b) No, it can only be used for SELECT statements  
    c) Yes, for queries returning rows  
    d) No, it only works with SELECT queries returning a single value  
    **Answer:** a) Yes, if you want to return the inserted value
