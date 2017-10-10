# Sharepoint Calculated Field Formulas

### NOT Supported columns:
- ```Created by```
- ```Modified by```
- ```ID```
- everything else should work as an input to a calculated column, of course depending on its type. 
- **note** that the default columns ```Created```, ```Modified``` **as well as** ```Version``` are supported in calculated columns.


## All Formulas - by category
## All Formulas - alphabetical

[**A**](#A) | [**B**](#B) | [**C**](#C)


| Index | Formula| Description |
|-------|--------|-------------|
| <h2 id="A">A</h2>      | AND    | descr |
| <h2 id="B">B</h2>      | AND    | descr |
| <h2 id="C">C</h2>      | AND    | descr |

ABS() – Absolute. Remove the negative if presentAND() – Logical And. Return true if both clauses return true.AVERAGE() – Average value. The average of all the provided parametersCONCATENATE() – String concatenation. Concatenates every parameter provided and returns it as a single string.COUNT() – Count the values. Returns the number of values provided.COUNTA() – Count the non-null values. Returns the number of non-null values returned.DATE() – Create a date. Given a month, day, and year return a dateDATEDIF() – Difference between dates. Given two dates, return the difference between them.DAY() – Day of month. Given a date return the day of month.EVEN() -Round up to the nearest even number.EXACT() – Exact comparison. Given two values return true if they are exactly the sameFIND() – Find a string in another. Returns the position of the first string in the second or null if not foundHOUR() – Returns the hour of day. Given a date time column returns the hour of dayIF() – Return results based on a comparison. If the first parameter is true return the second parameter otherwise return the third parameterINT() – Returns an integer. Given a number returns the integer portion.ISERROR()- Is the parameter an error. Returns true if the parameter is an error and false if it is not.ISNUMBER() – Is the parameter a number. Returns true if the parameter results in a number and false if not.LEN() – Length of a string. Returns the number of characters in a string.LEFT() – Left portion of a string. Returns from the first parameter the number of characters specified in the second.LOWER() – Convert string to all lower case. Returns the string provided but in all lower case.MAX() – Maximum. Returns the maximum of the provided parameters.MEDIAN() – Median. Returns the number at the median of the provided set of parameters.MIN() – Minimum. Returns the smallest of the provided parameters.MINUTE() – Minutes after the hour. Returns the number of minutes after the hour from a provided date time parameterMONTH() – Month of year. Given a date returns the month of year.NOT() – Logical not. Returns true if the parameter results in false and false if the parameter results in true.ODD() – Round up to the next odd number.OR() – Logical Or. Returns true if either of the parameters result in true.POWER() – Exponent. Raises the first number to the power (exponent) of the second.PRODUCT() – Multiply. Multiplies the provided parametersPROPER() – Proper case a string. Initial capitalize the string.REPT() – Repeat character. Repeat the string provided in the first parameter the number of times specified in the second parameter.RIGHT() – Right portion of the string. Return from the first parameter string the number of characters specified in the second parameter – from the end of the string.ROUND() – Round. Round the number to the nearest whole number (up or down).ROUNDDOWN() – Round down only. Round the number down to the nearest integer.ROUNDUP() – Round up only. Round the number up to the nearest integer.SECOND() – Seconds after the minute. Given a date time parameter, return the number of seconds after the minute.SUM() – Arithmetic sum. Add the parameters togetherTEXT() – Convert to string. Format the first parameter according to the format specification in the second parameter.TRIM() – Remove spaces. Removes spaces from the front and end of a string.UPPER() – Upper case string. Converts a string to all upper case.WEEKDAY() – Day of Week. Returns the day of week for a date time parameterYEAR() – Year. Returns the year for a given date time parameter


## Example - TBD list of formulas and examples
- status new / revised
- unique id
