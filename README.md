# mendix-java-util

Useful Mendix JavaActions
  - **MendixLogout**
	```
	Logs out the current user from session.
	```

  - **FormatCNPJ**
	```
	Formats a 14 length String in the pattern "99.999.999/9999-99".
	If the String contains non numerical characters, it will remove them before formatting.
	If the String's length > 14, it will return it.
	```
	
  - **RemoveNonNumber**
	```
	Removes any non numerical character from a String using regular expression.
	If the String is empty or null, it will return it.
	```
	
  - **ValidateCPF**
	```
	Using the mod11 algorithm it verifies if the CPF is a valid one by it's verifier digits
	```
	
  - **GetDatesBetween**
	```
	Returns the list of DateEntity between the two selected dates:
	  StartDate
	  EndDate
 
	Filtering by the selected week days:
	  Sunday
	  Monday
	  Tuesday
	  Wednesday
	  Thursday
	  Friday
	  Saturday
	```
