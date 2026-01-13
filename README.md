Unit and Integration Testing using PyTest

Student Name:
Maaz

Roll Number:
231400104

Course:
Software Quality Engineering (SE-315L)

Project Description:
This project focuses on performing unit testing and integration testing on a simple banking application using Python. The banking application includes functions such as deposit, withdrawal, interest calculation, loan eligibility checking, and fund transfer. Unit testing is used to verify each function independently, while integration testing ensures that multiple functions work together correctly. PyTest is used as the testing framework, and GitHub Actions is used for Continuous Integration to run tests automatically.

Project Structure:
bank_app.py – contains the banking application functions
test_unit.py – contains unit test cases for individual functions
test_integration.py – contains integration test cases involving multiple functions
requirements.txt – contains required Python testing libraries
.github/workflows/python-tests.yml – GitHub Actions workflow file for CI

How to Run Tests Locally:

Install required dependencies using:
pip install -r requirements.txt

Run all tests:
pytest

Run tests with detailed output:
pytest -v

Generate HTML test report:
pytest --html=report.html -v

GitHub Actions Description:
GitHub Actions is configured to automatically execute unit and integration tests whenever code is pushed to the repository or a pull request is created. The workflow installs required dependencies and runs all PyTest test cases. A successful run is indicated by a green tick in the GitHub Actions tab.
