# AIMCodeExercise
Forex Rates Table
Develop a website that renders a table with the below description
- Make a GET REST to https://api.apilayer.com/fixer/latest with the header
“apikey : 9sOx2d1gWYZrKY0uD4hCbOMIQzLcL4KQ” and then retrieve the
foreign currency data and save it to variable. ( if the access_key isn’t usable,
please create a new access_key by registration a free account on their website )
- Create a new variable with the previous obtained data from the REST API call, but
in this new variable, add 10.0002 to each values of those currencies.
- Display both variables in a table
- For those values where its value is of even number, add a border colour of red to
the table data. For those value where the currency is HKD, add a border colour of
red to the table data as well.
- Create a function to check if the value is an even number.
