![ref1]
# **Parent and Child functions**

**PATH:**

1\. Use Case: Hierarchical Data Analysis

`   `Question: In a hierarchical data structure, the PATH function can be used to retrieve the complete path of each node. How can PATH be utilized to retrieve the path of a specific node in the hierarchy?

2\. Use Case: Navigating Parent-Child Relationships

`   `Question: How can the PATH function be used to navigate through a parent-child relationship and identify all the parents of a given node?

3\. Use Case: Building Tree-like Structures

`   `Question: When constructing a tree-like structure, how can the PATH function be used to generate a delimited text string that represents the path from the root node to each leaf node?

4\. Use Case: Filtering Data based on Path

`   `Question: In a dataset with hierarchical data, how can the PATHCONTAINS function be used to filter records based on whether a specific item exists within its path?

5\. Use Case: Determining Path Length

`   `Question: When analyzing a hierarchical structure, how can the PATHLENGTH function be used to determine the number of parents to a specific item in the path, including itself?









**PATHCONTAINS:**

1\. Use Case: Checking Ancestor-Child Relationship

`   `Question: How can the PATHCONTAINS function be used to check if a specific item exists within the path of another item, indicating an ancestor-child relationship?

2\. Use Case: Identifying Common Paths

`   `Question: In a dataset with hierarchical paths, how can the PATHCONTAINS function be utilized to identify common paths among different items?

3\. Use Case: Filtering Paths with Specific Item

`   `Question: How can the PATHCONTAINS function be used to filter a dataset and retrieve only the records where a specific item exists within their paths?

4\. Use Case: Validating Hierarchical Paths

`   `Question: In a hierarchical structure, how can the PATHCONTAINS function be utilized to validate if a given path is correct and contains all the necessary items?

5\. Use Case: Searching for Related Items

`   `Question: When exploring a hierarchical dataset, how can the PATHCONTAINS function be used to search for related items based on their path relationships?


**PATHITEM:**

1\. Use Case: Extracting Specific Item from Path

`   `Question: How can the PATHITEM function be used to extract a specific item from a delimited text string resulting from the evaluation of a PATH function?

2\. Use Case: Navigating Hierarchical Structures

`   `Question: When analyzing a hierarchical structure, how can the PATHITEM function be used to retrieve a particular item at a specific position from the path?

3\. Use Case: Indexing Nodes in a Path

`   `Question: How can the PATHITEM function be utilized to assign an index or position to each item in a delimited text string representing a path?

4\. Use Case: Building Custom Hierarchies

`   `Question: In scenarios where the existing hierarchy is not suitable, how can the PATHITEM function be used to build custom hierarchies by rearranging items within the path?

5\. Use Case: Validating Path Integrity

`   `Question: When working with hierarchical paths, how can the PATHITEM function be used to validate if a specific item exists at a particular position within the path?






**PATHLENGTH:**

1\. Use Case: Analyzing Depth of Hierarchy

`   `Question: How can the PATHLENGTH function be used to determine the number of parents to a specific item in a hierarchical structure, including itself?

2\. Use Case: Detecting Anomalies in Hierarchy

`   `Question: In a dataset with hierarchical data, how can the PATHLENGTH function be utilized to identify any unusual or unexpected variations in the depth of the hierarchy?

3\. Use Case: Sorting Hierarchy by Path Length

`   `Question: How can the PATHLENGTH function be used to sort a hierarchical dataset based on the length of the paths, from the shortest to the longest?

4\. Use Case: Grouping Data by Path Length

`   `Question: When analyzing a hierarchical structure, how can the PATHLENGTH function be used to group data based on the number of parents to a specific item in the path?

5\. Use Case: Identifying Depth of Tree-like Structures

`   `Question: In a tree-like structure, how can the PATHLENGTH function be utilized to determine the depth of each node and identify the level at which it exists in the tree?





# **Relationship functions**
#
**CROSSFILTER:**

1\. Use Case: Bidirectional Cross-Filtering

`   `Question: In a scenario where a bidirectional relationship exists between two tables, how can the CROSSFILTER function be used to specify the cross-filtering direction for a calculation?

2\. Use Case: Controlling Filter Propagation

`   `Question: When performing calculations involving related tables, how can the CROSSFILTER function be utilized to control how filters are propagated between the tables?

3\. Use Case: Cross-Filtering Behavior Modification

`   `Question: How does the CROSSFILTER function allow you to modify the default cross-filtering behavior between tables and specify a different direction for filtering?

4\. Use Case: Optimizing Query Performance

`   `Question: In a data model with multiple relationships, how can the CROSSFILTER function be used strategically to optimize query performance by controlling the direction of cross-filtering?

5\. Use Case: Resolving Ambiguous Filters

`   `Question: When encountering ambiguous filter contexts in a calculation involving related tables, how can the CROSSFILTER function be employed to explicitly define the desired cross-filtering direction?


**RELATED:**

1\. Use Case: Retrieving Related Information

`   `Question: How can the RELATED function be used to retrieve a value from another table that is related to the current table through a defined relationship?

2\. Use Case: Aggregating Data from Related Tables

`   `Question: In a scenario where data needs to be aggregated across related tables, how can the RELATED function be utilized to access and summarize information from those tables?

3\. Use Case: Accessing Parent-Child Relationships

`   `Question: When working with a parent-child relationship, how can the RELATED function be used to access the related parent or child records based on the current context?

4\. Use Case: Drill-Through Analysis

`   `Question: How can the RELATED function be employed to enable drill-through analysis, allowing users to navigate from one table to another based on the related values?

5\. Use Case: Dynamically Expanding Data

`   `Question: In a data model with hierarchies, how can the RELATED function be used to dynamically expand data by retrieving related information from higher levels of the hierarchy?








**RELATEDTABLE:**

1\. Use Case: Filtering Related Tables

`   `Question: How can the RELATEDTABLE function be used to evaluate a table expression in the context of the current row and retrieve a table of related records?

2\. Use Case: Aggregating Data from Related Tables

`   `Question: When performing calculations involving related tables, how can the RELATEDTABLE function be utilized to aggregate data from the related table based on the current context?

3\. Use Case: Calculating Conditional Sums

`   `Question: In a scenario where conditional sums need to be calculated based on related records, how can the RELATEDTABLE function be used to filter the related table and perform the necessary calculations?

4\. Use Case: Context Modification for Calculations

`   `Question: How does the RELATEDTABLE function modify the context in which a table expression is evaluated, and how can it be leveraged to perform calculations on related records?

5\. Use Case: Comparing Related Data

`   `Question: When comparing data across related tables, how can the RELATEDTABLE function be employed to retrieve and analyze the relevant records from the related table in the current context?

**USERELATIONSHIP:**

1\. Use Case: Overriding Default Relationships

`   `Question: How does the USERELATIONSHIP function allow you to override the default relationships in a data model and specify a different relationship for a specific calculation?

2\. Use Case: Multiple Relationships Between Tables

`   `Question: In a scenario where multiple relationships exist between two tables, how can the USERELATIONSHIP function be used to specify which relationship should be used for a particular calculation?

3\. Use Case: Filtering Data with Non-Active Relationships

`   `Question: How can the USERELATIONSHIP function be utilized to filter data using a relationship that is not the active relationship in the data model?

4\. Use Case: Customized Relationship Behavior

`   `Question: When performing calculations involving related tables, how can the USERELATIONSHIP function be employed to customize the behavior of the relationship and ensure accurate results?

5\. Use Case: Handling Ambiguous Relationships

`   `Question: In a scenario where there are ambiguous relationships between tables, how can the USERELATIONSHIP function be used to specify the desired relationship and resolve any ambiguity in the calculation?



#
# **Text functions**

**COMBINEVALUES:**

1\. Use Case: Merging First Name and Last Name

`   `Question: Which function can be used to join the first name and last name columns in a dataset into a single text string?

a) CONCATENATE

b) CONCATENATEX

c) COMBINEVALUES

d) REPT

2\. Use Case: Creating Full Address

`   `Question: In data analysis, if you want to combine the address line, city, state, and postal code columns to create a full address, which function would you use?

a) FORMAT

b) REPLACE

c) CONCATENATE

d) RIGHT

3\. Use Case: Repeating Text

`   `Question: Suppose you need to repeat a specific text string multiple times. Which function would you use?

a) MID

b) UPPER

c) REPT

d) SUBSTITUTE



4\. Use Case: Extracting Substring

`   `Question: If you want to extract a substring from a larger text string, given the starting position and length, which function would you use?

a) SEARCH

b) LEN

c) MID

d) REPLACE

5\. Use Case: Converting Text to Number

`   `Question: When working with text data that represents numeric values, which function can be used to convert the text string to an actual number?

a) VALUE

b) TRIM

c) UNICODE

d) LOWER

**CONCATENATE:**

1\. Use Case: Combining First Name and Last Name

`   `Question: Which function can be used to concatenate the first name and last name columns in a dataset into a single text string?

a) CONCATENATEX

b) COMBINEVALUES

c) CONCATENATE

d) REPLACE





2\. Use Case: Creating a Sentence

`   `Question: In data analysis, if you want to combine multiple text strings to form a complete sentence, which function would you use?

a) VALUE

b) FORMAT

c) CONCATENATE

d) SUBSTITUTE

3\. Use Case: Joining Text with Separator

`   `Question: Suppose you have a list of items and you want to join them into a single text string with a separator between each item. Which function would you use?

a) REPT

b) TRIM

c) CONCATENATE

d) SUBSTITUTE

4\. Use Case: Concatenating Columns in a Table

`   `Question: When working with a table, which function allows you to concatenate the values from multiple columns into a single column?

a) UPPER

b) CONCATENATEX

c) CONCATENATE

d) RIGHT

5\. Use Case: Combining Text and Numeric Values

`   `Question: If you have a text string and a numeric value that you want to combine into a single text string, which function would you use?

a) VALUE

b) CONCATENATE

c) REPLACE

d) UNICHAR

EXACT:

1\. Use Case: Comparing User Input

`   `Question: Which function is commonly used to compare two text strings for an exact match, such as when validating user input?

a) EXACT

b) SUBSTITUTE

c) REPLACE

d) UPPER

2\. Use Case: Checking Data Consistency

`   `Question: In data analysis, if you want to verify the consistency of text values across different columns or datasets, which function would you use?

a) VALUE

b) UPPER

c) EXACT

d) TRIM

3\. Use Case: Handling Case-Sensitive Comparisons

`   `Question: When comparing text strings and you want to consider case sensitivity, which function should you use?

a) LOWER

b) TRIM

c) EXACT

d) CONCATENATE

4\. Use Case: Validating Data Entry

`   `Question: In a data entry form, if you want to check whether the entered text exactly matches a predefined value, which function would you use?

a) EXACT

b) MID

c) SEARCH

d) LEN

5\. Use Case: Checking Data Integrity

`   `Question: Which function would you use to compare two text strings and determine if they are exactly the same, without any variations or differences?

a) REPLACE

b) UNICODE

c) EXACT

d) CONCATENATE

**FIND:**

1\. Use Case: Searching for Substrings

`   `Question: Which function is used to find the starting position of a specific substring within a text string?

a) REPLACE

b) MID

c) RIGHT

d) FIND

2\. Use Case: Extracting Text

`   `Question: In data manipulation, if you want to extract a specific portion of text from a longer string, which function would you use?

a) EXACT

b) SUBSTITUTE

c) TRIM

d) FIND

3\. Use Case: Checking Substring Existence

`   `Question: If you want to determine whether a particular substring exists within a text string, which function should you use?

a) UPPER

b) SEARCH

c) CONCATENATE

d) FIND

4\. Use Case: Text Positioning

`   `Question: Which function allows you to find the position of a specific character or substring within a text string, reading from left to right?a) LEFT

b) RIGHT

c) FIND

d) LEN

5\. Use Case: Counting Occurrences

`   `Question: In data analysis, if you want to count the number of times a specific substring appears within a text string, which function would you use?

a) REPLACE

b) REPT

c) FIND

d) VALUE

**FIXED:**

1\. Use Case: Formatting Numbers

`   `Question: Which function is used to round a number to a specified number of decimals and convert it to a text string?

a) CONCATENATE

b) VALUE

c) FIXED

d) SUBSTITUTE

2\. Use Case: Displaying Currency

`   `Question: If you want to format a numeric value as a currency with a specified number of decimals, which function would you use?

a) CONCATENATEX

b) TRIM

c) FIXED

d) SEARCH

3\. Use Case: Formatting Percentage

`   `Question: In financial reporting, if you need to display a number as a percentage with a specific number of decimals, which function should you use?

a) REPLACE

b) CONCATENATE

c) FIXED

d) EXACT

4\. Use Case: Displaying Large Numbers

`   `Question: Which function can be used to format very large numbers with a specific number of decimals and thousand separators?

a) VALUE

b) REPT

c) FIXED

d) UPPER

5\. Use Case: Text Alignment

`   `Question: In data visualization, if you want to align numeric values in a column to a specific width by adding leading spaces, which function would you use?

a) RIGHT

b) SUBSTITUTE

c) FIXED

d) SEARCH

**FORMAT:**

1\. Use Case: Date Formatting

`   `Question: Which function is used to convert a date value into a text string with a specified date format?

a) FORMAT

b) CONCATENATE

c) REPLACE

d) SEARCH

2\. Use Case: Custom Text Formatting

`   `Question: If you want to display a text value in a specific format, such as adding a prefix or suffix, which function should you use?

a) UPPER

b) CONCATENATE

c) FORMAT

d) TRIM

3\. Use Case: Numeric Formatting with Thousand Separators

`   `Question: In financial reports, if you want to display a large numeric value with thousand separators, which function would you use?

a) SEARCH

b) FORMAT

c) EXACT

d) REPLACE

4\. Use Case: Decimal Precision

`   `Question: Which function allows you to specify the number of decimal places for a numeric value in a formatted text string?

a) TRIM

b) FORMAT

c) SUBSTITUTE

d) RIGHT

5\. Use Case: Conditional Formatting

`   `Question: If you want to format a value based on a specific condition, such as highlighting negative numbers in red, which function would be useful?

a) REPLACE

b) UPPER

c) FORMAT

d) CONCATENATE


**LEFT:**

1\. Use Case: Extracting Substring

`   `Question: Which function is used to extract a specified number of characters from the beginning of a text string?

a) LEFT

b) CONCATENATE

c) REPLACE

d) SEARCH

2\. Use Case: Getting First Name

`   `Question: If you have a full name stored in a text string and you want to extract the first name, which function would you use?

a) REPLACE

b) UPPER

c) LEFT

d) CONCATENATE

3\. Use Case: Truncating Text

`   `Question: You want to truncate a long text string to a certain number of characters. Which function would you use?

a) SEARCH

b) LEFT

c) FORMAT

d) EXACT

4\. Use Case: Extracting File Extension

`   `Question: If you have a file name stored in a text string and you want to extract the file extension, which function would you use?

a) REPLACE

b) LEFT

c) SUBSTITUTE

d) CONCATENATE

5\. Use Case: Getting Country Code

`   `Question: If you have a phone number stored in a text string and you want to extract the country code, which function would you use?

a) LEFT

b) UPPER

c) REPLACE

d) CONCATENATE

**LEN:**

1\. Use Case: Checking Text Length

`   `Question: Which function is used to determine the number of characters in a text string?

a) LEFT

b) CONCATENATE

c) REPLACE

d) LEN

2\. Use Case: Validating Input Length

`   `Question: If you want to validate that a user input has a specific length, which function would you use?

a) CONCATENATE

b) LEN

c) EXACT

d) TRIM





3\. Use Case: Filtering Text Length

`   `Question: You want to filter a dataset based on the length of a text column. Which function would you use in the filter expression?

a) SEARCH

b) VALUE

c) LEFT

d) LEN

4\. Use Case: Counting Characters

`   `Question: If you have a text column in a table and you want to count the number of characters in each row, which function would you use in a calculated column?

a) TRIM

b) REPLACE

c) RIGHT

d) LEN

5\. Use Case: Trimming Text Length

`   `Question: If you want to remove leading and trailing spaces from a text string, which function would you use to get the length of the trimmed string?

a) LEN

b) TRIM

c) REPLACE

d) UPPER

**LOWER:**

1\. Use Case: Standardizing Text Case

`   `Question: Which function can be used to convert all letters in a text string to lowercase?

a) UPPER

b) LOWER

c) PROPER

d) INITCAP

2\. Use Case: Case-Insensitive Text Comparison

`   `Question: When comparing two text strings without considering their case, which function would you use?

a) EXACT

b) UPPER

c) LOWER

d) CONCATENATE

3\. Use Case: Formatting Text for Consistency

`   `Question: If you want to ensure that all text in a column is in lowercase, which function would you use in a calculated column?

a) REPLACE

b) TRIM

c) LOWER

d) UPPER

4\. Use Case: Transforming User Input

`   `Question: When processing user input, which function would you use to convert the input to lowercase before further processing?

a) FORMAT

b) LEN

c) LOWER

d) VALUE

5\. Use Case: Searching for Text

`   `Question: If you want to find a specific text string within a larger text, but without considering the case, which function would you use?

a) FIND

b) SEARCH

c) REPLACE

d) LOWER


**MID:**

1\. Use Case: Extracting Substrings

`   `Question: Which function allows you to extract a substring from a text string based on a specified starting position and length?

a) LEFT

b) RIGHT

c) MID

d) REPLACE

2\. Use Case: Extracting Middle Name

`   `Question: You have a column with full names in the format "First Middle Last". Which function would you use to extract the middle name?

a) MID

b) LEN

c) SUBSTITUTE

d) CONCATENATE

3\. Use Case: Parsing Textual Data

`   `Question: You have a text string that contains multiple data elements separated by a delimiter. Which function would you use to extract a specific element?

a) MID

b) UPPER

c) SEARCH

d) VALUE

4\. Use Case: Extracting Date Components

`   `Question: You have a text string representing a date in the format "MM/DD/YYYY". Which function would you use to extract the month component?

a) LEFT

b) RIGHT

c) MID

d) FIND

5\. Use Case: Dynamic Text Manipulation

`   `Question: You want to dynamically manipulate a text string based on a variable length. Which function would you use to achieve this?

a) REPLACE

b) TRIM

c) MID

d) CONCATENATE

**REPLACE:**

1\. Use Case: Replacing Characters

`   `Question: Which function allows you to replace a specific number of characters in a text string with another text string?

a) REPLACE

b) CONCATENATE

c) SUBSTITUTE

d) TRIM

2\. Use Case: Cleaning Data

`   `Question: You have a column with phone numbers that include dashes, and you want to remove the dashes. Which function would you use?

a) REPLACE

b) UPPER

c) SEARCH

d) VALUE

3\. Use Case: Masking Sensitive Data

`   `Question: You need to mask sensitive data, such as credit card numbers, by replacing all but the last four digits with "X". Which function would you use?

a) REPLACE

b) MID

c) LEN

d) LEFT

4\. Use Case: Removing Unwanted Characters

`   `Question: You have a text string with special characters that you want to remove. Which function would you use?

a) REPLACE

b) TRIM

c) RIGHT

d) LOWER

5\. Use Case: Find and Replace

`   `Question: You want to replace all occurrences of a specific word in a text string with another word. Which function would you use?

a) REPLACE

b) CONCATENATE

c) MID

d) SEARCH

**CONCATENATE:**

1\. Use Case: Combining First Name and Last Name

`   `Question: You have two columns, "First Name" and "Last Name," and you want to create a single column that contains the full name. Which function would you use?

a) CONCATENATE

b) REPLACE

c) UPPER

d) LEFT

2\. Use Case: Creating a Unique Identifier

`   `Question: You want to create a unique identifier by combining the values from multiple columns. Which function would you use?

a) CONCATENATE

b) RIGHT

c) FIND

d) LOWER

3\. Use Case: Creating a Concatenated List

`   `Question: You have a column with product names, and you want to create a single cell that contains all the product names separated by commas. Which function would you use?

a) CONCATENATE

b) MID

c) SEARCH

d) TRIM

4\. Use Case: Building a Dynamic Text String

`   `Question: You want to create a text string that includes both static text and the values from specific cells. Which function would you use?

a) CONCATENATE

b) UPPER

c) VALUE

d) SUBSTITUTE

5\. Use Case: Creating a File Path

`   `Question: You have separate columns for the folder path and the file name, and you want to combine them to create a complete file path. Which function would you use?

a) CONCATENATE

b) REPLACE

c) LEN

d) LEFT

**EXACT:**

1\. Use Case: Comparing Email Addresses

`   `Question: You have two columns containing email addresses, and you want to compare them to check if they are exactly the same. Which function would you use?

a) EXACT

b) REPLACE

c) UPPER

d) LEFT

2\. Use Case: Checking for Case Sensitivity

`   `Question: You want to compare two text strings and determine if they are exactly the same, taking case sensitivity into account. Which function would you use?

a) EXACT

b) RIGHT

c) FIND

d) LOWER

3\. Use Case: Validating User Input

`   `Question: You have a cell where users input a specific value, and you want to check if it matches the expected value exactly. Which function would you use?

a) EXACT

b) MID

c) SEARCH

d) TRIM

4\. Use Case: Verifying Passwords

`   `Question: You have two columns containing passwords, and you want to check if they match exactly to validate the user's input. Which function would you use?

a) EXACT

b) UPPER

c) VALUE

d) SUBSTITUTE

5\. Use Case: Identifying Exact Matches

`   `Question: You have a list of product codes, and you want to find the exact match for a specific code. Which function would you use?

a) EXACT

b) REPLACE

c) LEN

d) LEFT


**REPLACE:**

1\. Use Case: Replacing Substrings

`   `Question: You need to replace a specific substring within a text string with a different substring. Which function would you use?

a) REPLACE

b) CONCATENATE

c) LEFT

d) VALUE

2\. Use Case: Removing Unwanted Characters

`   `Question: You want to remove certain characters from a text string. Which function would you use?

a) REPLACE

b) FIND

c) UPPER

d) TRIM

3\. Use Case: Swapping Characters

`   `Question: You want to swap two characters within a text string. Which function would you use?

a) REPLACE

b) MID

c) EXACT

d) LOWER

4\. Use Case: Removing Spaces

`   `Question: You want to remove all spaces from a text string. Which function would you use?

a) REPLACE

b) RIGHT

c) SUBSTITUTE

d) SEARCH

5\. Use Case: Replacing Multiple Occurrences

`   `Question: You want to replace all occurrences of a specific substring within a text string. Which function would you use?

a) REPLACE

b) CONCATENATE

c) LEN

d) UNICHAR

**REPT:**

1\. Use Case: Repeating Text

`   `Question: You want to repeat a specific text multiple times. Which function would you use?

a) REPT

b) CONCATENATE

c) FIND

d) VALUE

2\. Use Case: Creating Duplicated Values

`   `Question: You want to create a series of duplicate values for a specific text. Which function would you use?

a) REPT

b) LEFT

c) REPLACE

d) UPPER

3\. Use Case: Generating Placeholder Text

`   `Question: You want to generate a placeholder text for testing purposes. Which function would you use?

a) REPT

b) MID

c) EXACT

d) LOWER

4\. Use Case: Building Repeated Patterns

`   `Question: You want to create a pattern by repeating a specific text in a specific sequence. Which function would you use?

a) REPT

b) RIGHT

c) SUBSTITUTE

d) SEARCH

5\. Use Case: Creating Text Art

`   `Question: You want to generate a graphical representation of a text by repeating specific characters. Which function would you use?

a) REPT

b) CONCATENATE

c) LEN

d) UNICHAR

**RIGHT:**

1\. Use Case: Extracting Last Characters

`   `Question: You want to extract the last 3 characters from a text string. Which function would you use?

a) RIGHT

b) MID

c) LEFT

d) REPLACE

2\. Use Case: Formatting Phone Numbers

`   `Question: You want to format a phone number by keeping only the last 4 digits. Which function would you use?

a) RIGHT

b) TRIM

c) UPPER

d) CONCATENATE

3\. Use Case: Extracting File Extensions

`   `Question: You want to extract the file extension from a file name. Which function would you use?

a) RIGHT

b) SEARCH

c) SUBSTITUTE

d) LOWER

4\. Use Case: Extracting Suffixes

`   `Question: You want to extract the suffix (e.g., "Jr.", "Sr.", "III") from a person's name. Which function would you use?

a) RIGHT

b) UPPER

c) FIND

d) VALUE

5\. Use Case: Displaying Last Updated Dates

`   `Question: You want to display the last updated dates for a list of files. Which function would you use?

a) RIGHT

b) REPLACE

c) TODAY

d) TEXT

**SEARCH:**

1\. Use Case: Finding Substrings

`   `Question: You want to find the position of the substring "apple" within a text string. Which function would you use?

a) SEARCH

b) REPLACE

c) CONCATENATE

d) EXACT

2\. Use Case: Case-Insensitive Search

`   `Question: You want to perform a case-insensitive search for a specific word in a text string. Which function would you use?

a) SEARCH

b) UPPER

c) LOWER

d) TRIM

3\. Use Case: Finding Character Occurrences

`   `Question: You want to count the number of times a specific character appears in a text string. Which function would you use?

a) SEARCH

b) MID

c) LEN

d) SUBSTITUTE

4\. Use Case: Searching with Wildcards

`   `Question: You want to search for text patterns using wildcards, such as finding words that start with "car". Which function would you use?

a) SEARCH

b) RIGHT

c) LEFT

d) FIND

5\. Use Case: Searching within a Range

`   `Question: You want to find the first occurrence of a specific value within a range of cells. Which function would you use?

a) SEARCH

b) VLOOKUP

c) MATCH

d) INDEX


**SUBSTITUTE:**

1\. Use Case: Replacing Text

`   `Question: You want to replace the word "blue" with "red" in a text string. Which function would you use?

a) SUBSTITUTE

b) CONCATENATE

c) REPT

d) UPPER

2\. Use Case: Removing Unwanted Characters

`   `Question: You want to remove all the spaces from a text string. Which function would you use?

a) SUBSTITUTE

b) LEFT

c) TRIM

d) REPT

3\. Use Case: Multiple Replacements

`   `Question: You want to replace multiple occurrences of a specific word in a text string. Which function would you use?

a) SUBSTITUTE

b) REPLACE

c) MID

d) SEARCH

4\. Use Case: Case-Sensitive Replacement

`   `Question: You want to replace the word "apple" with "orange" in a text string, considering the case sensitivity. Which function would you use?

a) SUBSTITUTE

b) EXACT

c) LOWER

d) UPPER

5\. Use Case: Dynamic Text Replacement

`   `Question: You want to replace a placeholder in a text string with a dynamic value. Which function would you use?

a) SUBSTITUTE

b) CONCATENATE

c) VALUE

d) TEXT

**TRIM:**

1\. Use Case: Removing Leading and Trailing Spaces

`   `Question: You have a text string that contains leading and trailing spaces. Which function would you use to remove those spaces?

a) TRIM

b) UPPER

c) CONCATENATE

d) SUBSTITUTE

2\. Use Case: Cleaning Up Data

`   `Question: You have a dataset with text values that may contain extra spaces. Which function would you use to remove the extra spaces and normalize the data?

a) TRIM

b) REPLACE

c) LEFT

d) MID

3\. Use Case: Removing Specific Characters

`   `Question: You have a text string that contains specific characters you want to remove. Which function would you use to remove those characters?

a) TRIM

b) SUBSTITUTE

c) RIGHT

d) REPT

4\. Use Case: Handling Whitespace Errors

`   `Question: You have a text string that may have inconsistent whitespace, including multiple spaces between words. Which function would you use to correct the whitespace errors?

a) TRIM

b) LOWER

c) SEARCH

d) VALUE

5\. Use Case: Cleaning Up User Input

`   `Question: You have a user input field where users may accidentally include leading or trailing spaces. Which function would you use to sanitize the input and remove the spaces?

a) TRIM

b) PROPER

c) FIND

d) UNICHAR

**UNICHAR:**

1\. Use Case: Converting Unicode Values to Characters

`   `Question: You have a dataset that contains numeric codes representing Unicode characters. Which function would you use to convert these codes into actual characters?

a) UNICHAR

b) CONCATENATE

c) VALUE

d) SUBSTITUTE

2\. Use Case: Displaying Special Characters

`   `Question: You want to display special characters, such as symbols or emojis, in your text. Which function would you use to insert these characters into your text string?

a) UNICHAR

b) REPLACE

c) MID

d) UPPER

3\. Use Case: Generating Dynamic Strings

`   `Question: You need to generate a string that includes dynamic characters based on certain conditions or variables. Which function would you use to include these dynamic characters in your string?

a) UNICHAR

b) LEFT

c) SEARCH

d) TRIM

4\. Use Case: Handling Foreign Languages

`   `Question: You are working with text data that includes characters from different languages. Which function would you use to ensure the proper display of these characters?

a) UNICHAR

b) LOWER

c) SEARCH

d) VALUE

5\. Use Case: Data Import and Transformation

`   `Question: You are importing data that includes special characters or non-standard symbols. Which function would you use to transform the imported data into the appropriate characters?

a) UNICHAR

b) PROPER

c) FIND

d) RADIANS








**UNICODE:**

1\. Use Case: Finding the Numeric Code for a Character

`   `Question: You need to determine the numeric code corresponding to the first character of a given text string. Which function would you use to retrieve the Unicode code of the character?

a) UNICODE

b) REPLACE

c) CONCATENATE

d) IFERROR

2\. Use Case: Converting Numeric Codes to Characters

`   `Question: You have a dataset that contains numeric codes representing Unicode characters. Which function would you use to convert these codes into actual characters?

a) UNICHAR

b) UPPER

c) LEFT

d) FORMAT

3\. Use Case: Manipulating Unicode Characters

`   `Question: You want to perform string operations, such as searching or replacing, on text strings that include Unicode characters. Which function would you use to handle these operations?

a) REPLACE

b) UNICODE

c) TRIM

d) SUBSTITUTE






4\. Use Case: Filtering Data Based on Unicode Characters

`   `Question: You have a table of text data and you want to filter rows based on the presence of specific Unicode characters. Which function would you use to identify the Unicode characters in the text and apply the filter?

a) UNICODE

b) SEARCH

c) IF

d) CONCATENATE

5\. Use Case: Data Validation for Unicode Characters

`   `Question: You want to ensure that a text string only contains valid Unicode characters. Which function would you use to validate the presence of valid Unicode characters in the string?

a) UNICODE

b) VALIDATE

c) FIND

d) LEN

**UPPER:**

1\. Use Case: Converting Text to Uppercase

`   `Question: You have a text string and you want to convert it to uppercase. Which function would you use to achieve this?

a) UPPER

b) CONCATENATE

c) REPLACE

d) FIND






2\. Use Case: Normalizing Text Case

`   `Question: You have a dataset with inconsistent text case, and you want to standardize it to uppercase for consistency. Which function would you use to convert the text to uppercase regardless of its current case?

a) UPPER

b) TRIM

c) LEN

d) SEARCH

3\. Use Case: Case-Insensitive Text Comparison

`   `Question: You need to compare two text strings for equality, ignoring differences in case. Which function would you use to perform a case-insensitive comparison?

a) UPPER

b) EXACT

c) LEFT

d) SUBSTITUTE

4\. Use Case: Text Analysis Based on Uppercase

`   `Question: You want to analyze a text string and identify words or phrases that are written in all uppercase letters. Which function would you use to check if a word or phrase is written in uppercase?

a) UPPER

b) SEARCH

c) FIND

d) LEN

5\. Use Case: Converting Mixed Case Text to Uppercase

`   `Question: You have a text string with mixed case, where some words are lowercase and others are uppercase. Which function would you use to convert the entire text to uppercase?

a) UPPER

b) LOWER

c) PROPER

d) TRIM

**VALUE:**

1\. Use Case: Converting Text to Number

`   `Question: You have a text string that represents a number, and you want to convert it to an actual numeric value. Which function would you use to achieve this?

a) VALUE

b) CONCATENATE

c) REPLACE

d) FIND

2\. Use Case: Extracting Numeric Values from Text

`   `Question: You have a text string that contains both numeric and non-numeric characters, and you want to extract only the numeric values. Which function would you use to extract the numeric values as numbers?

a) VALUE

b) TRIM

c) LEN

d) SUBSTITUTE

3\. Use Case: Handling Numeric Text with Different Formats

`   `Question: You have a dataset where numeric values are stored as text, and they use different decimal separators (e.g., period or comma). Which function would you use to convert these text values to numeric values, regardless of the decimal separator?

a) VALUE

b) FORMAT

c) TEXT

d) SUBSTITUTE






4\. Use Case: Converting Date Text to Dates

`   `Question: You have a column of date values stored as text, and you want to convert them to actual date values. Which function would you use to convert the text dates to date values?

a) VALUE

b) DATE

c) DATEDIFF

d) TODAY

5\. Use Case: Summing Numeric Text Values

`   `Question: You have a column of numeric values stored as text, and you want to calculate the sum of these values. Which function would you use to convert the text values to numbers and perform the sum calculation?

a) VALUE

b) SUM

c) SUMX

d) CALCULATE



[ref1]: Aspose.Words.0aca6f62-2c7b-4485-86cb-3ac960fdc27b.001.png
