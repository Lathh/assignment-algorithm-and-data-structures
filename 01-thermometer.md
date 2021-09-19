FUNCTION thermometer (input NUMBER, input STRING) RETURN NUMBER
	DECLARE var1 STRING, value of string is fahrenheit, kelvin, and celcius
	DECLARE var2 NUMBER
	STORE "Result"
	COMPUTE IF value of var1 is fahrenheit
		DO (var2 - 32) AND (5/9)
		ELSE IF value of var1 is kelvin
		IDO (var2 - 273.15)
		ELSE  value of var1 is celcius
		SHOW var2
	SET "Result" with computing result
	RETURN "Result"