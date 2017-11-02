<h6 id="top"></h6>

# Sharepoint Calculated Field Formulas 
## Choose section
- [supported](#supported)
- [browse by category](#cat)
- [browse alphabetically](#alpha)
- [examples](#examples)

<h6 id="supported"></h6>

## Not Supported Columns:
- ```Created by```
- ```Modified by```
- everything else should work as an input to a calculated column, of course depending on its type. 
- **note** that the default columns ```ID```, ```Created```, ```Modified``` **as well as** ```Version``` are supported in calculated columns.

<h6 id="cat"></h6>

## All Formulas - by category 

[**Conditional formulas**](#conditional) | [**Date and time formulas**](#datetime) | [**Mathematical formulas**](#math) | [**Text formulas**](#text)


<h4 id="conditional"></h4>

### Conditional formulas

<h4 id="datetime"></h4>

### Date and time formulas

<h4 id="math"></h4>

### Mathematical formulas

<h4 id="text"></h4>

### Text formulas

| Category | Formula | Example |
|:----------:|----------|----------|
||      |   |


<h6 id="alpha"></h6>

## All Formulas - alphabetical 

[**A**](#A) | [**C**](#C) | [**D**](#D) | [**E**](#E) | [**F**](#F) | [**H**](#H) | [**I**](#I) | [**L**](#L) | [**M**](#M) | [**N**](#N) | [**O**](#O) | [**P**](#P) | [**R**](#R) | [**S**](#S) | [**T**](#T) | [**U**](#U) | [**W**](#W) | [**Y**](#Y)


|           Index | Formula      |                               Description |
|:---------------:|--------------|-------------------------------------------|
|<h4 id="A">A</h4>| ABS()        | Absolute. Remove the negative if present. |
|                 | AND()        | Logical And. Returns TRUE if all clauses are true, or FALSE if one clause is false.|
|                 | AVERAGE()    | Returns the average of all provided values. |
|<h4 id="C">C</h4>| CHAR()       | Returnts the character, specified by a number from 1 to 255. [ASCII table reference]              (http://www.asciitable.com/) |
|                 | CHOOSE()     | Select a values based on an index. ```=CHOOSE(index, val1, val2)``` If index is 1, CHOOSE will return  val1|
|                 | CODE()       | Display the numeric code for a character. |
|                 | CONCATENATE()| String concatenation. Concatenates every parameter provided and returns it as a single string. |
|                 | COUNT()      | Count the values. Returns the number of values provided. |
|                 | COUNTA()     | Count the non-null values. Returns the number of non-null values returned.|
|<h4 id="D">D</h4>| DATE()       | Create a date. Given a month, day, and year return a date.|
|                 | DATEDIF()    | Difference between dates. Given two dates, return the difference between them. |
|                 | DAY()        | Day of month. Given a date return the day of month. |
|<h4 id="E">E</h4>| EVEN()       | Round up to the nearest even number. |
|                 | EXACT()      | Exact comparison. Given two values return true if they are exactly the same. |
|<h4 id="F">F</h4>| FACT()       | Returns the factorial of a number. |
|                 | FIND()       |Find a string in another. Returns the position of the first string in the second or null if not found|
|<h4 id="H">H</h4>| HOUR()       | Returns the hour of day. Given a date time column returns the hour of day |
|<h4 id="I">I</h4>| IF()         | Return results based on a comparison. If the first parameter is true return the second parameter otherwise return the third parameter
|                 | INT()        | Returns an integer. Given a number returns the integer portion.|
|                 | ISERROR()    | Is the parameter an error. Returns true if the parameter is an error and false if it is not.
|                 | ISNUMBER()   | Is the parameter a number. Returns true if the parameter results in a number and false if not.
|<h4 id="L">L</h4>| LEN()        | Length of a string. Returns the number of characters in a string.|
|                 | LEFT()       | Left portion of a string. Returns from the first parameter the number of characters specified in the second. |
|                 | LOWER()      | Convert string to all lower case. Returns the string provided but in all lower case. |
|<h4 id="M">M</h4>| MAX()        | Maximum. Returns the maximum of the provided parameters.
|                 | MEDIAN()     | Median. Returns the number at the median of the provided set of parameters.
|                 | MIN()        | Minimum. Returns the smallest of the provided parameters.
|                 | MINUTE()     | Minutes after the hour. Returns the number of minutes after the hour from a provided date time parameter.|
|                 | MONTH()      | Month of year. Given a date returns the month of year. |
|<h4 id="N">N</h4>| NOT()        | Logical not. Returns true if the parameter results in false and false if the parameter results in true.
|<h4 id="O">O</h4>| ODD()        | Round up to the next odd number.|
|                 | OR()         | Logical Or. Returns true if either of the parameters result in true.|
|<h4 id="P">P</h4>| POWER()      | Exponent. Raises the first number to the power (exponent) of the second. |
|                 | PRODUCT()    | Multiply. Multiplies the provided parameters. |
|                 | PROPER()     | Proper case a string. Initial capitalize the string.
|<h4 id="R">R</h4>| REPT()       | Repeat character. Repeat the string provided in the first parameter the number of times specified in the second parameter. |
|                  | RIGHT()     | Right portion of the string. Return from the first parameter string the number of characters specified in the second parameter – from the end of the string. |
|                  | ROUND()     | Round. Round the number to the nearest whole number (up or down). |
|                  | ROUNDDOWN() | Round down only. Round the number down to the nearest integer.|
|                  | ROUNDUP()   | Round up only. Round the number up to the nearest integer. |
|<h4 id="S">S</h4> | SECOND()    | Seconds after the minute. Given a date time parameter, return the number of seconds after the minute.|
|                  | SUM()       | Arithmetic sum. Add the parameters together. |
|<h4 id="Т">Т</h4> | TEXT()      | Convert to string. Format the first parameter according to the format specification in the second parameter.|
|                  | TRIM()      | Remove spaces. Removes spaces from the front and end of a string. |
|<h4 id="U">U</h4> | UPPER()     | Upper case string. Converts a string to all upper case. |
|<h4 id="W">W</h4> | WEEKDAY()   | Day of Week. Returns the day of week for a date time parameter. |
|<h4 id="Y">Y</h4> | YEAR()      | Year. Returns the year for a given date time parameter

[back to top](#top)
[back to categories](#cat)
[back to alphabetical index](#alpha)

<h6 id="examples"></h6>

## Example - TBD list of formulas and examples
- Status new / revised for a list record: ```=IF([Modified] > [Created], "Revised", "New")```
- Number of revisions: ```=INT([Version]) - 1 ```
- Filter a view so that it displays only entries that the current user has created: ```Modified by = [Me]```
