# playground-datascience-python
playground-datascience-python

## Chapter 1: Introduction and Setup

### Setup

### Pre-work

### Introduction to Data Analysis

## Chapter 2: Core Python

### Data types
- built in primitive types
  - numbers, floats, integers
  - declare float
  - convert float to integer
  - convert integer to float
- basic arithmetic for numbers
  - use of math module for square root
  - use of math module for calculate distributions
- print formatting
- strings
  - substrings
  - string split
- date
  - declare a date
  - find days between dates
  - add/subtract dates
  - format dates
- booleans
- test equality
- none or null

### Data structures
- built in types
    - lists
        - creating lists
        - generating sequence lists with range
        - access elements
        - appending, inserting, and removing elements from lists
        - apply functions (to a list)
        - map, filter and reduce
    - tuples
        - creating tuples
        - creating tuples from lists
        - accessing elements from a tuple
    - dictionaries
        - creating dictionaries
        - adding and removing elements from a dictionary
        - dictionary generators
    - sets
        - creating a set

### Control flow
-  Conditionals, Loops and Iteration
  - conditionals
    - basic
    - if else
    - multiple conditions
  - loops
    - basic for loop
    - basic while loop
  - iteration
    - map returns a generator
  - error handling
    - invoking error and handling

### Functions
- Functions
  - Defining custom functions
    - Simple function
    - Empty function
    - Emulate VLOOKUP function in Excel without loop
  - Function performance
    - Measuring execution time use time module

### Case study

## Chapter 3: Data Analysis in Pandas

### Data frames
- Data Frames
  - Fundamentals of data frames
    - Construct a data frame from a dictionary
    - Construct a data frame from a comma-separated value (csv) file
    - Construct a data frame from a fixed-width file
    - Construct a data frame from an Excel file
    - Fundamental data frame properties
    - Fundamental data frame methods
    - Selecting columns, rows and cells
    - Adding and removing columns from a data frame
    - Series operations
  - Data frame operations: dropping duplicates, sorting, filtering and formulas
    - Using drop_duplicates to return unique combinations of column values
    - Sort a data frame by its columns
    - Filtering.  There are two ways to row filter (e.g., boolean series)
    - Missing data and filters
  - Exporting Data Frames to Excel and csv
    - Exporting to Excel and csv
 
### Composing and combining data
- Combining Data Frames
  - Concatentation
    - Row concatenation (bottom-to-top)

### Aggregation, grouping, pivot tables
- Grouping, Aggregation and Pivot Tables
  - Grouping and Aggregation
    - Grouping
    - Standard Aggregation - use if possible due to performance
    - Custom Aggregation
    - Pivot Tables      

### Case study
e.g., Cancer data set?

## Chapter 4: Advanced Data Manipulation

### Consolidate files
- Glob files read from Csv
- Import Excel into Data Frame
- Export Data Frame to Csv

### Basic Pandas Review
- Filtering
- De-duplication
- Sorting

### Melting, Reshaping
- Dataset: DESYNPUF
- Add column
- Split variable into two parts
- Format percentages
- Create Pivot table

### Grouping, Aggregating
- Split, Apply, Combine

### Time series
- Group by
- Indexing using DateTime object
- Shift, Lag
- Cumulative sum
- Rolling window
- Plotting

### Case study

## Chapter 5:  Polygot - Integration with other Programming Languages

### Excel integration
- Read Csv
- ExcelWriter
- Save Excel workbook

### SQL support
- SqlLite
- SQL Alchemy
- Read Csv to Data Frame
- Data Frame to Database

### R support
- Rpy2
- Import R packages
- Convert Pandas to R Data Frames
- Run machine learning
  - Linear regression
- Output results

### Case study:

## Future Direction
- Arrow
  - Too many other modules
    - datetime, time, calendar, etc.
- Dask
  - Parallel Task library
- Pandas2