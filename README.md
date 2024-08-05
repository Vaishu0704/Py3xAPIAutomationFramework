# Python API Automation Framework

### Tech Stack
- Python 3.12
- Requests - HTTP Requests
- PyTest - Testing Framework
- Reporting - Allure Report, PyTest HTML
- Test Data - CSV, Excel, JSON, Faker
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)
- Allure Report
- Screenshot 2024-08-05 at 08 19 43
### Allure Report

<img width="689" alt="image" src="https://github.com/user-attachments/assets/c7ac7a1a-90db-4689-858f-eaa29c97307c">

### How to Install Packages
 pip install requests pytest pytest-html faker allure-pytest jsonschema

### How to run your Testcase Parallel
pip install pytest-xdist

### How to add the .gitignore File?
Copy the content from this to .gitignore file https://www.toptal.com/developers/gitignore/api/pycharm+all

### How to run the Basic Test with Allure report
 pytest tests/tests/crud/test_create_booking.py  --alluredir=allure_result -s
