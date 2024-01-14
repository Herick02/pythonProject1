# Selenium Webdriver Login Page Testing

## Introduction
This repository contains Python code for testing a login page using Selenium Webdriver. The purpose of this project is to perform both positive and negative tests on a login page to ensure its functionality and security.

## Technologies Used
- **Python**: The programming language used for scripting the tests.
- **Selenium Webdriver**: A powerful tool for controlling web browsers through programs and performing browser automation.

## Getting Started
Follow the steps below to set up and run the tests on your local machine:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/selenium-login-page-testing.git
   cd selenium-login-page-testing
   ```

2. **Install Dependencies:**
   Ensure you have Python installed on your machine. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Test Parameters:**
   Open the `config.py` file and update the following parameters:
   - `BASE_URL: (https://practicetestautomation.com/practice-test-login/).
   - `VALID_USERNAME` and `VALID_PASSWORD`: Credentials for positive testing.
   - `INVALID_USERNAME` and `INVALID_PASSWORD`: Credentials for negative testing.

## Running the Tests
Execute the test script by running the following command in your terminal:
```bash
python main.py
```

## Test Cases
The `main.py` script includes both positive and negative test cases for the login page. It covers scenarios such as:
- Successful login with valid credentials.
- Invalid login with incorrect username or password.
- Handling of empty username or password fields.
- Additional test cases based on the specific requirements of your application.

## Reporting
Test results and logs will be displayed in the console. Additionally, screenshots of the browser at critical steps will be saved in the `screenshots` folder for further analysis.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and enhancements are highly appreciated.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the Selenium and Python communities for providing excellent tools and resources for automated testing.
