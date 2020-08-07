Chapter	Lesson name
1- Introduction	Course Agenda
	System Development Life Cycle & Database Definition
	What is a Table?
	Data Models & ERM
	About Primary key & foreign key
	SQL and Types of SQL Statements
	Oracle Database 12c Architecture
	HR Schema in this Course
2-Live SQL & Download/ Install	Oracle Live SQL / No Installation for anything
	Downloading Oracle DB 12c
	Installing Oracle DB 12c
3-Connecting to the Database	Connecting SYS using SQL plus & SQL Developer
	Unlock HR Account Part 1
	Unlock HR Account Part 2
	ORA-01033 oracle initialization or shutdown in progress 12c 
4- Retrieving data using the select statement	Navigate HR schema
	Capabilities of SQL SELECT Statements
	Arithmetic expressions and NULL values
	Column Alias, Concatenation , Distinct and DESCRIBE
	Important Notes in Select Statement
5-Restricting and Sorting Data	The WHERE Clause & Comparison Operators
	Using Between and / IN / Like Operators
	Using IS NULL / NOT / Not equal Operators
	Logical Operators (AND/ OR/ NOT)
	Order by Clause
	The FETCH Clause
6-Substitution Variables	What is a Substitution Variables (&)
	DEFINE /  UNDEFINE 
	ACCEPT / PROMPT 
	 Double-Ampersand / SET VERIFY / SET DEFINE
07-Using Single-Row Functions to Customize Output	Single Row Function Introduction
	Character functions (Upper, Lower, Initcap )
	Character functions (concat, substr, length )
	Character functions ( instr )
	Character functions ( lpad, rpad , replace, trim)
	Number functions ( Round, Trunc, MOD )
	Date Functions ( Sysdate)
	Date Functions ( months_between, add_months, next_day, last_day)
	Date Functions ( round , trunc  )
	Nesting Functions
8- Using Conversion Functions and Conditional Expressions	Implicit Data Conversion VS Explicit
	TO_CHAR  with dates
	TO_CHAR  with numbers
	TO_NUMBER , TO_DATE Functions
	nvl , nvl2 , nullif  and coalesce Functions
	The CASE Function  
	The DECODE Function
9-Reporting Aggregated Data Using the Group Functions	Group functions Introduction
	Group functions (sum, count, max, min, avg & more)
	Group by Clause, Having Clause
10-Displaying Data from multiple tables using joins	Before You Start, important notes
	HR Tables Diagram, Joins Clarification
	What is Cartesian product?
	Old Joins: Equijoin
	Old Joins: nonEquijoins
	Old Joins: outer join
	Old Joins: Self Join and More Practices
	1999 Syntax: Cross Join (Cartesian product )
	1999 Syntax: Natural Join
	1999 Syntax: USING Clause
	1999 Syntax: ON Clause
	1999 Syntax: Left/Right/full Outer Join
11-Using Subqueries to Solve Queries	Single row Subqueries
	Multiple rows Subqueries
	NULL values and Subqueries
	Exists and not Exists 
12-Using the Set Operators	Overview (Union, union all, intersect, minus )
	Practice (Union, union all, intersect, minus )
13- Managing tables using DML Statments	Introduction to DML
	Insert Statement
	Inserting common errors
	Update Statement
	Delete Statement
	What is Database Transactions?
	About Commit & Rollback
	Practice ( Commit and rollback )
	SAVEPOINT
	ROW Lock
	FOR UPDATE Clause
14-Introduction to Data Definition Language	DDL & Naming Rules
	Data Types Part 1
	Data Types Part 2
	Creating Tables (without constraints)
	Types of constraints and why we use it?
	Creating Tables ( Column Level Constraints )
	Creating Tables ( Table Level Constraints )
	Constraints Guidelines
	ON DELETE cascade / ON DELETE set null
	Create Table AS subquery
	Alter Table/ Add Columns
	Alter Table/ Modify Columns
	Alter Table/ Drop Columns
	Alter Table/ Set Unused
	ALTER TABLE READ ONLY /  READ write
	Drop Table
	Rename Column / Rename Table
15-Tips you Should know	Tips you Should know Part 1
	Tips you Should know Part 2
	Tips you Should know Part 3
	Tips you Should know Part 4
	Tips you Should know Part 5
	Tips you Should know Part 6
16-Exam 1Z0-061 / Oracle Database 12c: SQL Fundamentals	About Exam  1Z0-061 / Visiting Oracle Website
	My recommendations
17-Introduction to Data Dictionary Views	What is Data Dictionary Views?
	What is DICTIONARY?
	USER_OBJECTS / ALL_OBJECTS
	USER_TABLES / ALL_TABLES / USER_TAB_COLUMNS
	USER_CONSTRAINTS & USER_CONS_COLUMNS Part 1
	USER_CONSTRAINTS & USER_CONS_COLUMNS Part 2
	COMMENT ON TABLE / COLUMN
18-Creating sequences, synonyms, and indexes	Sequences Part 1
	Sequences Part 2
	Sequences Part 3
	Sequences Part 4
	Creating Synonyms
	Creating Indexes Part 1
	Creating Indexes Part 2
19-Creating Views	What is a View? / What is the benefits of Views?
	Creating Simple Views
	Creating Complex Views
	With READ ONLY / With check option / Force view
20-Managing Schema Objects	Adding constraints / dropping constraints
	Rename Column / Rename Constraint
	Enable / Disable  Constraints
	Understanding DEFERRABLE Constraints
	DEFERRABLE Constraints Exercises
	GLOBAL TEMPORARY TABLE
	About SQL*Loader
	External Tables Part 1
	External Tables Part 2
21-Retrieving Data By Using Subqueries	Using the subquery as a source table
	Pairwise/ Non Pairwise Subqueries
	Scalar Subquery / Correlated Subquery
	Reminder of  Exists /  Not Exists 
	WITH Clause
22-Manipulating Data By Using Subqueries	Inserting/ Updating /Deleting  Using a subquery as a target
	Correlated Update / Correlated Delete
23-Controlling User Access	Database Security / System Privileges & Roles
	Database Security / Object Privileges 
	System Privileges & Privileges Practice 1
	System Privileges & Privileges Practice 2
	Creating ROLE Practice
	With Grant Option
	Drop user Statement
24-Manipulating Data	What is Data Warehouse?
	Explicit default value in insert & update statement
	Copy rows from another table
	INSERT ALL statement / INSERT FIRST
	Another "INSERT ALL" Example & Notes
	Creating Matrix Report Using PIVOT 
	The Merge Statement
	FLASHBACK Table & System change Number ( SCN)
25-Managing Data in Different Time Zones	THE INTERVAL ( YEAR TO MONTH / day TO second)
	to_yminterval / to_dsinterval
	Extract function
	timestamp / timestamp with time zone
	V$TIMEZONE_NAMES and some functions
	timestamp with local time zone
	TZ_OFFSET / FROM_TZ / TO_TIMESTAMP
26-Exam 1Z0-061	26-Exam 1Z0-061
