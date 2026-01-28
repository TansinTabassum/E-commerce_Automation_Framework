# E-commerce Automation Framework

## Overview
This is a *Selenium WebDriver + Pytest automation framework* for automating key functionalities of an E-commerce website.  
It follows the *Page Object Model (POM)* design pattern and includes features like *reporting, screenshots on failure, and explicit waits*.

---

## Features
- Login automation (valid & invalid scenarios)
- Product search automation (valid & invalid)
- Add to cart automation
- Screenshot on test failure
- HTML reports for test results
- Structured framework using *Page Object Model*

---

## Tech Stack
- *Python 3.9+*
- *Selenium WebDriver*
- *Pytest*
- *Pytest-html* (HTML report generation)
- *ChromeDriver*
- *VS Code* (IDE)

---

## Folder Structure

selenium_pytest_framework/ 
│ ├── tests/
│   ├── test_login.py 
│   ├── test_search.py 
│   ├── test_cart.py 
│ ├── pages/ 
│   ├── login_page.py 
│   ├── search_page.py 
│   ├── cart_page.py 
│ ├── utils/ 
│   ├── config.py 
│   ├── wait_utils.py 
│   └── screenshot.py 
│ ├── reports/ 
│ ├── conftest.py 
├── pytest.ini 
├── requirements.txt 
└── README.md



selenium_pytest_framework/ │ ├── tests/ │   ├── test_login.py │   ├── test_search.py │   ├── test_cart.py │ ├── pages/ │   ├── login_page.py │   ├── search_page.py │   ├── cart_page.py │ ├── utils/ │   ├── config.py │   ├── wait_utils.py │   └── screenshot.py │ ├── reports/ │ ├── conftest.py ├── pytest.ini ├── requirements.txt └── README.md
