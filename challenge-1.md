# Month Name

### Challenege

Write a function. It will return the name of a month of the year, given the month number, according to the table below. Make sure you do not put any input or output statements in the function; the month number will be passed in and the string containing the name will be returned.

Number	Month -1	January -2	February -3	March -4	April -5	May -6	June -7	July -8	August -9 September -10	October -11	November -12	December

### Solution

```function month_name(num) {
	let monthArray = ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December']
	let month = monthArray[num -1]
	return month
	}

```