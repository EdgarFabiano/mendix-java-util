# mendix-java-util

Useful Mendix JavaActions
  - **FormatCNPJ**
	```
	Formats a 14 length String in the pattern "99.999.999/9999-99".
	If the String contains non numerical characters, it will remove them before formatting.
	If the String's length > 14, it will return it.
	```
	
  - **FormatCPF**
	```
	Formats a 11 length String in the pattern "999.999.999-99".
	If the String contains non numerical characters, it will remove them before formatting.
	If the String's length > 11, it will return it.
	```
	
  - **GetDatesBetween**
	```
	Returns the list of DateEntity between the two selected dates:
	  startDate
	  endDate
	Filtering by the selected week days:
	  sunday
	  monday
	  tuesday
	  wednesday
	  thursday
	  friday
	  saturday
	```

  - **MendixLogout**
	```
	Logs out the current user from session.
	```

  - **RemoveNonNumber**
	```
	Removes any non numerical character from a String using regular expression.
	If the String is empty or null, it will return it.
	```

  - **ValidateCNPJ**
	```
	Using the mod11 algorithm it verifies if the CNPJ is a valid one by it's verifier digits
	```
	
  - **ValidateCPF**
	```
	Using the mod11 algorithm it verifies if the CPF is a valid one by it's verifier digits
	```
	

