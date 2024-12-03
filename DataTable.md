# DataTable in ADO.NET - MCQs

1. **What does a DataTable represent in ADO.NET?**  
   a) A collection of columns  
   b) A collection of rows  
   c) A single row of data  
   d) A collection of DataSets  
   **Answer:** b) A collection of rows

2. **Which class is used to represent a table of in-memory data in ADO.NET?**  
   a) DataColumn  
   b) DataRow  
   c) DataTable  
   d) DataAdapter  
   **Answer:** c) DataTable

3. **Which method is used to add a DataRow to a DataTable in ADO.NET?**  
   a) Rows.Add()  
   b) Tables.Add()  
   c) DataTable.AddRow()  
   d) AddRow()  
   **Answer:** a) Rows.Add()

4. **Which property of DataTable holds the collection of rows?**  
   a) Rows  
   b) DataRows  
   c) Columns  
   d) DataSet  
   **Answer:** a) Rows

5. **What type of object is added to a DataTable's Rows collection?**  
   a) DataColumn  
   b) DataRow  
   c) DataSet  
   d) DataView  
   **Answer:** b) DataRow

6. **Which method is used to remove a row from a DataTable?**  
   a) Rows.Remove()  
   b) DataRows.Remove()  
   c) DeleteRow()  
   d) RemoveRow()  
   **Answer:** a) Rows.Remove()

7. **Which method of DataTable is used to accept all changes made to the table?**  
   a) CommitChanges()  
   b) AcceptChanges()  
   c) ConfirmChanges()  
   d) ValidateChanges()  
   **Answer:** b) AcceptChanges()

8. **Which property of DataTable is used to get or set the primary key for the table?**  
   a) PrimaryKey  
   b) Constraints  
   c) DataRows  
   d) DataColumn  
   **Answer:** b) Constraints

9. **Which of the following is true about DataTable in ADO.NET?**  
   a) It can only hold one column of data.  
   b) It holds only a single type of data.  
   c) It contains only read-only data.  
   d) It can store multiple columns and rows of data.  
   **Answer:** d) It can store multiple columns and rows of data.

10. **How do you define a column in a DataTable?**  
    a) By using the DataRow object  
    b) By using the DataColumn object  
    c) By using the DataSet object  
    d) By using the DataView object  
    **Answer:** b) By using the DataColumn object

11. **Which of the following is used to represent a row in a DataTable?**  
    a) DataRow  
    b) DataColumn  
    c) DataSet  
    d) DataAdapter  
    **Answer:** a) DataRow

12. **Which method of DataTable is used to load data into the DataTable from a data reader?**  
    a) Load()  
    b) Fill()  
    c) Import()  
    d) LoadData()  
    **Answer:** a) Load()

13. **How can you modify the values in a DataRow?**  
    a) By directly updating the DataTable  
    b) By modifying the values in the DataRow object  
    c) By using the DataSet's Update() method  
    d) By using DataAdapter's Fill() method  
    **Answer:** b) By modifying the values in the DataRow object

14. **Which of the following methods is used to add a new column to a DataTable?**  
    a) Columns.Add()  
    b) DataTable.AddColumn()  
    c) AddColumn()  
    d) AddNewColumn()  
    **Answer:** a) Columns.Add()

15. **Which property of a DataTable holds the collection of columns?**  
    a) Columns  
    b) Rows  
    c) DataRows  
    d) DataColumnCollection  
    **Answer:** a) Columns

16. **What is the default value for the AutoIncrement property of a DataColumn in a DataTable?**  
    a) True  
    b) False  
    c) Null  
    d) Undefined  
    **Answer:** b) False

17. **Which method is used to remove all rows from a DataTable?**  
    a) Rows.Clear()  
    b) Rows.RemoveAll()  
    c) ClearRows()  
    d) RemoveRows()  
    **Answer:** a) Rows.Clear()

18. **Which event is triggered when a row is added to a DataTable?**  
    a) RowAdding  
    b) RowInserted  
    c) RowChanged  
    d) RowCreated  
    **Answer:** c) RowChanged

19. **Which of the following is true about DataColumn in ADO.NET?**  
    a) It stores the actual data in a DataTable.  
    b) It defines the schema (metadata) of a DataTable.  
    c) It can hold multiple rows of data.  
    d) It is used to filter the data in a DataTable.  
    **Answer:** b) It defines the schema (metadata) of a DataTable.

20. **Which property of DataRow is used to get the value of a specific column in the row?**  
    a) Columns  
    b) Field  
    c) DataColumn  
    d) Value  
    **Answer:** b) Field

21. **Which method can be used to modify the state of a DataRow?**  
    a) AcceptChanges()  
    b) BeginEdit()  
    c) CommitChanges()  
    d) EndEdit()  
    **Answer:** d) EndEdit()

22. **How can you find the index of a row in a DataTable?**  
    a) By using the DataRowIndex() method  
    b) By using the Rows.Find() method  
    c) By using the DataRow’s Index property  
    d) By using the DataTable.Rows.IndexOf() method  
    **Answer:** d) By using the DataTable.Rows.IndexOf() method

23. **Which method is used to update a DataTable in the database?**  
    a) Update()  
    b) Save()  
    c) Insert()  
    d) Commit()  
    **Answer:** a) Update()

24. **Which of the following represents a collection of DataRow objects in a DataTable?**  
    a) DataRowCollection  
    b) DataColumnCollection  
    c) DataSet  
    d) DataRelation  
    **Answer:** a) DataRowCollection

25. **Which of the following is used to define constraints on a DataTable in ADO.NET?**  
    a) DataColumn  
    b) DataRow  
    c) DataSet  
    d) Constraint  
    **Answer:** d) Constraint

26. **Which property of DataTable allows you to define a unique constraint for one or more columns?**  
    a) Columns  
    b) Constraints  
    c) PrimaryKey  
    d) DataRow  
    **Answer:** b) Constraints

27. **Which method of DataTable is used to get a copy of the structure (without data) of the DataTable?**  
    a) Clone()  
    b) Copy()  
    c) GetStructure()  
    d) Export()  
    **Answer:** a) Clone()

28. **What is the purpose of the `TableName` property in DataTable?**  
    a) To define the name of the DataTable in memory  
    b) To define the name of the table in the database  
    c) To hold the column names  
    d) To hold the primary key of the table  
    **Answer:** a) To define the name of the DataTable in memory

29. **Which of the following is true about a DataTable with an empty schema?**  
    a) It will automatically load data from the database.  
    b) It requires explicit column definitions before adding data.  
    c) It can only hold null values.  
    d) It is used for storing data temporarily during database transactions.  
    **Answer:** b) It requires explicit column definitions before adding data.

30. **Which of the following methods allows you to filter rows in a DataTable?**  
    a) DataRow.Select()  
    b) DataTable.Filter()  
    c) DataTable.SelectRows()  
    d) DataRow.Filter()  
    **Answer:** a) DataRow.Select()

31. **How do you ensure that a DataTable column has a unique set of values?**  
    a) Use the Unique property of DataColumn  
    b) Use a DataRelation to enforce uniqueness  
    c) Set the AutoIncrement property of DataColumn  
    d) Define a primary key constraint on the column  
    **Answer:** d) Define a primary key constraint on the column

32. **Which of the following operations cannot be performed on a DataRow?**  
    a) Add a new row  
    b) Delete an existing row  
    c) Modify the value of a row  
    d) Merge rows from another DataTable  
    **Answer:** d) Merge rows from another DataTable

33. **How can you load data from a DataReader into a DataTable?**  
    a) By using the DataTable.Load() method  
    b) By using the DataAdapter.Fill() method  
    c) By using the DataTable.Import() method  
    d) By using the DataReader.Load() method  
    **Answer:** a) By using the DataTable.Load() method

34. **Which of the following is used to add constraints like foreign key and primary key in a DataTable?**  
    a) DataColumn  
    b) DataSet  
    c) DataRelation  
    d) Constraints  
    **Answer:** d) Constraints

35. **Which method is used to retrieve a specific DataRow by its primary key in a DataTable?**  
    a) Rows.Find()  
    b) Rows.GetRow()  
    c) DataRow.Select()  
    d) DataTable.GetRow()  
    **Answer:** a) Rows.Find()
