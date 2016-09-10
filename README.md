# Dabrowski Software Development [ JavaScript ] 
# JsUtilityFunctions (v0.0.5)

- NEW:
 - calculateCountdownTime (deadlineDate, yearMark, monthMark, dayMark, hourMark, minuteMark, secondMark)
   - calculates time from current day up to some date in the future and returns in the following format depending on provided year-, month-, day-, hour-, minute- and second- marks
    <strong>06y 10m 03d 16h : 11m : 45s</strong>
 - Params:
   - deadlineDate: deadline date in the future
    - the remaining parameters are marks for years, months, days, hours, minutes and seconds respectively
 - <strong>UPLOADED 2016-09-10 16:45:00 GMT +01:00 [FEATURE]</strong>
 - 
 - calculateNumberOfDaysForCurrentMonth(currentMonth, currentYear)
   - calculates number of days for the given month and year
 - Params:
   - currentMonth: month of the year we want to calculate number of days
   - currentYear: year based upon we want to calculate number of days
 - <strong>UPLOADED 2016-09-10 16:45:00 GMT +01:00 [FEATURE]</strong>
 - 
- OLD:
 - sliceOff(arrayOfIndicesToRemoveItemsFromInputArray, applyToObject, optionalArrayOfObjectProps)
  - from inut array of objects removes those objects with ids specified in the first argument (all in one batch). You can filter input array of objects by supplying the second argument and optional third argument with specified object props and values. It is optimized for ordered list of array indices for objects to be removed;
 - insert(newArray, startIndex) : inserts new array into existing array starting at given index

 - reverse(): reverses input string (equivalent to TSQL REVERSE function)

 - countNumberOfChars(charToBeSearched): returns the total number of charToBeSearched chars for the given string

 - calculateDateDifference(startDate, endDate) - returns date difference as a literal string, e.g.  3 years 6 months
