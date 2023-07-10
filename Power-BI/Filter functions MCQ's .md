![](Aspose.Words.3d93deb1-52c9-409a-b5d7-029528f463fb.001.png)

1\. **ALL**:

`   `a) What is the purpose of the ALL function in Power Query?

`      `i) Returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) Applies a specific filter to a column, limiting the rows returned.

`      `iii) Retrieves distinct values from a column, ignoring any filters.

`      `iv) Calculates a cumulative total for a column, considering all rows.

`   `b) How does the ALL function differ from the ALLSELECTED function?

`      `i) ALL returns all rows in a table, while ALLSELECTED retains other context filters or explicit filters.

`      `ii) ALL removes all context filters, while ALLSELECTED retains column and row filters.

`      `iii) ALL returns distinct values, while ALLSELECTED returns all values with applied filters.

`      `iv) ALL removes all filters from a column, while ALLSELECTED keeps existing filters.

`   `c) Which function can be used to remove all filters except for specific columns in Power Query?

`      `i) REMOVEFILTERS

`      `ii) ALLEXCEPT

`      `iii) CALCULATE

`      `iv) INDEX

d) What is the data type returned by the ALL function?

`      `i) Text

`      `ii) Number

`      `iii) Table

`      `iv) Boolean

`   `e) How can the ALL function be useful in data analysis or transformations?

`      `i) It allows for performing calculations without considering any filters or applied context.

`      `ii) It helps in identifying outliers or anomalies by examining all data points.

`      `iii) It supports creating new measures or calculations based on the complete dataset.

`      `iv) It enables comparisons between filtered and unfiltered data for insights.

2\. **CALCULATE**:

`   `a) What is the purpose of the CALCULATE function in Power Query?

`      `i) It evaluates an expression in a modified filter context.

`      `ii) It calculates the average of numeric values in a column.

`      `iii) It returns all rows in a table, ignoring any filters.

`      `iv) It applies a specific filter to a column, limiting the rows returned.

` `b) How does the CALCULATE function modify the filter context?

`      `i) It clears all filters on a column before applying the specified expression.

`      `ii) It adds additional filters to the existing filter context based on the specified expression.

`      `iii) It removes all filters from the current filter context and applies only the specified expression.

`      `iv) It replaces the existing filter context with a new filter context defined by the specified expression.

` `c) Which function can be used in combination with CALCULATE to perform complex calculations involving multiple tables?

`      `i) FILTER

`      `ii) CALCULATETABLE

`      `iii) EARLIER

`      `iv) LOOKUPVALUE

` `d) What is the syntax for using the CALCULATE function?

`      `i) CALCULATE(expression, table, filter)

`      `ii) CALCULATE(expression, filter)

`      `iii) CALCULATE(table, filter, expression)

`      `iv) CALCULATE(filter, expression, table)

`   `e) How can the CALCULATE function be useful in data analysis or transformations?

`      `i) It allows for applying dynamic filters or conditions to calculations based on specific criteria.

`     `ii) It supports creating custom measures or aggregations based on modified filter contexts.

`      `iii) It enables comparing calculations or metrics with different filter configurations.

`      `iv) It helps in performing complex calculations involving multiple tables and relationships.

3\. **FILTER**:

`   `a) What is the purpose of the FILTER function in Power Query?

`      `i) It returns a table that represents a subset of another table or expression based on specified conditions.

`      `ii) It calculates the average of numeric values in a column.

`      `iii) It removes all filters from the specified tables or columns.

`      `iv) It retrieves distinct values from a column, ignoring any filters.

`   `b) How does the FILTER function determine which rows to include in the resulting table?

`      `i) It includes all rows from the original table.

`      `ii) It includes only the rows that meet the specified conditions.

`      `iii) It includes a random selection of rows from the original table.

`      `iv) It includes the first and last rows from the original table.

`   `c) Which function can be used in combination with FILTER to perform calculations over the filtered subset of data?

`      `i) CALCULATE

`      `ii) INDEX

`      `iii) ROWNUMBER

`      `iv) EARLIER

`   `d) What is the syntax for using the FILTER function?

`      `i) FILTER(table, condition)

`      `ii) FILTER(condition, table)

`      `iii) FILTER(expression, table, condition)

`      `iv) FILTER(table, condition, expression)

`   `e) How can the FILTER function be useful in data analysis or transformations?

`      `i) It allows for extracting specific subsets of data based on user-defined conditions.

`      `ii) It facilitates creating filtered views or temporary tables for further analysis.

`      `iii) It helps in applying dynamic filters to tables or expressions during calculations.

`      `iv) It supports data cleaning by removing undesired rows based on specified criteria.

4\. **INDEX**:

`   `a) What is the purpose of the INDEX function in Power Query?

`      `i) It returns a table that represents a subset of another table or expression based on specified conditions.

`      `ii) It calculates the average of numeric values in a column.

`      `iii) It returns a row at an absolute position within a table, sorted by a specified order or axis.

`      `iv) It removes all filters from the specified tables or columns.

`   `b) How does the INDEX function determine which row to return?

`      `i) It returns the first row from the table.

`      `ii) It returns the last row from the table.

`      `iii) It returns a row based on an absolute position specified by the position parameter.

`      `iv) It returns a row based on a relative position within the table.

` `c) Which function can be used in combination with INDEX to define the sort order within each partition of a WINDOW function?

`      `i) ORDERBY

`      `ii) RANK

`      `iii) OFFSET

`      `iv) PARTITIONBY

` `d) What is the syntax for using the INDEX function?

`      `i) INDEX(table, position)

`      `ii) INDEX(position, table)

`      `iii) INDEX(table, position, sort\_order)

`      `iv) INDEX(position, table, sort\_order)

`   `e) How can the INDEX function be useful in data analysis or transformations?

`      `i) It allows for retrieving specific rows or observations from a table based on their position.

`      `ii) It supports sorting data within partitions for ranking or ranking-related calculations.

`      `iii) It helps in selecting a specific row for further analysis or processing.

`      `iv) It facilitates creating custom tables by combining rows from different sources.

5\. **EARLIER**:

`   `a) What is the purpose of the EARLIER function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It calculates the average of numeric values in a column.

`      `iii) It returns the current value of the specified column in an outer evaluation pass.

`      `iv) It removes all filters from the specified tables or columns.

` `b) How does the EARLIER function differ from the EARLIEST function?

`      `i) EARLIER returns the current value of a column in an outer evaluation pass, while EARLIEST returns the earliest value.

`      `ii) EARLIER operates within the same table, while EARLIEST can access values from different tables.

`      `iii) EARLIER retrieves the first row in a table, while EARLIEST retrieves the earliest row based on a specified column.

`      `iv) EARLIER can be used in calculated columns, while EARLIEST is used in measures or aggregations.

`  `c) Which function can be used in combination with EARLIER to perform complex calculations involving multiple tables?

`      `i) CALCULATE

`      `ii) LOOKUPVALUE

`      `iii) FILTER

`      `iv) WINDOW

d) What is the syntax for using the EARLIER function?

`      `i) EARLIER(column)

`      `ii) EARLIER(table, column)

`      `iii) EARLIER(expression)

`      `iv) EARLIER(expression, table)


e) How can the EARLIER function be useful in data analysis or transformations?

`      `i) It allows for referring to a previous value of a column during calculations or comparisons.

`      `ii) It supports creating running totals or cumulative calculations based on a specific order or condition.

iii) It helps in identifying changes or trends in data by comparing current and previous values.

`      `iv) It facilitates custom calculations that require accessing values from an outer evaluation pass.

6\. **REMOVEFILTERS**:

`   `a) What is the purpose of the REMOVEFILTERS function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iii) It calculates the average of numeric values in a column after removing any applied filters.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the REMOVEFILTERS function affect the filter context of a table?

`      `i) It retains all existing filters and only removes the current filter.

`      `ii) It removes all filters from the specified tables or columns.

`      `iii) It adds additional filters to the table based on specified conditions.

`      `iv) It resets the filter context of the table, removing all filters and selections.

`   `c) Which function can be used in combination with REMOVEFILTERS to modify how filters are applied during calculations?

`      `i) CALCULATE

`      `ii) KEEPFILTERS

`      `iii) FILTER

`      `iv) INDEX

`   `d) What is the syntax for using the REMOVEFILTERS function?

`      `i) REMOVEFILTERS(table)

`      `ii) REMOVEFILTERS(column)

`      `iii) REMOVEFILTERS(expression)

`      `iv) REMOVEFILTERS()

`   `e) How can the REMOVEFILTERS function be useful in data analysis or transformations?

`      `i) It allows for working with unfiltered data, disregarding any applied filters.

`      `ii) It helps in isolating specific tables or columns for analysis without interference from filters.

`      `iii) It supports creating custom views or subsets of data by selectively removing filters.

`      `iv) It facilitates troubleshooting and debugging by starting with a clean filter context.

7\. **ALLSELECTED**:

`   `a) What is the purpose of the ALLSELECTED function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It clears all context filters in the table, providing a clean slate for further analysis.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It removes context filters from columns and rows, while retaining other context filters or explicit filters.

`   `b) How does the ALLSELECTED function differ from the ALL function?

`      `i) ALLSELECTED clears all context filters, while ALL returns all rows in a table regardless of filters.

`      `ii) ALLSELECTED retains the current filter context, while ALL removes all filters from the specified tables or columns.

`      `iii) ALLSELECTED applies additional filters to the table based on specified conditions, while ALL clears all filters.

`      `iv) ALLSELECTED removes filters from specific columns and rows, while ALL applies filters to all columns.

`   `c) Which function can be used in combination with ALLSELECTED to perform calculations over a modified filter context?

`      `i) CALCULATE

`      `ii) LOOKUPVALUE

`      `iii) REMOVEFILTERS

`      `iv) EARLIER

`   `d) What is the syntax for using the ALLSELECTED function?

`      `i) ALLSELECTED(table)

`      `ii) ALLSELECTED(column)

`      `iii) ALLSELECTED(expression)

`      `iv) ALLSELECTED()

`   `e) How can the ALLSELECTED function be useful in data analysis or transformations?

`      `i) It allows for performing calculations or aggregations within the current filter context.

`      `ii) It supports creating dynamic reports or visualizations that adjust based on user-selected filters.

`      `iii) It helps in comparing values across different filter selections or scenarios.

`      `iv) It facilitates creating advanced measures that respond to specific filter configurations.

8\. **CALCULATETABLE**:

`   `a) What is the purpose of the CALCULATETABLE function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It evaluates a table expression in a modified filter context.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the CALCULATETABLE function differ from the CALCULATE function?

`      `i) CALCULATETABLE evaluates table expressions, while CALCULATE performs calculations on scalar values.

`      `ii) CALCULATETABLE modifies the filter context for tables, while CALCULATE modifies the filter context for expressions.

`      `iii) CALCULATETABLE applies additional filters to the table, while CALCULATE removes filters from the specified tables or columns.

`      `iv) CALCULATETABLE performs row-level calculations, while CALCULATE performs column-level calculations.

`   `c) Which function can be used in combination with CALCULATETABLE to modify how filters are applied during calculations?

`      `i) KEEPFILTERS

`      `ii) FILTER

`      `iii) INDEX

`      `iv) REMOVEFILTERS

`   `d) What is the syntax for using the CALCULATETABLE function?

`      `i) CALCULATETABLE(table, filter\_expression)

`      `ii) CALCULATETABLE(expression, filter\_expression)

`      `iii) CALCULATETABLE(column, filter\_expression)

`      `iv) CALCULATETABLE(filter\_expression)

`   `e) How can the CALCULATETABLE function be useful in data analysis or transformations?

`      `i) It allows for creating dynamic tables based on specific filter conditions or expressions.

`      `ii) It supports applying additional filters to tables while evaluating expressions or calculations.

`      `iii) It helps in isolating subsets of data for further analysis or visualization.

`      `iv) It facilitates creating custom views or reports by modifying the filter context for tables.

9\. **INDEX**:

`   `a) What is the purpose of the INDEX function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It retrieves a row at an absolute position within a table, based on specified criteria.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the INDEX function determine the position of the row to retrieve?

`      `i) It uses the row number as the position indicator.

`      `ii) It uses the values in specified columns to identify the position.

`      `iii) It uses a combination of row number and column values to determine the position.

`      `iv) It retrieves the row based on the order specified by the ORDERBY function.

`   `c) Which function can be used in combination with INDEX to define the columns that determine the sort order within each partition?

`      `i) ORDERBY

`      `ii) FILTER

`      `iii) LOOKUPVALUE

`      `iv) CALCULATE

`   `d) What is the syntax for using the INDEX function?

`      `i) INDEX(table, position)

`      `ii) INDEX(table, row\_expression)

`      `iii) INDEX(table, column\_expression)

`      `iv) INDEX(table)

`   `e) How can the INDEX function be useful in data analysis or transformations?

`      `i) It allows for retrieving specific rows from a table based on their position or criteria.

`      `ii) It supports creating dynamic calculations or aggregations based on row-level data.

`      `iii) It helps in creating custom sorting or ranking algorithms within tables.

`      `iv) It facilitates working with large datasets by efficiently retrieving specific rows.




10\. **LOOKUPVALUE**:

`    `a) What is the purpose of the LOOKUPVALUE function in Power Query?

`       `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`       `ii) It retrieves the value for a specified column based on search conditions.

`       `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`       `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`    `b) How does the LOOKUPVALUE function determine the value to retrieve?

`       `i) It uses a combination of search conditions specified by multiple columns.

`       `ii) It uses the values in a single column to identify the value to retrieve.

`       `iii) It uses the row number as the position indicator for the value.

`       `iv) It retrieves the value based on the order specified by the ORDERBY function.

`    `c) Which function can be used in combination with LOOKUPVALUE to define multiple search conditions?

`       `i) CALCULATE

`       `ii) FILTER

`       `iii) REMOVEFILTERS

`       `iv) EARLIER

` `d) What is the syntax for using the LOOKUPVALUE function?

`       `i) LOOKUPVALUE(table, result\_column, search\_expression)

`       `ii) LOOKUPVALUE(table, search\_column, search\_expression, result\_column)

`       `iii) LOOKUPVALUE(result\_column, table, search\_expression)

`       `iv) LOOKUPVALUE(table, result\_column, search\_expression, search\_column)

`    `e) How can the LOOKUPVALUE function be useful in data analysis or transformations?

`       `i) It allows for retrieving specific values from a table based on search conditions.

`       `ii) It supports creating dynamic calculations or aggregations based on specific criteria.

`       `iii) It helps in creating relationships or linking data between tables based on matching values.

`       `iv) It facilitates data validation or error checking by comparing values across tables.

11\. **PARTITIONBY**:

`   `a) What is the purpose of the PARTITIONBY function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It defines the columns that are used to determine the sort order within each partition in a WINDOW function.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the PARTITIONBY function affect the evaluation of a WINDOW function?

`      `i) It divides the data into groups or partitions based on the specified columns.

`      `ii) It reorders the rows in a table based on the specified columns.

`      `iii) It removes duplicate values from the specified columns in a table.

`      `iv) It applies a filter to restrict the data within each partition.

`   `c) Which function can be used in combination with PARTITIONBY to define the columns used for partitioning in a WINDOW function?

`      `i) FILTER

`      `ii) INDEX

`      `iii) RANK

`      `iv) CALCULATE

`   `d) What is the syntax for using the PARTITIONBY function?

`      `i) PARTITIONBY(expression, partition\_columns)

`      `ii) PARTITIONBY(partition\_columns, expression)

`      `iii) PARTITIONBY(expression)

`      `iv) PARTITIONBY(partition\_columns)

`   `e) How can the PARTITIONBY function be useful in data analysis or transformations?

`      `i) It enables performing calculations or aggregations within specific groups or partitions of data.

`      `ii) It assists in identifying and analyzing patterns or trends within each partition.

`      `iii) It helps in comparing the values within each partition to make relative evaluations.

`      `iv) It facilitates creating custom grouping or segmentations based on specific columns.

12\. **RANK**:

`   `a) What is the purpose of the RANK function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It calculates the ranking of a row within the given interval based on specified criteria.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the RANK function determine the ranking of a row?

`      `i) It uses a combination of sorting and partitioning to assign the rank.

`      `ii) It assigns the rank based on the row number within a specified partition.

`      `iii) It assigns the rank based on the values in a specified column.

`      `iv) It assigns the rank based on the order specified by the ORDERBY function.

`   `c) Which function can be used in combination with RANK to define the columns that determine the sort order within each partition?

`      `i) CALCULATE

`      `ii) FILTER

`      `iii) PARTITIONBY

`      `iv) ORDERBY

`   `d) What is the syntax for using the RANK function?

`      `i) RANK(expression, rank\_order)

`      `ii) RANK(expression, partition\_columns, rank\_order)

`      `iii) RANK(rank\_order, expression)

`      `iv) RANK(rank\_order)


`   `e) How can the RANK function be useful in data analysis or transformations?

`      `i) It helps in identifying top or bottom performers based on a specific criterion.

`      `ii) It supports creating custom sorting or ranking algorithms within tables.

`      `iii) It facilitates creating percentile calculations or segmentations based on ranking.

`      `iv) It assists in identifying and analyzing outliers or anomalies within data.

13\. **REMOVEFILTERS**:

`   `a) What is the purpose of the REMOVEFILTERS function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iii) It clears all context filters in the table, providing a clean slate for further analysis.

`      `iv) It calculates the unique ranking of a row within the given interval.

`   `b) How does the REMOVEFILTERS function affect the evaluation of a query?

`      `i) It removes all filters applied to the specified tables or columns, including slicers and visual filters.

`      `ii) It applies additional filters to the specified tables or columns, narrowing down the data set.

`      `iii) It modifies the context in which calculations and transformations are performed.

`      `iv) It returns a new table with only the filtered rows based on the specified conditions.

`   `c) Which function can be used in combination with REMOVEFILTERS to selectively keep specific filters while removing others?

`      `i) FILTER

`      `ii) CALCULATE

`      `iii) ALL

`      `iv) INDEX

`   `d) What is the syntax for using the REMOVEFILTERS function?

`      `i) REMOVEFILTERS()

`      `ii) REMOVEFILTERS(table)

`      `iii) REMOVEFILTERS(column)

`      `iv) REMOVEFILTERS(table, column)

`   `e) How can the REMOVEFILTERS function be useful in data analysis or transformations?

`      `i) It allows for a clean analysis by removing all context filters and starting fresh.

`      `ii) It enables the removal of specific filters while retaining others for targeted analysis.

`      `iii) It supports the creation of complex filter logic by selectively applying and removing filters.

`      `iv) It helps in troubleshooting data-related issues by isolating the effects of filters.

14\. **ROWNUMBER**:

`   `a) What is the purpose of the ROWNUMBER function in Power Query?

`      `i) It returns the unique ranking of a row within the given interval.

`      `ii) It calculates the sum of values in a column or table.

`      `iii) It removes filters from the specified tables or columns, allowing for unrestricted data retrieval.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the ROWNUMBER function assign a unique ranking to each row?

`      `i) It assigns a sequential number to each row based on the order specified by the ORDERBY function.

`      `ii) It assigns a random number to each row, ensuring uniqueness within the given interval.

`      `iii) It assigns the rank based on the values in a specified column.

`      `iv) It assigns the rank based on the row number within a specified partition.

`   `c) Which function can be used in combination with ROWNUMBER to define the columns used to partition the data before assigning row numbers?

`      `i) CALCULATE

`      `ii) FILTER

`      `iii) PARTITIONBY

`      `iv) ORDERBY

`   `d) What is the syntax for using the ROWNUMBER function?

`      `i) ROWNUMBER()

`      `ii) ROWNUMBER(partition\_columns)

`      `iii) ROWNUMBER(expression, partition\_columns, order\_by)

`      `iv) ROWNUMBER(order\_by)

`   `e) How can the ROWNUMBER function be useful in data analysis or transformations?

`      `i) It helps in identifying and tracking the changes or movements of rows within a table.

`      `ii) It facilitates the creation of unique identifiers or keys for rows in a dataset.

`      `iii) It supports the generation of row-level rankings or sequence numbers for further analysis.

`      `iv) It assists in comparing the relative positions of rows within a specified partition.

15\. **SELECTEDVALUE**:

`   `a) What is the purpose of the SELECTEDVALUE function in Power Query?

`      `i) It returns the average value of a numeric column.

`      `ii) It calculates the sum of values in a column or table.

`      `iii) It returns the value when the context for a column has been filtered down to one distinct value only.

`      `iv) It removes all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the SELECTEDVALUE function behave when multiple distinct values are present in the context for a column?

`      `i) It returns an error indicating that multiple distinct values are present.

`      `ii) It returns the sum of all distinct values.

`      `iii) It returns the first distinct value encountered in the context.

`      `iv) It returns an average of all distinct values.

`   `c) Which function can be used as an alternative to SELECTEDVALUE when handling scenarios with multiple distinct values?

`      `i) CALCULATE

`      `ii) AVERAGE

`      `iii) SUM

`      `iv) DISTINCTCOUNT

`   `d) What is the syntax for using the SELECTEDVALUE function?

`      `i) SELECTEDVALUE(column)

`      `ii) SELECTEDVALUE(column, alternateResult)

`      `iii) SELECTEDVALUE(table, column)

`      `iv) SELECTEDVALUE(expression, column)

`   `e) How can the SELECTEDVALUE function be useful in data analysis or transformations?

`      `i) It enables the retrieval of a single value when the context filters ensure a unique value.

`      `ii) It helps handle scenarios where there might be missing or null values in a column.

`      `iii) It assists in aggregating values across multiple rows into a single result.

`      `iv) It simplifies calculations by automatically handling the selection of values based on the context.

16\. **WINDOW**:

`   `a) What is the purpose of the WINDOW function in Power Query?

`      `i) It returns all the rows in a table, regardless of any filters that might have been applied.

`      `ii) It calculates the sum of values in a column or table.

`      `iii) It returns multiple rows positioned within a given interval for further analysis.

`      `iv) It clears all context filters in the table, providing a clean slate for further analysis.

`   `b) How does the WINDOW function determine the rows to return within the given interval?

`      `i) It defines the columns that determine the sort order within each partition using the ORDERBY function.

`      `ii) It assigns a unique ranking to each row based on the specified criteria.

`      `iii) It evaluates an expression in a modified filter context to determine the rows.

`      `iv) It removes all context filters from the specified tables or columns.

`   `c) Which function can be used in combination with WINDOW to define the columns used to partition the data before returning the rows?

`      `i) FILTER

`      `ii) PARTITIONBY

`      `iii) CALCULATE

`      `iv) INDEX

`   `d) What is the syntax for using the WINDOW function?

`      `i) WINDOW()

`      `ii) WINDOW(partition\_columns, order\_by)

`      `iii) WINDOW(expression, partition\_columns, order\_by)

`      `iv) WINDOW(order\_by)

`   `e) How can the WINDOW function be useful in data analysis or transformations?

`      `i) It allows for the calculation of running totals, moving averages, and other window-based calculations.

`      `ii) It provides a way to examine subsets of data within a specified range or interval.

`      `iii) It supports the identification and analysis of patterns or trends in a dataset.

`      `iv) It facilitates the comparison of values across different rows or groups within a partition.


