# SauceDemo-Test-Automation
Selenium automation project for SauceDemo.
# SauceDemo UI Automation Project

This project is a UI automation framework for the SauceDemo web application (https://www.saucedemo.com/ ). It is built using Selenium WebDriver with Java, TestNG, and Maven.

## Features

*   Automates the full cart and checkout functionality.
*   Uses Page Object Model (POM) design pattern (although we haven't explicitly created separate page classes, our `BaseTest` and `CartAndCheckoutTest` act as a simple structure).
*   Integrated with GitHub Actions for Continuous Integration (CI).

## How to Run the Tests

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/engomniaebrahim/SauceDemo-Test-Automation.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd SauceDemo-Test-Automation
    ```
3.  **Run the tests using Maven:**
    ```bash
    mvn test
    ```

## CI/CD Pipeline

The project is configured with a GitHub Actions workflow (`.github/workflows/maven.yml` ). The tests are automatically executed on every push to the `main` branch.
