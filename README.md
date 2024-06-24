# PowerBI-Practice
Welcome to the Power BI Practice repository! This project is dedicated to hands-on practice with various features and functionalities of Power BI, including tables, graphs, and DAX(DATA ANALYSIS EXPRESSIONS) functions. The aim is to get a proper understanding and practical experience by working on different aspects of Power BI every day.

1) Different Date functions
2) Different Logical Functions
3) Aggregate functions 
4) Time sentive functions 

[10:34 AM, 6/22/2024] Preethi Reddy: Date: create a date for individual year, month and day
Date( year, month, day)

Year: extract year from the date
Year(date)

Similarly for month and day

Today() returns cutrent date

Now() returns current date and time

EOMonth : returns end of the month specified with the number next to it
EOMonth(date,1)

DateIFF : returns no of units(days, months,quaters,year) between two dates.
DATEDIFF(date, shipdate, units)
Units: day, month, quarter, year

DateAdd : returns date with specified no of intervels and the intervel
DateAdd( date, no of intervel, unit)
DateAdd( date, -1 , month)

DatesYTD: returns set of dates in year to date period
DatesYTD(date)

WeekDay: Returns the day of the week for a date.
Weekday(date)

WeekNum: returns the week number for a date.
Weeknum(date, 1/2..)
[10:39 AM, 6/22/2024] Preethi Reddy: Logical functions:

IF: evaluates a condition, returns one value if it is true and one value if it is false.
If( condition, value if true, value if false)
IF(sales> 1000, “high”, “low”)

Switch: evalues an expression against a list of values and returns one possible value in return.

Switch( true(), contion, value if true, condition , value if true, value for others)
[11:56 AM, 6/22/2024] Preethi Reddy: Not: changes false to true and true to false
Not(condition)

Iferror: if error then the mentioned value if not the usual real value obtained.
IfERROR(condition, value if error)

Contains: checks if there any any rows that satisfy a condition.
Contains( sales, sales(productid), 123)

Isblank(): returns true if the value is blank
Isblank(sales)

Isnumber: returns true if the value is number
Is number(sales)

Text functions

Concatenate:
Combine two text strings into 1
Concatenate( firstname, last name)
