**DAX:** Data analysis Expresisions(DAX) is formula a laguaage the consists of a library of more than 200 funcitons, constants, and operators

DAX is used in a formula or expression, to calculate and return a single value, or multiple values

DAX is not a new feature: you may have used it in Power Pivot for Excel or SQL Server Analysis Services(SAAS)

**USE CASE:**	

1. CREATING COLUMNS
1. CREATING TABLES
1. CREATING MEASURES

**Data Analysis Expressions (DAX)** is a library of functions and operators that can be combined to build formulas and expressions in Power BI, Analysis Services, and Power Pivot in Excel data models.

There are two primary data types in Power BI DAX functions:

- **Numeric:** numeric data types include decimals, currency values, integers, etc.
- **Non-numeric:** it consists of strings, binary objects, etc. 
## **DAX Formula – Syntax**


It represents a custom formula used to create new columns by multiplying the values of the other two columns. Let’s break it down and understand what each element does:

- Test Column: Name of the new measure
- (=) Sign: Indicates the starting of your DAX formula
- [Units Sold] and [Manufacturing Price]= These two are the arguments or columns whose values are used to generate the output.
- (\*): The ‘\*’ operator multiplies the values of the two-column variables.
- [Segment]= Segment represents the classification of the corresponding formula. Unlike regular columns, the calculated columns are necessary to have at least one.


**DAX function reference**

[New DAX functions](https://learn.microsoft.com/en-us/dax/new-dax-functions) - These functions are new or are existing functions that have been significantly updated.

[Aggregation functions](https://learn.microsoft.com/en-us/dax/aggregation-functions-dax) - These functions calculate a (scalar) value such as count, sum, average, minimum, or maximum for all rows in a column or table as defined by the expression.

[Date and time functions](https://learn.microsoft.com/en-us/dax/date-and-time-functions-dax) - These functions in DAX are similar to date and time functions in Microsoft Excel. However, DAX functions are based on the date time data types used by Microsoft SQL Server.

[Filter functions](https://learn.microsoft.com/en-us/dax/filter-functions-dax) - These functions help you return specific data types, look up values in related tables, and filter by related values. Lookup functions work by using tables and relationships between them. Filtering functions let you manipulate data context to create dynamic calculations.

[Financial functions](https://learn.microsoft.com/en-us/dax/financial-functions-dax) - These functions are used in formulas that perform financial calculations, such as net present value and rate of return.

[Information functions](https://learn.microsoft.com/en-us/dax/information-functions-dax) - These functions look at a table or column provided as an argument to another function and returns whether the value matches the expected type. For example, the ISERROR function returns TRUE if the value you reference contains an error.

[Logical functions](https://learn.microsoft.com/en-us/dax/logical-functions-dax) - These functions return information about values in an expression. For example, the TRUE function lets you know whether an expression that you are evaluating returns a TRUE value.

[Math and Trig functions](https://learn.microsoft.com/en-us/dax/math-and-trig-functions-dax) - Mathematical functions in DAX are similar to Excel's mathematical and trigonometric functions. However, there are some differences in the numeric data types used by DAX functions.

[Other functions](https://learn.microsoft.com/en-us/dax/other-functions-dax) - These functions perform unique actions that cannot be defined by any of the categories most other functions belong to.

[Parent and Child functions](https://learn.microsoft.com/en-us/dax/parent-and-child-functions-dax) - These functions help users manage data that is presented as a parent/child hierarchy in their data models.

[Relationship functions](https://learn.microsoft.com/en-us/dax/relationship-functions-dax) - These functions are for managing and utilizing relationships between tables. For example, you can specify a particular relationship to be used in a calculation.

[Statistical functions](https://learn.microsoft.com/en-us/dax/statistical-functions-dax) - These functions calculate values related to statistical distributions and probability, such as standard deviation and number of permutations.

[Table manipulation functions](https://learn.microsoft.com/en-us/dax/table-manipulation-functions-dax) - These functions return a table or manipulate existing tables.

[Text functions](https://learn.microsoft.com/en-us/dax/text-functions-dax) - With these functions, you can return part of a string, search for text within a string, or concatenate string values. Additional functions are for controlling the formats for dates, times, and numbers.

[Time intelligence functions](https://learn.microsoft.com/en-us/dax/time-intelligence-functions-dax) - These functions help you create calculations that use built-in knowledge about calendars and dates. By using time and date ranges in combination with aggregations or calculations, you can build meaningful comparisons across comparable time periods for sales, inventory, and so on.

Expression: it defines a condition.

# **Aggregation functions**


|**Function**|**Description**|
| :- | :- |
|[APPROXIMATEDISTINCTCOUNT](https://learn.microsoft.com/en-us/dax/approximate-distinctcount-function-dax)|Returns an *estimated* count of unique values in a column.0|
|[AVERAGE](https://learn.microsoft.com/en-us/dax/average-function-dax)|Returns the average (arithmetic mean) of numeric values, excluding blanks|
|[AVERAGEA](https://learn.microsoft.com/en-us/dax/averagea-function-dax)|Returns the average (arithmetic mean) both numeric and non numeric values, treating non-numeric values as Zero|
|[AVERAGEX](https://learn.microsoft.com/en-us/dax/averagex-function-dax)|Calculates the average (arithmetic mean) of a set of expressions evaluated over a table  or based on expression and an iterator|
|[COUNT](https://learn.microsoft.com/en-us/dax/count-function-dax)|Counts the number of rows in the specified column that contain non-blank values, excluding blank and null values|
|[COUNTA](https://learn.microsoft.com/en-us/dax/counta-function-dax)|Counts the number of rows in the specified column that contain non-blank values , Boolean functions, Boolean values, strings and dates, blank values but returns a blank and errors|
|[COUNTAX](https://learn.microsoft.com/en-us/dax/countax-function-dax)|Counts non-blank results when evaluating the result of an expression over a table, Boolean functions, Boolean values, strings and dates, blank values but returns a blank and errors|
|[COUNTBLANK](https://learn.microsoft.com/en-us/dax/countblank-function-dax)|Counts the number of blank cells in a column.|
|[COUNTROWS](https://learn.microsoft.com/en-us/dax/countrows-function-dax)|Counts the number of rows in the specified table, or in a table defined by an expression.|
|[COUNTX](https://learn.microsoft.com/en-us/dax/countx-function-dax)|Counts the number of rows that contain a number or an expression that evaluates to a number, when evaluating an expression over a table, excluding blank. The **CountX** function does not count boolean values but If you include true/false with categorical data and numerical values it will count. The only boolean values does not count.|
|[DISTINCTCOUNT](https://learn.microsoft.com/en-us/dax/distinctcount-function-dax)|Counts the number of distinct values in a column, which can contain any type of data.|
|[DISTINCTCOUNTNOBLANK](https://learn.microsoft.com/en-us/dax/distinctcountnoblank-function-dax)|Counts the number of distinct values in a column.|
|[MAX](https://learn.microsoft.com/en-us/dax/max-function-dax)|Returns the largest numeric value in a column, or between two scalar expressions.|
|[MAXA](https://learn.microsoft.com/en-us/dax/maxa-function-dax)|Returns the largest value in a column.|
|[MAXX](https://learn.microsoft.com/en-us/dax/maxx-function-dax)|Evaluates an expression for each row of a table and returns the largest numeric value.|
|[MIN](https://learn.microsoft.com/en-us/dax/min-function-dax)|Returns the smallest numeric value in a column, or between two scalar expressions.|
|[MINA](https://learn.microsoft.com/en-us/dax/mina-function-dax)|Returns the smallest value in a column, including any logical values and numbers represented as text.|
|[MINX](https://learn.microsoft.com/en-us/dax/minx-function-dax)|Returns the smallest numeric value that results from evaluating an expression for each row of a table.|
|[PRODUCT](https://learn.microsoft.com/en-us/dax/product-function-dax)|Returns the product of the numbers in a column.|
|[PRODUCTX](https://learn.microsoft.com/en-us/dax/productx-function-dax)|Returns the product of an expression evaluated for each row in a table.|
|[SUM](https://learn.microsoft.com/en-us/dax/sum-function-dax)|Adds all the numbers in a column.|
|[SUMX](https://learn.microsoft.com/en-us/dax/sumx-function-dax)|Returns the sum of an expression evaluated for each row in a table|

# **Date and time functions**
#

|**Function**|**Description**|
| :- | :- |
|[CALENDAR](https://learn.microsoft.com/en-us/dax/calendar-function-dax)|Returns a table with a single column named "Date" that contains a contiguous set of dates.|
|[CALENDARAUTO](https://learn.microsoft.com/en-us/dax/calendarauto-function-dax)|Returns a table with a single column named "Date" that contains a contiguous set of dates.|
|[DATE](https://learn.microsoft.com/en-us/dax/date-function-dax)|Returns the specified date in datetime format.|
|[DATEDIFF](https://learn.microsoft.com/en-us/dax/datediff-function-dax)|Returns the number of interval boundaries between two dates.|
|[DATEVALUE](https://learn.microsoft.com/en-us/dax/datevalue-function-dax)|Converts a date in the form of text to a date in datetime format.|
|[DAY](https://learn.microsoft.com/en-us/dax/day-function-dax)|Returns the day of the month, a number from 1 to 31.|
|[EDATE](https://learn.microsoft.com/en-us/dax/edate-function-dax)|Returns the date that is the indicated number of months before or after the start date.|
|[EOMONTH](https://learn.microsoft.com/en-us/dax/eomonth-function-dax)|Returns the date in datetime format of the last day of the month, before or after a specified number of months.|
|[HOUR](https://learn.microsoft.com/en-us/dax/hour-function-dax)|Returns the hour as a number from 0 (12:00 A.M.) to 23 (11:00 P.M.).|
|[MINUTE](https://learn.microsoft.com/en-us/dax/minute-function-dax)|Returns the minute as a number from 0 to 59, given a date and time value.|
|[MONTH](https://learn.microsoft.com/en-us/dax/month-function-dax)|Returns the month as a number from 1 (January) to 12 (December).|
|[NETWORKDAYS](https://learn.microsoft.com/en-us/dax/networkdays-dax)|Returns the number of whole workdays between two dates.|
|[NOW](https://learn.microsoft.com/en-us/dax/now-function-dax)|Returns the current date and time in datetime format.|
|[QUARTER](https://learn.microsoft.com/en-us/dax/quarter-function-dax)|Returns the quarter as a number from 1 to 4.|
|[SECOND](https://learn.microsoft.com/en-us/dax/second-function-dax)|Returns the seconds of a time value, as a number from 0 to 59.|
|[TIME](https://learn.microsoft.com/en-us/dax/time-function-dax)|Converts hours, minutes, and seconds given as numbers to a time in datetime format.|
|[TIMEVALUE](https://learn.microsoft.com/en-us/dax/timevalue-function-dax)|Converts a time in text format to a time in datetime format.|
|[TODAY](https://learn.microsoft.com/en-us/dax/today-function-dax)|Returns the current date.|
|[UTCNOW](https://learn.microsoft.com/en-us/dax/utcnow-function-dax)|Returns the current UTC date and time|
|[UTCTODAY](https://learn.microsoft.com/en-us/dax/utctoday-function-dax)|Returns the current UTC date.|
|[WEEKDAY](https://learn.microsoft.com/en-us/dax/weekday-function-dax)|Returns a number from 1 to 7 identifying the day of the week of a date.|
|[WEEKNUM](https://learn.microsoft.com/en-us/dax/weeknum-function-dax)|Returns the week number for the given date and year according to the return\_type value.|
|[YEAR](https://learn.microsoft.com/en-us/dax/year-function-dax)|Returns the year of a date as a four digit integer in the range 1900-9999.|
|[YEARFRAC](https://learn.microsoft.com/en-us/dax/yearfrac-function-dax)|Calculates the fraction of the year represented by the number of whole days between two dates.|


# **Filter functions**


|**Function**|**Description**|
| :- | :- |
|[ALL](https://learn.microsoft.com/en-us/dax/all-function-dax)|Returns all the rows in a table, or all the values in a column, ignoring any filters that might have been applied.|
|[ALLCROSSFILTERED](https://learn.microsoft.com/en-us/dax/allcrossfiltered-function-dax)|Clear all filters which are applied to a table.|
|[ALLEXCEPT](https://learn.microsoft.com/en-us/dax/allexcept-function-dax)|Removes all context filters in the table except filters that have been applied to the specified columns.|
|[ALLNOBLANKROW](https://learn.microsoft.com/en-us/dax/allnoblankrow-function-dax)|From the parent table of a relationship, returns all rows but the blank row, or all distinct values of a column but the blank row, and disregards any context filters that might exist.|
|[ALLSELECTED](https://learn.microsoft.com/en-us/dax/allselected-function-dax)|Removes context filters from columns and rows in the current query, while retaining all other context filters or explicit filters.|
|[CALCULATE](https://learn.microsoft.com/en-us/dax/calculate-function-dax)|Evaluates an expression in a modified filter context.|
|[CALCULATETABLE](https://learn.microsoft.com/en-us/dax/calculatetable-function-dax)|Evaluates a table expression in a modified filter context.|
|[EARLIER](https://learn.microsoft.com/en-us/dax/earlier-function-dax)|Returns the current value of the specified column in an outer evaluation pass of the mentioned column.|
|[EARLIEST](https://learn.microsoft.com/en-us/dax/earliest-function-dax)|Returns the current value of the specified column in an outer evaluation pass of the specified column.|
|[FILTER](https://learn.microsoft.com/en-us/dax/filter-function-dax)|Returns a table that represents a subset of another table or expression.|
|[INDEX](https://learn.microsoft.com/en-us/dax/index-function-dax)|Returns a row at an absolute position, specified by the position parameter, within the specified partition, sorted by the specified order or on the specified axis.|
|[KEEPFILTERS](https://learn.microsoft.com/en-us/dax/keepfilters-function-dax)|Modifies how filters are applied while evaluating a CALCULATE or CALCULATETABLE function.|
|[LOOKUPVALUE](https://learn.microsoft.com/en-us/dax/lookupvalue-function-dax)|Returns the value for the row that meets all criteria specified by search conditions. The function can apply one or more search conditions.|
|[MATCHBY](https://learn.microsoft.com/en-us/dax/matchby-function-dax)|In window functions, defines the columns that are used to determine how to match data and identify the *current row*.|
|[OFFSET](https://learn.microsoft.com/en-us/dax/offset-function-dax)|Returns a single row that is positioned either before or after the *current row* within the same table, by a given offset.|
|[ORDERBY](https://learn.microsoft.com/en-us/dax/orderby-function-dax)|Defines the columns that determine the sort order within each of a WINDOW function’s partitions.|
|[PARTITIONBY](https://learn.microsoft.com/en-us/dax/partitionby-function-dax)|Defines the columns that are used to partition a WINDOW function’s <relation> parameter.|
|[RANK](https://learn.microsoft.com/en-us/dax/rank-function-dax)|Returns the ranking of a row within the given interval.|
|[REMOVEFILTERS](https://learn.microsoft.com/en-us/dax/removefilters-function-dax)|Clears filters from the specified tables or columns.|
|[ROWNUMBER](https://learn.microsoft.com/en-us/dax/rownumber-function-dax)|Returns the unique ranking of a row within the given interval.|
|[SELECTEDVALUE](https://learn.microsoft.com/en-us/dax/selectedvalue-function)|Returns the value when the context for columnName has been filtered down to one distinct value only. Otherwise returns alternateResult.|
|[WINDOW](https://learn.microsoft.com/en-us/dax/window-function-dax)|Returns multiple rows which are positioned within the given interval.|


# **Financial functions**



|**Function**|**Description**|
| :- | :- |
|[ACCRINT](https://learn.microsoft.com/en-us/dax/accrint-function-dax)|Returns the accrued interest for a security that pays periodic interest.|
|[ACCRINTM](https://learn.microsoft.com/en-us/dax/accrintm-function-dax)|Returns the accrued interest for a security that pays interest at maturity.|
|[AMORDEGRC](https://learn.microsoft.com/en-us/dax/amordegrc-function-dax)|Returns the depreciation for each accounting period. Similar to AMORLINC, except a depreciation coefficient is applied depending on the life of the assets.|
|[AMORLINC](https://learn.microsoft.com/en-us/dax/amorlinc-function-dax)|Returns the depreciation for each accounting period.|
|[COUPDAYBS](https://learn.microsoft.com/en-us/dax/coupdaybs-function-dax)|Returns the number of days from the beginning of a coupon period until its settlement date.|
|[COUPDAYS](https://learn.microsoft.com/en-us/dax/coupdays-function-dax)|Returns the number of days in the coupon period that contains the settlement date.|
|[COUPDAYSNC](https://learn.microsoft.com/en-us/dax/coupdaysnc-function-dax)|Returns the number of days from the settlement date to the next coupon date.|
|[COUPNCD](https://learn.microsoft.com/en-us/dax/coupncd-function-dax)|Returns the next coupon date after the settlement date.|
|[COUPNUM](https://learn.microsoft.com/en-us/dax/coupnum-function-dax)|Returns the number of coupons payable between the settlement date and maturity date, rounded up to the nearest whole coupon.|
|[COUPPCD](https://learn.microsoft.com/en-us/dax/couppcd-function-dax)|Returns the previous coupon date before the settlement date.|
|[CUMIPMT](https://learn.microsoft.com/en-us/dax/cumipmt-function-dax)|Returns the cumulative interest paid on a loan between start\_period and end\_period.|
|[CUMPRINC](https://learn.microsoft.com/en-us/dax/cumprinc-function-dax)|Returns the cumulative principal paid on a loan between start\_period and end\_period.|
|[DB](https://learn.microsoft.com/en-us/dax/db-function-dax)|Returns the depreciation of an asset for a specified period using the fixed-declining balance method.|
|[DDB](https://learn.microsoft.com/en-us/dax/ddb-function-dax)|Returns the depreciation of an asset for a specified period using the double-declining balance method or some other method you specify.|
|[DISC](https://learn.microsoft.com/en-us/dax/disc-function-dax)|Returns the discount rate for a security.|
|[DOLLARDE](https://learn.microsoft.com/en-us/dax/dollarde-function-dax)|Converts a dollar price expressed as an integer part and a fraction part, such as 1.02, into a dollar price expressed as a decimal number.|
|[DOLLARFR](https://learn.microsoft.com/en-us/dax/dollarfr-function-dax)|Converts a dollar price expressed as an integer part and a fraction part, such as 1.02, into a dollar price expressed as a decimal number.|
|[DURATION](https://learn.microsoft.com/en-us/dax/duration-function-dax)|Returns the Macauley duration for an assumed par value of $100.|
|[EFFECT](https://learn.microsoft.com/en-us/dax/effect-function-dax)|Returns the effective annual interest rate, given the nominal annual interest rate and the number of compounding periods per year.|
|[FV](https://learn.microsoft.com/en-us/dax/fv-function-dax)|Calculates the future value of an investment based on a constant interest rate.|
|[INTRATE](https://learn.microsoft.com/en-us/dax/intrate-function-dax)|Returns the interest rate for a fully invested security.|
|[IPMT](https://learn.microsoft.com/en-us/dax/ipmt-function-dax)|Returns the interest payment for a given period for an investment based on periodic, constant payments and a constant interest rate.|
|[ISPMT](https://learn.microsoft.com/en-us/dax/ispmt-function-dax)|Calculates the interest paid (or received) for the specified period of a loan (or investment) with even principal payments.|
|[MDURATION](https://learn.microsoft.com/en-us/dax/mduration-function-dax)|Returns the modified Macauley duration for a security with an assumed par value of $100.|
|[NOMINAL](https://learn.microsoft.com/en-us/dax/nominal-function-dax)|Returns the nominal annual interest rate, given the effective rate and the number of compounding periods per year.|
|[NPER](https://learn.microsoft.com/en-us/dax/nper-function-dax)|Returns the number of periods for an investment based on periodic, constant payments and a constant interest rate.|
|[ODDFPRICE](https://learn.microsoft.com/en-us/dax/oddfprice-function-dax)|Returns the price per $100 face value of a security having an odd (short or long) first period.|
|[ODDFYIELD](https://learn.microsoft.com/en-us/dax/oddfyield-function-dax)|Returns the yield of a security that has an odd (short or long) first period.|
|[ODDLPRICE](https://learn.microsoft.com/en-us/dax/oddlprice-function-dax)|Returns the price per $100 face value of a security having an odd (short or long) last coupon period.|
|[ODDLYIELD](https://learn.microsoft.com/en-us/dax/oddlyield-function-dax)|Returns the yield of a security that has an odd (short or long) last period.|
|[PDURATION](https://learn.microsoft.com/en-us/dax/pduration-function-dax)|Returns the number of periods required by an investment to reach a specified value.|
|[PMT](https://learn.microsoft.com/en-us/dax/pmt-function-dax)|Calculates the payment for a loan based on constant payments and a constant interest rate.|
|[PPMT](https://learn.microsoft.com/en-us/dax/ppmt-function-dax)|Returns the payment on the principal for a given period for an investment based on periodic, constant payments and a constant interest rate.|
|[PRICE](https://learn.microsoft.com/en-us/dax/price-function-dax)|Returns the price per $100 face value of a security that pays periodic interest.|
|[PRICEDISC](https://learn.microsoft.com/en-us/dax/pricedisc-function-dax)|Returns the price per $100 face value of a discounted security.|
|[PRICEMAT](https://learn.microsoft.com/en-us/dax/pricemat-function-dax)|Returns the price per $100 face value of a security that pays interest at maturity.|
|[PV](https://learn.microsoft.com/en-us/dax/pv-function-dax)|Calculates the present value of a loan or an investment, based on a constant interest rate.|
|[RATE](https://learn.microsoft.com/en-us/dax/rate-function-dax)|Returns the interest rate per period of an annuity.|
|[RECEIVED](https://learn.microsoft.com/en-us/dax/received-function-dax)|Returns the amount received at maturity for a fully invested security.|
|[RRI](https://learn.microsoft.com/en-us/dax/rri-function-dax)|Returns an equivalent interest rate for the growth of an investment.|
|[SLN](https://learn.microsoft.com/en-us/dax/sln-function-dax)|Returns the straight-line depreciation of an asset for one period.|
|[SYD](https://learn.microsoft.com/en-us/dax/syd-function-dax)|Returns the sum-of-years' digits depreciation of an asset for a specified period.|
|[TBILLEQ](https://learn.microsoft.com/en-us/dax/tbilleq-function-dax)|Returns the bond-equivalent yield for a Treasury bill.|
|[TBILLPRICE](https://learn.microsoft.com/en-us/dax/tbillprice-function-dax)|Returns the price per $100 face value for a Treasury bill.|
|[TBILLYIELD](https://learn.microsoft.com/en-us/dax/tbillyield-function-dax)|Returns the yield for a Treasury bill.|
|[VDB](https://learn.microsoft.com/en-us/dax/vdb-function-dax)|Returns the depreciation of an asset for any period you specify, including partial periods, using the double-declining balance method or some other method you specify.|
|[XIRR](https://learn.microsoft.com/en-us/dax/xirr-function-dax)|Returns the internal rate of return for a schedule of cash flows that is not necessarily periodic.|
|[XNPV](https://learn.microsoft.com/en-us/dax/xnpv-function-dax)|Returns the present value for a schedule of cash flows that is not necessarily periodic.|
|[YIELD](https://learn.microsoft.com/en-us/dax/yield-function-dax)|Returns the yield on a security that pays periodic interest.|
|[YIELDDISC](https://learn.microsoft.com/en-us/dax/yielddisc-function-dax)|Returns the annual yield for a discounted security.|
|[YIELDMAT](https://learn.microsoft.com/en-us/dax/yieldmat-function-dax)|Returns the annual yield of a security that pays interest at maturity.|


# **Information functions**


|**Function**|**Description**|
| :- | :- |
|[COLUMNSTATISTICS](https://learn.microsoft.com/en-us/dax/columnstatistics-function-dax)|Returns a table of statistics regarding every column in every table in the model.|
|[CONTAINS](https://learn.microsoft.com/en-us/dax/contains-function-dax)|Returns true if values for all referred columns exist, or are contained, in those columns; otherwise, the function returns false.|
|[CONTAINSROW](https://learn.microsoft.com/en-us/dax/containsrow-function-dax)|Returns TRUE if a row of values exists or contained in a table, otherwise returns FALSE.|
|[CONTAINSSTRING](https://learn.microsoft.com/en-us/dax/containsstring-function-dax)|Returns TRUE or FALSE indicating whether one string contains another string.|
|[CONTAINSSTRINGEXACT](https://learn.microsoft.com/en-us/dax/containsstringexact-function-dax)|Returns TRUE or FALSE indicating whether one string contains another string.|
|[CUSTOMDATA](https://learn.microsoft.com/en-us/dax/customdata-function-dax)|Returns the content of the CustomData property in the connection string.|
|[HASONEFILTER](https://learn.microsoft.com/en-us/dax/hasonefilter-function-dax)|Returns TRUE when the number of directly filtered values on *columnName* is one; otherwise returns FALSE.|
|[HASONEVALUE](https://learn.microsoft.com/en-us/dax/hasonevalue-function-dax)|Returns TRUE when the context for *columnName* has been filtered down to one distinct value only. Otherwise is FALSE.|
|[ISAFTER](https://learn.microsoft.com/en-us/dax/isafter-function-dax)|A boolean function that emulates the behavior of a Start At clause and returns true for a row that meets all of the condition parameters.|
|[ISBLANK](https://learn.microsoft.com/en-us/dax/isblank-function-dax)|Checks whether a value is blank, and returns TRUE or FALSE.|
|[ISCROSSFILTERED](https://learn.microsoft.com/en-us/dax/iscrossfiltered-function-dax)|Returns TRUE when *columnName* or another column in the same or related table is being filtered.|
|[ISEMPTY](https://learn.microsoft.com/en-us/dax/isempty-function-dax)|Checks if a table is empty.|
|[ISERROR](https://learn.microsoft.com/en-us/dax/iserror-function-dax)|Checks whether a value is an error, and returns TRUE or FALSE.|
|[ISEVEN](https://learn.microsoft.com/en-us/dax/iseven-function-dax)|Returns TRUE if number is even, or FALSE if number is odd.|
|[ISFILTERED](https://learn.microsoft.com/en-us/dax/isfiltered-function-dax)|Returns TRUE when *columnName* is being filtered directly.|
|[ISINSCOPE](https://learn.microsoft.com/en-us/dax/isinscope-function-dax)|Returns true when the specified column is the level in a hierarchy of levels.|
|[ISLOGICAL](https://learn.microsoft.com/en-us/dax/islogical-function-dax)|Checks whether a value is a logical value, (TRUE or FALSE), and returns TRUE or FALSE.|
|[ISNONTEXT](https://learn.microsoft.com/en-us/dax/isnontext-function-dax)|Checks if a value is not text (blank cells are not text), and returns TRUE or FALSE.|
|[ISNUMBER](https://learn.microsoft.com/en-us/dax/isnumber-function-dax)|Checks whether a value is a number, and returns TRUE or FALSE.|
|[ISODD](https://learn.microsoft.com/en-us/dax/isodd-function-dax)|Returns TRUE if number is odd, or FALSE if number is even.|
|[ISONORAFTER](https://learn.microsoft.com/en-us/dax/isonorafter-function-dax)|A boolean function that emulates the behavior of a Start At clause and returns true for a row that meets all of the condition parameters.|
|[ISSELECTEDMEASURE](https://learn.microsoft.com/en-us/dax/isselectedmeasure-function-dax)|Used by expressions for calculation items to determine the measure that is in context is one of those specified in a list of measures.|
|[ISSUBTOTAL](https://learn.microsoft.com/en-us/dax/issubtotal-function-dax)|Creates another column in a SUMMARIZE expression that returns True if the row contains subtotal values for the column given as argument, otherwise returns False.|
|[ISTEXT](https://learn.microsoft.com/en-us/dax/istext-function-dax)|Checks if a value is text, and returns TRUE or FALSE.|
|[NONVISUAL](https://learn.microsoft.com/en-us/dax/nonvisual-function-dax)|Marks a value filter in a SUMMARIZECOLUMNS expression as non-visual.|
|[SELECTEDMEASURE](https://learn.microsoft.com/en-us/dax/selectedmeasure-function-dax)|Used by expressions for calculation items to reference the measure that is in context.|
|[SELECTEDMEASUREFORMATSTRING](https://learn.microsoft.com/en-us/dax/selectedmeasureformatstring-function-dax)|Used by expressions for calculation items to retrieve the format string of the measure that is in context.|
|[SELECTEDMEASURENAME](https://learn.microsoft.com/en-us/dax/selectedmeasurename-function-dax)|Used by expressions for calculation items to determine the measure that is in context by name.|
|[USERCULTURE](https://learn.microsoft.com/en-us/dax/userculture-function-dax)|Returns the locale for the current user.|
|[USERNAME](https://learn.microsoft.com/en-us/dax/username-function-dax)|Returns the domain name and username from the credentials given to the system at connection time.|
|[USEROBJECTID](https://learn.microsoft.com/en-us/dax/userobjectid-function-dax)|Returns the current user's Object ID or SID.|
|[USERPRINCIPALNAME](https://learn.microsoft.com/en-us/dax/userprincipalname-function-dax)|Returns the user principal name.|


# **Logical functions**


|**Function**|**Description**|
| :- | :- |
|[AND](https://learn.microsoft.com/en-us/dax/and-function-dax)|Checks whether both arguments are TRUE, and returns TRUE if both arguments are TRUE.|
|[BITAND](https://learn.microsoft.com/en-us/dax/bitand-function-dax)|Returns a bitwise 'AND' of two numbers.|
|[BITLSHIFT](https://learn.microsoft.com/en-us/dax/bitlshift-function-dax)|Returns a number shifted left by the specified number of bits.|
|[BITOR](https://learn.microsoft.com/en-us/dax/bitor-function-dax)|Returns a bitwise 'OR' of two numbers.|
|[BITRSHIFT](https://learn.microsoft.com/en-us/dax/bitrshift-function-dax)|Returns a number shifted right by the specified number of bits.|
|[BITXOR](https://learn.microsoft.com/en-us/dax/bitxor-function-dax)|Returns a bitwise 'XOR' of two numbers.|
|[COALESCE](https://learn.microsoft.com/en-us/dax/coalesce-function-dax)|Returns the first expression that does not evaluate to BLANK.|
|[FALSE](https://learn.microsoft.com/en-us/dax/false-function-dax)|Returns the logical value FALSE.|
|[IF](https://learn.microsoft.com/en-us/dax/if-function-dax)|Checks a condition, and returns one value when TRUE, otherwise it returns a second value.|
|[IF.EAGER](https://learn.microsoft.com/en-us/dax/if-eager-function-dax)|Checks a condition, and returns one value when TRUE, otherwise it returns a second value. Uses an *eager* execution plan which always executes the branch expressions regardless of the condition expression.|
|[IFERROR](https://learn.microsoft.com/en-us/dax/iferror-function-dax)|Evaluates an expression and returns a specified value if the expression returns an error|
|[NOT](https://learn.microsoft.com/en-us/dax/not-function-dax)|Changes FALSE to TRUE, or TRUE to FALSE.|
|[OR](https://learn.microsoft.com/en-us/dax/or-function-dax)|Checks whether one of the arguments is TRUE to return TRUE.|
|[SWITCH](https://learn.microsoft.com/en-us/dax/switch-function-dax)|Evaluates an expression against a list of values and returns one of multiple possible result expressions.|
|[TRUE](https://learn.microsoft.com/en-us/dax/true-function-dax)|Returns the logical value TRUE.|


# **Math and Trig functions**



|**Function**|**Description**|
| :- | :- |
|[ABS](https://learn.microsoft.com/en-us/dax/abs-function-dax)|Returns the absolute value of a number.|
|[ACOS](https://learn.microsoft.com/en-us/dax/acos-function-dax)|Returns the arccosine, or inverse cosine, of a number.|
|[ACOSH](https://learn.microsoft.com/en-us/dax/acosh-function-dax)|Returns the inverse hyperbolic cosine of a number.|
|[ACOT](https://learn.microsoft.com/en-us/dax/acot-function-dax)|Returns the arccotangent, or inverse cotangent, of a number.|
|[ACOTH](https://learn.microsoft.com/en-us/dax/acoth-function-dax)|Returns the inverse hyperbolic cotangent of a number.|
|[ASIN](https://learn.microsoft.com/en-us/dax/asin-function-dax)|Returns the arcsine, or inverse sine, of a number.|
|[ASINH](https://learn.microsoft.com/en-us/dax/asinh-function-dax)|Returns the inverse hyperbolic sine of a number.|
|[ATAN](https://learn.microsoft.com/en-us/dax/atan-function-dax)|Returns the arctangent, or inverse tangent, of a number.|
|[ATANH](https://learn.microsoft.com/en-us/dax/atanh-function-dax)|Returns the inverse hyperbolic tangent of a number.|
|[CEILING](https://learn.microsoft.com/en-us/dax/ceiling-function-dax)|Rounds a number up, to the nearest integer or to the nearest multiple of significance.|
|[CONVERT](https://learn.microsoft.com/en-us/dax/convert-function-dax)|Converts an expression of one data type to another.|
|[COS](https://learn.microsoft.com/en-us/dax/cos-function-dax)|Returns the cosine of the given angle.|
|[COSH](https://learn.microsoft.com/en-us/dax/cosh-function-dax)|Returns the hyperbolic cosine of a number.|
|[COT](https://learn.microsoft.com/en-us/dax/cot-function-dax)|Returns the cotangent of an angle specified in radians.|
|[COTH](https://learn.microsoft.com/en-us/dax/coth-function-dax)|Returns the hyperbolic cotangent of a hyperbolic angle.|
|[CURRENCY](https://learn.microsoft.com/en-us/dax/currency-function-dax)|Evaluates the argument and returns the result as currency data type.|
|[DEGREES](https://learn.microsoft.com/en-us/dax/degrees-function-dax)|Converts radians into degrees.|
|[DIVIDE](https://learn.microsoft.com/en-us/dax/divide-function-dax)|Performs division and returns alternate result or BLANK() on division by 0.|
|[EVEN](https://learn.microsoft.com/en-us/dax/even-function-dax)|Returns number rounded up to the nearest even integer.|
|[EXP](https://learn.microsoft.com/en-us/dax/exp-function-dax)|Returns e raised to the power of a given number.|
|[FACT](https://learn.microsoft.com/en-us/dax/fact-function-dax)|Returns the factorial of a number, equal to the series 1\*2\*3\*...\* , ending in the given number.|
|[FLOOR](https://learn.microsoft.com/en-us/dax/floor-function-dax)|Rounds a number down, toward zero, to the nearest multiple of significance.|
|[GCD](https://learn.microsoft.com/en-us/dax/gcd-function-dax)|Returns the greatest common divisor of two or more integers.|
|[INT](https://learn.microsoft.com/en-us/dax/int-function-dax)|Rounds a number down to the nearest integer.|
|[ISO.CEILING](https://learn.microsoft.com/en-us/dax/iso-ceiling-function-dax)|Rounds a number up, to the nearest integer or to the nearest multiple of significance.|
|[LCM](https://learn.microsoft.com/en-us/dax/lcm-function-dax)|Returns the least common multiple of integers.|
|[LN](https://learn.microsoft.com/en-us/dax/ln-function-dax)|Returns the natural logarithm of a number.|
|[LOG](https://learn.microsoft.com/en-us/dax/log-function-dax)|Returns the logarithm of a number to the base you specify.|
|[LOG10](https://learn.microsoft.com/en-us/dax/log10-function-dax)|Returns the base-10 logarithm of a number.|
|[MOD](https://learn.microsoft.com/en-us/dax/mod-function-dax)|Returns the remainder after a number is divided by a divisor. The result always has the same sign as the divisor.|
|[MROUND](https://learn.microsoft.com/en-us/dax/mround-function-dax)|Returns a number rounded to the desired multiple.|
|[ODD](https://learn.microsoft.com/en-us/dax/odd-function-dax)|Returns number rounded up to the nearest odd integer.|
|[PI](https://learn.microsoft.com/en-us/dax/pi-function-dax)|Returns the value of Pi, 3.14159265358979, accurate to 15 digits.|
|[POWER](https://learn.microsoft.com/en-us/dax/power-function-dax)|Returns the result of a number raised to a power.|
|[QUOTIENT](https://learn.microsoft.com/en-us/dax/quotient-function-dax)|Performs division and returns only the integer portion of the division result.|
|[RADIANS](https://learn.microsoft.com/en-us/dax/radians-function-dax)|Converts degrees to radians.|
|[RAND](https://learn.microsoft.com/en-us/dax/rand-function-dax)|Returns a random number greater than or equal to 0 and less than 1, evenly distributed.|
|[RANDBETWEEN](https://learn.microsoft.com/en-us/dax/randbetween-function-dax)|Returns a random number in the range between two numbers you specify.|
|[ROUND](https://learn.microsoft.com/en-us/dax/round-function-dax)|Rounds a number to the specified number of digits.|
|[ROUNDDOWN](https://learn.microsoft.com/en-us/dax/rounddown-function-dax)|Rounds a number down, toward zero.|
|[ROUNDUP](https://learn.microsoft.com/en-us/dax/roundup-function-dax)|Rounds a number up, away from 0 (zero).|
|[SIGN](https://learn.microsoft.com/en-us/dax/sign-function-dax)|Determines the sign of a number, the result of a calculation, or a value in a column.|
|[SIN](https://learn.microsoft.com/en-us/dax/sin-function-dax)|Returns the sine of the given angle.|
|[SINH](https://learn.microsoft.com/en-us/dax/sinh-function-dax)|Returns the hyperbolic sine of a number.|
|[SQRT](https://learn.microsoft.com/en-us/dax/sqrt-function-dax)|Returns the square root of a number.|
|[SQRTPI](https://learn.microsoft.com/en-us/dax/sqrtpi-function-dax)|Returns the square root of (number \* pi).|
|[TAN](https://learn.microsoft.com/en-us/dax/tan-function-dax)|Returns the tangent of the given angle.|
|[TANH](https://learn.microsoft.com/en-us/dax/tanh-function-dax)|Returns the hyperbolic tangent of a number.|
|[TRUNC](https://learn.microsoft.com/en-us/dax/trunc-function-dax)|Truncates a number to an integer by removing the decimal, or fractional, part of the number.|


# **Other functions**


|**Function**|**Description**|
| :- | :- |
|[BLANK](https://learn.microsoft.com/en-us/dax/blank-function-dax)|Returns a blank.|
|[ERROR](https://learn.microsoft.com/en-us/dax/error-function)|Raises an error with an error message.|
|[EVALUATEANDLOG](https://learn.microsoft.com/en-us/dax/evaluateandlog-function-dax)|Returns the value of the first argument and logs it in a DAX Evaluation Log profiler event.|
|[TOCSV](https://learn.microsoft.com/en-us/dax/tocsv-function-dax)|Returns a table as a string in CSV format.|
|[TOJSON](https://learn.microsoft.com/en-us/dax/tojson-function-dax)|Returns a table as a string in JSON format.|

# **Parent and Child functions**
#

|**Function**|**Description**|
| :- | :- |
|[PATH](https://learn.microsoft.com/en-us/dax/path-function-dax)|Returns a delimited text string with the identifiers of all the parents of the current identifier.|
|[PATHCONTAINS](https://learn.microsoft.com/en-us/dax/pathcontains-function-dax)|Returns TRUE if the specified *item* exists within the specified *path*.|
|[PATHITEM](https://learn.microsoft.com/en-us/dax/pathitem-function-dax)|Returns the item at the specified *position* from a string resulting from evaluation of a PATH function.|
|[PATHITEMREVERSE](https://learn.microsoft.com/en-us/dax/pathitemreverse-function-dax)|Returns the item at the specified *position* from a string resulting from evaluation of a PATH function.|
|[PATHLENGTH](https://learn.microsoft.com/en-us/dax/pathlength-function-dax)|Returns the number of parents to the specified item in a given PATH result, including self.|
# **Relationship functions**


|**Function**|**Description**|
| :- | :- |
|[CROSSFILTER](https://learn.microsoft.com/en-us/dax/crossfilter-function)|Specifies the cross-filtering direction to be used in a calculation for a relationship that exists between two columns.|
|[RELATED](https://learn.microsoft.com/en-us/dax/related-function-dax)|Returns a related value from another table.|
|[RELATEDTABLE](https://learn.microsoft.com/en-us/dax/relatedtable-function-dax)|Evaluates a table expression in a context modified by the given filters.|
|[USERELATIONSHIP](https://learn.microsoft.com/en-us/dax/userelationship-function-dax)|Specifies the relationship to be used in a specific calculation as the one that exists between columnName1 and columnName2.|
# **Statistical functions**


|**Function**|**Description**|
| :- | :- |
|[BETA.DIST](https://learn.microsoft.com/en-us/dax/beta-dist-function-dax)|Returns the beta distribution.|
|[BETA.INV](https://learn.microsoft.com/en-us/dax/beta-inv-function-dax)|Returns the inverse of the beta cumulative probability density function (BETA.DIST).|
|[CHISQ.DIST](https://learn.microsoft.com/en-us/dax/chisq-dist-function-dax)|Returns the chi-squared distribution.|
|[CHISQ.DIST.RT](https://learn.microsoft.com/en-us/dax/chisq-dist-rt-function-dax)|Returns the right-tailed probability of the chi-squared distribution.|
|[CHISQ.INV](https://learn.microsoft.com/en-us/dax/chisq-inv-function-dax)|Returns the inverse of the left-tailed probability of the chi-squared distribution.|
|[CHISQ.INV.RT](https://learn.microsoft.com/en-us/dax/chisq-inv-rt-function-dax)|Returns the inverse of the right-tailed probability of the chi-squared distribution.|
|[COMBIN](https://learn.microsoft.com/en-us/dax/combin-function-dax)|Returns the number of combinations for a given number of items.|
|[COMBINA](https://learn.microsoft.com/en-us/dax/combina-function-dax)|Returns the number of combinations (with repetitions) for a given number of items.|
|[CONFIDENCE.NORM](https://learn.microsoft.com/en-us/dax/confidence-norm-function-dax)|The confidence interval is a range of values.|
|[CONFIDENCE.T](https://learn.microsoft.com/en-us/dax/confidence-t-function-dax)|Returns the confidence interval for a population mean, using a Student's t distribution.|
|[EXPON.DIST](https://learn.microsoft.com/en-us/dax/expon-dist-function-dax)|Returns the exponential distribution.|
|[GEOMEAN](https://learn.microsoft.com/en-us/dax/geomean-function-dax)|Returns the geometric mean of the numbers in a column.|
|[GEOMEANX](https://learn.microsoft.com/en-us/dax/geomeanx-function-dax)|Returns the geometric mean of an expression evaluated for each row in a table.|
|[LINEST](https://learn.microsoft.com/en-us/dax/linest-function-dax)|Uses the Least Squares method to calculate a straight line that best fits the given data.|
|[LINESTX](https://learn.microsoft.com/en-us/dax/linestx-function-dax)|Uses the Least Squares method to calculate a straight line that best fits the given data. The data result from expressions evaluated for each row in a table.|
|[MEDIAN](https://learn.microsoft.com/en-us/dax/median-function-dax)|Returns the median of numbers in a column.|
|[MEDIANX](https://learn.microsoft.com/en-us/dax/medianx-function-dax)|Returns the median number of an expression evaluated for each row in a table.|
|[NORM.DIST](https://learn.microsoft.com/en-us/dax/norm-dist-dax)|Returns the normal distribution for the specified mean and standard deviation.|
|[NORM.INV](https://learn.microsoft.com/en-us/dax/norm-inv-dax)|The inverse of the normal cumulative distribution for the specified mean and standard deviation.|
|[NORM.S.DIST](https://learn.microsoft.com/en-us/dax/norm-s-dist-dax)|Returns the standard normal distribution (has a mean of zero and a standard deviation of one).|
|[NORM.S.INV](https://learn.microsoft.com/en-us/dax/norm-s-inv-dax)|Returns the inverse of the standard normal cumulative distribution.|
|[PERCENTILE.EXC](https://learn.microsoft.com/en-us/dax/percentile-exc-function-dax)|Returns the k-th percentile of values in a range, where k is in the range 0..1, exclusive.|
|[PERCENTILE.INC](https://learn.microsoft.com/en-us/dax/percentile-inc-function-dax)|Returns the k-th percentile of values in a range, where k is in the range 0..1, inclusive.|
|[PERCENTILEX.EXC](https://learn.microsoft.com/en-us/dax/percentilex-exc-function-dax)|Returns the percentile number of an expression evaluated for each row in a table.|
|[PERCENTILEX.INC](https://learn.microsoft.com/en-us/dax/percentilex-inc-function-dax)|Returns the percentile number of an expression evaluated for each row in a table.|
|[PERMUT](https://learn.microsoft.com/en-us/dax/permut-function-dax)|Returns the number of permutations for a given number of objects that can be selected from number objects.|
|[POISSON.DIST](https://learn.microsoft.com/en-us/dax/poisson-dist-function-dax)|Returns the Poisson distribution.|
|[RANK.EQ](https://learn.microsoft.com/en-us/dax/rank-eq-function-dax)|Returns the ranking of a number in a list of numbers.|
|[RANKX](https://learn.microsoft.com/en-us/dax/rankx-function-dax)|Returns the ranking of a number in a list of numbers for each row in the *table* argument.|
|[SAMPLE](https://learn.microsoft.com/en-us/dax/sample-function-dax)|Returns a sample of N rows from the specified table.|
|[STDEV.P](https://learn.microsoft.com/en-us/dax/stdev-p-function-dax)|Returns the standard deviation of the entire population.|
|[STDEV.S](https://learn.microsoft.com/en-us/dax/stdev-s-function-dax)|Returns the standard deviation of a sample population.|
|[STDEVX.P](https://learn.microsoft.com/en-us/dax/stdevx-p-function-dax)|Returns the standard deviation of the entire population.|
|[STDEVX.S](https://learn.microsoft.com/en-us/dax/stdevx-s-function-dax)|Returns the standard deviation of a sample population.|
|[T.DIST](https://learn.microsoft.com/en-us/dax/t-dist-dax)|Returns the Student's left-tailed t-distribution.|
|[T.DIST.2T](https://learn.microsoft.com/en-us/dax/t-dist-2t-dax)|Returns the two-tailed Student's t-distribution.|
|[T.DIST.RT](https://learn.microsoft.com/en-us/dax/t-dist-rt-dax)|Returns the right-tailed Student's t-distribution.|
|[T.INV](https://learn.microsoft.com/en-us/dax/t-inv-dax)|Returns the left-tailed inverse of the Student's t-distribution.|
|[T.INV.2t](https://learn.microsoft.com/en-us/dax/t-inv-2t-dax)|Returns the two-tailed inverse of the Student's t-distribution.|
|[VAR.P](https://learn.microsoft.com/en-us/dax/var-p-function-dax)|Returns the variance of the entire population.|
|[VAR.S](https://learn.microsoft.com/en-us/dax/var-s-function-dax)|Returns the variance of a sample population.|
|[VARX.P](https://learn.microsoft.com/en-us/dax/varx-p-function-dax)|Returns the variance of the entire population.|
|[VARX.S](https://learn.microsoft.com/en-us/dax/varx-s-function-dax)|Returns the variance of a sample population.|

# **Table manipulation functions**


|**Function**|**Description**|
| :- | :- |
|[ADDCOLUMNS](https://learn.microsoft.com/en-us/dax/addcolumns-function-dax)|Adds calculated columns to the given table or table expression.|
|[ADDMISSINGITEMS](https://learn.microsoft.com/en-us/dax/addmissingitems-function-dax)|Adds combinations of items from multiple columns to a table if they do not already exist.|
|[CROSSJOIN](https://learn.microsoft.com/en-us/dax/crossjoin-function-dax)|Returns a table that contains the Cartesian product of all rows from all tables in the arguments.|
|[CURRENTGROUP](https://learn.microsoft.com/en-us/dax/currentgroup-function-dax)|Returns a set of rows from the table argument of a GROUPBY expression.|
|[DATATABLE](https://learn.microsoft.com/en-us/dax/datatable-function)|Provides a mechanism for declaring an inline set of data values.|
|[DETAILROWS](https://learn.microsoft.com/en-us/dax/detailrows-function-dax)|Evaluates a Detail Rows Expression defined for a measure and returns the data.|
|[DISTINCT column](https://learn.microsoft.com/en-us/dax/distinct-function-dax)|Returns a one-column table that contains the distinct values from the specified column.|
|[DISTINCT table](https://learn.microsoft.com/en-us/dax/distinct-table-function-dax)|Returns a table by removing duplicate rows from another table or expression.|
|[EXCEPT](https://learn.microsoft.com/en-us/dax/except-function-dax)|Returns the rows of one table which do not appear in another table.|
|[FILTERS](https://learn.microsoft.com/en-us/dax/filters-function-dax)|Returns a table of values directly applied as filters to *columnName*.|
|[GENERATE](https://learn.microsoft.com/en-us/dax/generate-function-dax)|Returns a table with the Cartesian product between each row in *table1* and the table that results from evaluating *table2* in the context of the current row from *table1*.|
|[GENERATEALL](https://learn.microsoft.com/en-us/dax/generateall-function-dax)|Returns a table with the Cartesian product between each row in *table1* and the table that results from evaluating *table2* in the context of the current row from *table1*.|
|[GENERATESERIES](https://learn.microsoft.com/en-us/dax/generateseries-function)|Returns a single column table containing the values of an arithmetic series.|
|[GROUPBY](https://learn.microsoft.com/en-us/dax/groupby-function-dax)|Similar to the SUMMARIZE function, GROUPBY does not do an implicit CALCULATE for any extension columns that it adds.|
|[IGNORE](https://learn.microsoft.com/en-us/dax/ignore-function-dax)|Modifies SUMMARIZECOLUMNS by omitting specific expressions from the BLANK/NULL evaluation.|
|[INTERSECT](https://learn.microsoft.com/en-us/dax/intersect-function-dax)|Returns the row intersection of two tables, retaining duplicates.|
|[NATURALINNERJOIN](https://learn.microsoft.com/en-us/dax/naturalinnerjoin-function-dax)|Performs an inner join of a table with another table.|
|[NATURALLEFTOUTERJOIN](https://learn.microsoft.com/en-us/dax/naturalleftouterjoin-function-dax)|Performs a join of the LeftTable with the RightTable.|
|[ROLLUP](https://learn.microsoft.com/en-us/dax/rollup-function-dax)|Modifies the behavior of SUMMARIZE by adding rollup rows to the result on columns defined by the groupBy\_columnName parameter.|
|[ROLLUPADDISSUBTOTAL](https://learn.microsoft.com/en-us/dax/rollupaddissubtotal-function-dax)|Modifies the behavior of SUMMARIZECOLUMNS by adding rollup/subtotal rows to the result based on the groupBy\_columnName columns.|
|[ROLLUPISSUBTOTAL](https://learn.microsoft.com/en-us/dax/rollupissubtotal-function-dax)|Pairs rollup groups with the column added by ROLLUPADDISSUBTOTAL within an ADDMISSINGITEMS expression.|
|[ROLLUPGROUP](https://learn.microsoft.com/en-us/dax/rollupgroup-function-dax)|Modifies the behavior of SUMMARIZE and SUMMARIZECOLUMNS by adding rollup rows to the result on columns defined by the the groupBy\_columnName parameter.|
|[ROW](https://learn.microsoft.com/en-us/dax/row-function-dax)|Returns a table with a single row containing values that result from the expressions given to each column.|
|[SELECTCOLUMNS](https://learn.microsoft.com/en-us/dax/selectcolumns-function-dax)|Adds calculated columns to the given table or table expression.|
|[SUBSTITUTEWITHINDEX](https://learn.microsoft.com/en-us/dax/substitutewithindex-function-dax)|Returns a table which represents a left semijoin of the two tables supplied as arguments.|
|[SUMMARIZE](https://learn.microsoft.com/en-us/dax/summarize-function-dax)|Returns a summary table for the requested totals over a set of groups.|
|[SUMMARIZECOLUMNS](https://learn.microsoft.com/en-us/dax/summarizecolumns-function-dax)|Returns a summary table over a set of groups.|
|[Table Constructor](https://learn.microsoft.com/en-us/dax/table-constructor)|Returns a table of one or more columns.|
|[TOPN](https://learn.microsoft.com/en-us/dax/topn-function-dax)|Returns the top N rows of the specified table.|
|[TREATAS](https://learn.microsoft.com/en-us/dax/treatas-function)|Applies the result of a table expression as filters to columns from an unrelated table.|
|[UNION](https://learn.microsoft.com/en-us/dax/union-function-dax)|Creates a union (join) table from a pair of tables.|
|[VALUES](https://learn.microsoft.com/en-us/dax/values-function-dax)|Returns a one-column table that contains the distinct values from the specified table or column.|


# **Text functions**


|**Function**|**Description**|
| :- | :- |
|[COMBINEVALUES](https://learn.microsoft.com/en-us/dax/combinevalues-function-dax)|Joins two or more text strings into one text string.|
|[CONCATENATE](https://learn.microsoft.com/en-us/dax/concatenate-function-dax)|Joins two text strings into one text string.|
|[CONCATENATEX](https://learn.microsoft.com/en-us/dax/concatenatex-function-dax)|Concatenates the result of an expression evaluated for each row in a table.|
|[EXACT](https://learn.microsoft.com/en-us/dax/exact-function-dax)|Compares two text strings and returns TRUE if they are exactly the same, FALSE otherwise.|
|[FIND](https://learn.microsoft.com/en-us/dax/find-function-dax)|Returns the starting position of one text string within another text string.|
|[FIXED](https://learn.microsoft.com/en-us/dax/fixed-function-dax)|Rounds a number to the specified number of decimals and returns the result as text.|
|[FORMAT](https://learn.microsoft.com/en-us/dax/format-function-dax)|Converts a value to text according to the specified format.|
|[LEFT](https://learn.microsoft.com/en-us/dax/left-function-dax)|Returns the specified number of characters from the start of a text string.|
|[LEN](https://learn.microsoft.com/en-us/dax/len-function-dax)|Returns the number of characters in a text string.|
|[LOWER](https://learn.microsoft.com/en-us/dax/lower-function-dax)|Converts all letters in a text string to lowercase.|
|[MID](https://learn.microsoft.com/en-us/dax/mid-function-dax)|Returns a string of characters from the middle of a text string, given a starting position and length.|
|[REPLACE](https://learn.microsoft.com/en-us/dax/replace-function-dax)|REPLACE replaces part of a text string, based on the number of characters you specify, with a different text string.|
|[REPT](https://learn.microsoft.com/en-us/dax/rept-function-dax)|Repeats text a given number of times.|
|[RIGHT](https://learn.microsoft.com/en-us/dax/right-function-dax)|RIGHT returns the last character or characters in a text string, based on the number of characters you specify.|
|[SEARCH](https://learn.microsoft.com/en-us/dax/search-function-dax)|Returns the number of the character at which a specific character or text string is first found, reading left to right.|
|[SUBSTITUTE](https://learn.microsoft.com/en-us/dax/substitute-function-dax)|Replaces existing text with new text in a text string.|
|[TRIM](https://learn.microsoft.com/en-us/dax/trim-function-dax)|Removes all spaces from text except for single spaces between words.|
|[UNICHAR](https://learn.microsoft.com/en-us/dax/unichar-function-dax)|Returns the Unicode character referenced by the numeric value.|
|[UNICODE](https://learn.microsoft.com/en-us/dax/unicode-function-dax)|Returns the numeric code corresponding to the first character of the text string.|
|[UPPER](https://learn.microsoft.com/en-us/dax/upper-function-dax)|Converts a text string to all uppercase letters.|
|[VALUE](https://learn.microsoft.com/en-us/dax/value-function-dax)|Converts a text string that represents a number to a number.|

# **Time intelligence functions**


|**Function**|**Description**|
| :- | :- |
|[CLOSINGBALANCEMONTH](https://learn.microsoft.com/en-us/dax/closingbalancemonth-function-dax)|Evaluates the expression at the last date of the month in the current context.|
|[CLOSINGBALANCEQUARTER](https://learn.microsoft.com/en-us/dax/closingbalancequarter-function-dax)|Evaluates the expression at the last date of the quarter in the current context.|
|[CLOSINGBALANCEYEAR](https://learn.microsoft.com/en-us/dax/closingbalanceyear-function-dax)|Evaluates the expression at the last date of the year in the current context.|
|[DATEADD](https://learn.microsoft.com/en-us/dax/dateadd-function-dax)|Returns a table that contains a column of dates, shifted either forward or backward in time by the specified number of intervals from the dates in the current context.|
|[DATESBETWEEN](https://learn.microsoft.com/en-us/dax/datesbetween-function-dax)|Returns a table that contains a column of dates that begins with a specified start date and continues until a specified end date.|
|[DATESINPERIOD](https://learn.microsoft.com/en-us/dax/datesinperiod-function-dax)|Returns a table that contains a column of dates that begins with a specified start date and continues for the specified number and type of date intervals.|
|[DATESMTD](https://learn.microsoft.com/en-us/dax/datesmtd-function-dax)|Returns a table that contains a column of the dates for the month to date, in the current context.|
|[DATESQTD](https://learn.microsoft.com/en-us/dax/datesqtd-function-dax)|Returns a table that contains a column of the dates for the quarter to date, in the current context.|
|[DATESYTD](https://learn.microsoft.com/en-us/dax/datesytd-function-dax)|Returns a table that contains a column of the dates for the year to date, in the current context.|
|[ENDOFMONTH](https://learn.microsoft.com/en-us/dax/endofmonth-function-dax)|Returns the last date of the month in the current context for the specified column of dates.|
|[ENDOFQUARTER](https://learn.microsoft.com/en-us/dax/endofquarter-function-dax)|Returns the last date of the quarter in the current context for the specified column of dates.|
|[ENDOFYEAR](https://learn.microsoft.com/en-us/dax/endofyear-function-dax)|Returns the last date of the year in the current context for the specified column of dates.|
|[FIRSTDATE](https://learn.microsoft.com/en-us/dax/firstdate-function-dax)|Returns the first date in the current context for the specified column of dates.|
|[FIRSTNONBLANK](https://learn.microsoft.com/en-us/dax/firstnonblank-function-dax)|Returns the first value in the column, column, filtered by the current context, where the expression is not blank|
|[LASTDATE](https://learn.microsoft.com/en-us/dax/lastdate-function-dax)|Returns the last date in the current context for the specified column of dates.|
|[LASTNONBLANK](https://learn.microsoft.com/en-us/dax/lastnonblank-function-dax)|Returns the last value in the column, column, filtered by the current context, where the expression is not blank.|
|[NEXTDAY](https://learn.microsoft.com/en-us/dax/nextday-function-dax)|Returns a table that contains a column of all dates from the next day, based on the first date specified in the dates column in the current context.|
|[NEXTMONTH](https://learn.microsoft.com/en-us/dax/nextmonth-function-dax)|Returns a table that contains a column of all dates from the next month, based on the first date in the dates column in the current context.|
|[NEXTQUARTER](https://learn.microsoft.com/en-us/dax/nextquarter-function-dax)|Returns a table that contains a column of all dates in the next quarter, based on the first date specified in the dates column, in the current context.|
|[NEXTYEAR](https://learn.microsoft.com/en-us/dax/nextyear-function-dax)|Returns a table that contains a column of all dates in the next year, based on the first date in the dates column, in the current context.|
|[OPENINGBALANCEMONTH](https://learn.microsoft.com/en-us/dax/openingbalancemonth-function-dax)|Evaluates the expression at the first date of the month in the current context.|
|[OPENINGBALANCEQUARTER](https://learn.microsoft.com/en-us/dax/openingbalancequarter-function-dax)|Evaluates the expression at the first date of the quarter, in the current context.|
|[OPENINGBALANCEYEAR](https://learn.microsoft.com/en-us/dax/openingbalanceyear-function-dax)|Evaluates the expression at the first date of the year in the current context.|
|[PARALLELPERIOD](https://learn.microsoft.com/en-us/dax/parallelperiod-function-dax)|Returns a table that contains a column of dates that represents a period parallel to the dates in the specified dates column, in the current context, with the dates shifted a number of intervals either forward in time or back in time.|
|[PREVIOUSDAY](https://learn.microsoft.com/en-us/dax/previousday-function-dax)|Returns a table that contains a column of all dates representing the day that is previous to the first date in the dates column, in the current context.|
|[PREVIOUSMONTH](https://learn.microsoft.com/en-us/dax/previousmonth-function-dax)|Returns a table that contains a column of all dates from the previous month, based on the first date in the dates column, in the current context.|
|[PREVIOUSQUARTER](https://learn.microsoft.com/en-us/dax/previousquarter-function-dax)|Returns a table that contains a column of all dates from the previous quarter, based on the first date in the dates column, in the current context.|
|[PREVIOUSYEAR](https://learn.microsoft.com/en-us/dax/previousyear-function-dax)|Returns a table that contains a column of all dates from the previous year, given the last date in the dates column, in the current context.|
|[SAMEPERIODLASTYEAR](https://learn.microsoft.com/en-us/dax/sameperiodlastyear-function-dax)|Returns a table that contains a column of dates shifted one year back in time from the dates in the specified dates column, in the current context.|
|[STARTOFMONTH](https://learn.microsoft.com/en-us/dax/startofmonth-function-dax)|Returns the first date of the month in the current context for the specified column of dates.|
|[STARTOFQUARTER](https://learn.microsoft.com/en-us/dax/startofquarter-function-dax)|Returns the first date of the quarter in the current context for the specified column of dates.|
|[STARTOFYEAR](https://learn.microsoft.com/en-us/dax/startofyear-function-dax)|Returns the first date of the year in the current context for the specified column of dates.|
|[TOTALMTD](https://learn.microsoft.com/en-us/dax/totalmtd-function-dax)|Evaluates the value of the expression for the month to date, in the current context.|
|[TOTALQTD](https://learn.microsoft.com/en-us/dax/totalqtd-function-dax)|Evaluates the value of the expression for the dates in the quarter to date, in the current context.|
|[TOTALYTD](https://learn.microsoft.com/en-us/dax/totalytd-function-dax)|Evaluates the year-to-date value of the expression in the current context.|

# **DAX Statements**
#

|**Statement**|**Description**|
| :- | :- |
|[DEFINE](https://learn.microsoft.com/en-us/dax/define-statement-dax)|(Keyword) Introduces one or more entity definitions that can be applied to one or more EVALUATE statements.|
|[EVALUATE](https://learn.microsoft.com/en-us/dax/evaluate-statement-dax)|(Keyword) Introduces a statement containing a table expression required to execute a DAX query.|
|[MEASURE](https://learn.microsoft.com/en-us/dax/measure-statement-dax)|(Keyword) Introduces a measure definition that can be used in one or more EVALUATE statements in a query.|
|[ORDER BY](https://learn.microsoft.com/en-us/dax/orderby-statement-dax)|(Keyword) Introduces a statement that defines the sort order of query results returned by an EVALUATE statement.|
|[START AT](https://learn.microsoft.com/en-us/dax/startat-statement-dax)|(Keyword) Introduces a statement that defines the starting value at which the query results of an ORDER BY statement are returned.|
|[VAR](https://learn.microsoft.com/en-us/dax/var-dax)|(Keyword) Stores the result of an expression as a named variable, which can then be passed as an argument to other measure expressions.|
#
#
#
#
#
# **DAX glossary**
**Analytic query**

Power BI visuals query a data model by using an *analytic query*. An analytic query strives to reduce potentially large data volumes and model complexities using three distinct phases: Filter, group and summarize. An analytic query is created automatically when fields are assigned to the wells of report visuals. Report authors can control the behavior of field assignments by renaming fields, modifying the summarization technique, or disabling summarization to achieve grouping. At report design time, filters can be added to the report, a report page, or a visual. In reading view, filters can be modified in the **Filters** pane, or by interactions with slicers and other visuals (cross-filtering).

**BLANK**

DAX defines the absence of a value as BLANK. It's the equivalent of SQL NULL, but it doesn't behave exactly the same. It's more closely aligned to Excel and how it defines an empty cell. BLANK is evaluated as zero or an empty string when combined with other operations. For example, BLANK + 20 = 20. Always use capital letters; the plural is BLANKs, with a lowercase "s".

**Calculated column**

A model calculation used to add a column to a tabular model by writing a DAX formula. The formula must return a scalar value, and it's evaluated for each row in the table. A calculated column can be added to an Import or DirectQuery storage mode table.

**Calculated measure**

In tabular modeling, there's no such concept as a *calculated measure*. Use *measure* instead. The word *calculated* is used to describe calculated tables and calculated columns. It distinguishes them from tables and columns that originate from Power Query. Power Query doesn't have the concept of a measure.

**Calculated table**

A model calculation used to add a table to a tabular model by writing a DAX formula. The formula must return a table object. It results in a table that uses Import storage mode.

**Calculation**

A deliberate process that transforms one or more inputs into one or more results. In a tabular data model, a calculation can be a model object; either a calculated table, calculated column, or measure.

**Context**

Describes the environment in which a DAX formula is evaluated. There are two types of context: *Row context* and *filter context*. Row context represents the "current row", and is used to evaluate calculated column formulas and expressions used by table iterators. Filter context is used to evaluate measures, and it represents filters applied directly to model columns and filters propagated by model relationships.

**DAX**

Data Analysis Expressions (DAX) language is a formula language for Power Pivot in Excel, Power BI, Azure Analysis Services, and tabular modeling in SQL Server Analysis Services. You can also use DAX to add data model calculations and define row-level security (RLS) rules.

**Dynamic security**

When row-level security (RLS) rules are enforced by using the identity of the report user. Rules filter model tables by using the user's account name, which can be done with the USERNAME or USERPRINCIPALNAME functions. See [Row-level security](https://learn.microsoft.com/en-us/dax/dax-glossary#row-level-security).

**Expression**

A unit of DAX logic that's evaluated and returns a result. Expressions can declare variables in which case they're assigned a sub-expression and must include a RETURN statement that outputs a final expression. Expressions are constructed by using model objects (tables, columns, or measures), functions, operators, or constants.

**Field**

Data model resource presented in the **Fields** pane. Fields are used to configure report filters and visuals. Fields consist of model columns, hierarchy levels, and measures.

**Formula**

One or more DAX expressions used to define a model calculation. Inner expressions are called sub-expressions. Plural is *formulas*.

**Function**

DAX functions have arguments that allow passing in parameters. Formulas can use many function calls, possibly nesting functions within other functions. In a formula, function names must be followed by parentheses. Within the parentheses, parameters are passed in.

**Implicit measure**

An automatically generated calculation achieved by configuring a Power BI visual to summarize column values. **Numeric** columns support the greatest range of summarization, including: Sum, Average, Minimum, Maximum, Count (Distinct), Count, Standard deviation, Variance, or Median. Columns of other data types can be summarized, too. **Text** columns can be summarized by using: First (alphabetically), Last (alphabetically), Count (Distinct), or Count. **Date** columns can be summarized by using: Earliest, Latest, Count (Distinct), or Count. **Boolean** columns can be summarized by using: Count (Distinct), or Count.

**Iterator function**

A DAX function that enumerates all rows of a given table and evaluate a given expression for each row. It provides flexibility and control over how model calculations summarize data.

**MDX**

Multidimensional Expressions (MDX) language is a formula language for SQL Server Analysis Services multidimensional models (also known as *cubes*). MDX can be used to query tabular models, however it can't define implicit measures. It can only query measures that are already defined in the model.

**Measure**

A calculation that achieves summarization. Measures are either [*implicit*](https://learn.microsoft.com/en-us/dax/dax-glossary#implicit-measure) or *explicit*. An explicit measure is a calculation added to a tabular data model by writing a DAX formula. A measure formula must return a scalar value. In the **Fields** pane, explicit measures are adorned with a calculator icon. Explicit measures are required when the model is queried by using Multidimensional Expressions (MDX), as is the case when using Analyze in Excel. An explicit measure is commonly just called a measure.

**Measure group**

A model table that contains at least one measure, and has no hierarchies or visible columns. In the **Fields** pane, each measure group is adorned with a multi-calculator icon. Measure groups are listed together at the top of the **Fields** pane, and sorted alphabetically by name.

**Model calculation**

A named formula that's used to add a calculated table, calculated column, or measure to a tabular data model. Its structure is <NAME> = <FORMULA>. Most calculations are added by data modelers in Power BI Desktop, but measures can also be added to a live connection report. See [Report measures](https://learn.microsoft.com/en-us/dax/dax-glossary#report-measures).

**Quick measures**

A feature in Power BI Desktop that eliminates the need to write DAX formulas for commonly defined measures. Quick measures include average per category, rank, and difference from baseline.

**Report measures**

Also called *report-level measures*. They're added to a live connection report in Power BI Desktop by writing a DAX formula, but only for connections to Power BI models or Analysis Services tabular models.

**Row-level security**

Also called *RLS*. Design technique to restrict access to subsets of data for specific users. In a tabular model, it's achieved by creating model roles. Roles have rules, which are DAX expressions to filter table rows.

**Scalar**

In DAX, a scalar is a single value. A scalar can be of any data type: Decimal, Integer, DateTime, String, Currency, Boolean. A scalar value can be the result of an expression calculated from multiple values. For example, an aggregation function such as MAX() returns a single maximum value from a set of values from which to evaluate.

**Summarization**

An operation applied to the values of a column. See [measure](https://learn.microsoft.com/en-us/dax/dax-glossary#measure).

**Time intelligence**

Time intelligence relates to calculations over time, like year-to-date (YTD).

**Time intelligence function**

DAX includes many time intelligence functions. Each time intelligence function achieves its result by modifying the filter context for date filters. Example functions: TOTALYTD and SAMEPERIODLASTYEAR.

**Value, values**

Data to be visualized.


**What-if parameter**

A Power BI Desktop feature that provides the ability to accept user input through slicers. Each parameter creates a single-column calculated table and a measure that returns a single-selected value. The measure can be used in model calculations to respond to the user's input.
# **DAX operators**
## **Types of operators**
There are four different types of calculation operators: arithmetic, comparison, text concatenation, and logical.
### **Arithmetic operators**



When several operators are combined in a single expression, the operations are ordered according to the following table, from the lowest to the highest precedence level number. If the operators have equal precedence value, they are ordered from left to right. For example:

- If an expression contains both a sum and a comparison, the sum is executed before the comparison.
- If an expression contains both a multiplication and division operator, they are evaluated in the order that they appear in the expression, from left to right.

|**PRIORITY LEVEL**|**OPERATOR**|**DESCRIPTION**|
| :- | :- | :- |
|1|()|Parentheses – grouping|
|1|F()|Scalar functions|
|1|[IN](https://dax.guide/op/in/)|Inclusive [OR](https://dax.guide/or/) list|
|2|[^](https://dax.guide/op/exponentiation/)|Exponentiation|
|3|+, –|Sign – unary plus/minus (-1)|
|4|[*](https://dax.guide/op/multiplication/), [/](https://dax.guide/op/division/)|Multiplication, division|
|5|[+](https://dax.guide/op/addition/), [–](https://dax.guide/op/subtraction/)|Addition, subtraction|
|6|[&](https://dax.guide/op/concatenation/)|Text concatenation|
|7|[=](https://dax.guide/op/equal-to/), [==](https://dax.guide/op/strictly-equal-to/), [<>](https://dax.guide/op/not-equal-to/), [<](https://dax.guide/op/less-than/), [>](https://dax.guide/op/greater-than/), [<=](https://dax.guide/op/less-than-or-equal-to/), [>=](https://dax.guide/op/greater-than-or-equal-to/)|Comparison operators|
|8|[NOT](https://dax.guide/op/not/)|Logical negation|
|9|[&&](https://dax.guide/op/and/)|Logical [AND](https://dax.guide/and/)|
|10|[||](https://dax.guide/op/or/)|Logical [OR](https://dax.guide/or/)|

.



DAX parameter-naming conventions

Parameter names are standardized in DAX reference to facilitate the usage and understanding of the functions.


**Parameter names**

|**Term**|**Definition**|
| :- | :- |
|expression|Any DAX expression that returns a single scalar value, where the expression is to be evaluated multiple times (for each row/context).|
|value|Any DAX expression that returns a single scalar value where the expression is to be evaluated exactly once before all other operations.|
|table|Any DAX expression that returns a table of data.|
|tableName|The name of an existing table using standard DAX syntax. It cannot be an expression.|
|columnName|The name of an existing column using standard DAX syntax, usually fully qualified. It cannot be an expression.|
|name|A string constant that will be used to provide the name of a new object.|
|order|An enumeration used to determine the sort order.|
|ties|An enumeration used to determine the handling of tie values.|
|type|An enumeration used to determine the data type for PathItem and PathItemReverse.|

### **Prefixing parameter names or using the prefix only**

|**Term**|**Definition**|
| :- | :- |
|prefixing|Parameter names may be further qualified with a prefix that is descriptive of how the argument is used and to avoid ambiguous reading of the parameters. For example:<br><br>Result\_ColumnName - Refers to an existing column used to get the result values in the LOOKUPVALUE() function.<br><br>Search\_ColumnName - Refers to an existing column used to search for a value in the LOOKUPVALUE() function.|
|omitting|Parameter names will be omitted if the prefix is clear enough to describe the parameter.<br><br>For example, instead of having the following syntax DATE (Year\_Value, Month\_Value, Day\_Value) it is clearer for the user to read DATE (Year, Month, Day); repeating three times the suffix value does not add anything to a better comprehension of the function and it clutters the reading unnecessarily.<br><br>However, if the prefixed parameter is Year\_columnName then the parameter name and the prefix will stay to make sure the user understands that the parameter requires a reference to an existing column of Years.|
###
