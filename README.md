# WEATHER API AUTOMATION

## Built with
 - Postman
 - Newman
  
## Covers the following test scenarios
- Implementation of two endpoints using GET and POST requests
- Implementation of tests to check
     - Response status codes
     - Data correctness
     - Data type
     - Schema validation
     
## Automation implementation covers the following
- Includes parameterization of test data using a CSV file
- Uses Newman to automate APIs
- Uses Newman reporter to generate reports

# Usage
Runs API collection to generate reports on CLI

~~~
newman run WeatherAPI\ Collection.postman_collection.json -e Dev.postman_environment.json --iteration-data location.csv
~~~

Runs API collection to generate the report as an HTML file

~~~
newman run WeatherAPI\ Collection.postman_collection.json -e Dev.postman_environment.json --iteration-data location.csv -r html
~~~ 



