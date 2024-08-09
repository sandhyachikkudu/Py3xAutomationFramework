# Python Api Automation Framework

### Tech stack
- python 3.12
- Requests - HTTO Framework
- Pytest - Testing Framework 
- Reporting - Allure Report, Pytest HTMl
- Test Data - CSV, Excel, JSON
- Advance API Testcase - jsonschema
- Parallel Execution - X distribute(xdist)


### How to Install Packages

'''pip install requests pytest pytest-html faker allure-pytest jsonschema'''

### How to run your Testcase Parallel
'''pip install pytest-xdist'''

### How to add .gitignore file?
copy the content from this to .gitignore file
https://www.toptal.com/developers/gitignore/api/visualstudiocode


#### organisation of code
- 1- API constant-url
- 2- Utils - header
- 3- payload - payload manager
- 4- requests - resquests
- 5- verification- tests 

### How to run the Basic Test with Allure report
'''pytest tests/tests/crud/test_create_booking.py  --alluredir=allure_result -s'''

# Allure Report

