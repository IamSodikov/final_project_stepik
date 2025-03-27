# final_project_stepikg
# Selenium Final Project – Automated UI Testing

This repository contains the final project for the automated testing course on Stepik. The project demonstrates usage of **Selenium WebDriver**, **PyTest**, and the **Page Object Model** design pattern to build readable, reusable, and maintainable UI tests for a demo online store.

## 💡 Project Structure
📁 pages/ # Page Object classes base_page.py # Base class with common methods product_page.py # Product page interactions basket_page.py # Basket page interactions login_page.py # Login page (placeholder) main_page.py # Main store page locators.py # All element locators 📄 test_main_page.py # Tests related to main page 📄 test_product_page.py # Tests related to product page 📄 conftest.py # PyTest setup and fixtures 📄 pytest.ini # PyTest configuration 📄 requirements.txt # Dependencies list


## ✅ What’s Tested?

- Guests can add products to the basket
- Success messages appear or don’t appear correctly
- Basket is empty when expected
- Navigation to login page works
- Page structure and elements

Each test is written in **Page Object style**, and all locators are kept in a centralized file.

## 🚀 How to Run the Tests

1. Install requirements:

```bash
pip install -r requirements.txt

Run all tests:
    pytest

Run only selected marked tests:
    pytest -m need_review

📌 Technologies Used
Python 3.x

Selenium 3.14.0

PyTest 5.1.1

Chrome WebDriver

📂 Notes
Some tests are marked as @pytest.mark.xfail intentionally to demonstrate negative testing and known issues.

