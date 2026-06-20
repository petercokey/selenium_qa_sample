A simple Selenium automation test written in Python.

## Objective

This script demonstrates basic web automation by:

1. Opening a demo login page
2. Entering valid credentials
3. Clicking the login button
4. Verifying that the login was successful

## Technologies Used

- Python 3
- Selenium WebDriver
- Google Chrome

## Test Scenario

The script navigates to:

https://the-internet.herokuapp.com/login

It then uses the following credentials:

- Username: `tomsmith`
- Password: `SuperSecretPassword!`

After login, the script verifies that the success message:

```text
You logged into a secure area!
```

is displayed.

## Installation

Clone the repository:

```bash
git clone https://github.com/petercokey/selenium_qa_sample.git
cd selenium_qa_sample
```

Install dependencies:

```bash
pip install selenium
```

## Running the Test

```bash
python test_login.py
```

Expected output:

```text
Test Passed
```

## Project Structure

```text
selenium_qa_sample/
│
├── test_login.py
├── README.md
└── requirements.txt
```

## Author

Peter Okezue
