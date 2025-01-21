# Python_finalProject

This project is designed to conduct both API and UI testing, ensuring that all functionalities meet the expected standards and behaviors. It includes structured tests, logging, and reporting components.

## Project Structure

- **assets/**: Contains static files like CSS for styling reports.
- **logs/**: Stores log files from test executions.
- **reports/**: Contains HTML reports generated from tests.
- **tests/**:
  - **api_tests/**: Tests related to API functionalities.
  - **ui_tests/**: Tests related to UI functionalities.
- **.flake8**: Configurations for flake8.
- **.pre-commit-config.yaml**: Configurations for pre-commit hooks.
- **.pylintrc**: Configurations for pylint.
- **README.md**: Documentation of the project.
- **requirements.txt**: All necessary Python dependencies.

## Setup

To set up this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Python_finalProject.git

## Navigate to the project directory:  cd Python_finalProject
## Install the required dependencies: pip install -r requirements.txt
##Running Tests: pytest tests/
## For API tests only: pytest tests/api_tests/
## For UI tests only: pytest tests/ui_tests/
## Generating Reports : 
#### pytest --html=reports/report_api.html tests/api_tests/
#### pytest --html=reports/report_ui.html tests/ui_tests/

## Logging:
Logs from the tests are stored in the logs/ directory. Check test.log for detailed test execution logs.
