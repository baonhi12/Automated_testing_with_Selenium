# Login Page with Selenium Test

This project consists of a simple login page built with HTML, CSS, along with a Selenium-based Python test script to validate the login functionality.

## Features

### Login Page
- A form for entering username and password.
- Frontend validation for the username and password.
- Displays an error message for invalid credentials.
- Redirects to a dashboard upon successful login.

### Dashboard Page
- Displays a welcome message after a successful login.
- Provides a logout button to return to the login page.

### Selenium Test Script
- Automated tests for login functionality using Selenium WebDriver.
- Tests multiple scenarios, including valid and invalid credentials.

---

## Project Structure

```
project/
├── index.html        # Login Page
├── dashboard.html    # Dashboard Page
├── test_login.py     # Selenium Test Script
├── Login.side    
└── README.md         # Project Documentation
```

---

## Getting Started

### Prerequisites
1. **Python**: Install Python (>= 3.8).
2. **Google Chrome**: Install the latest version.
3. **ChromeDriver**: Download and install the appropriate ChromeDriver for your version of Chrome.
4. **Selenium**: Install Selenium using pip:
   ```bash
   pip install selenium
   ```

---

## Running the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/baonhi12/Automated_testing_with_Selenium 
   ```
2. Open `index.html` in a local server or a browser (e.g., using VS Code's Live Server).
3. Enter username and password:
   - Valid credentials:
     - Username: `admin`
     - Password: `123`
   - Invalid credentials display an error message.

4. Successful login redirects to the dashboard.

---

## Running the Selenium Test

1. Update the test script (`test_login.py`) with the correct URL of the login page.
2. Run the test script:
   ```bash
   pytest test_login.py
   ```
3. The test script will:
   - Validate the login page functionality.
   - Test various scenarios with valid and invalid credentials.
   - example:
  ![image](https://github.com/user-attachments/assets/d2b15094-941e-477b-9ecb-383fcad9078b)
  ![image](https://github.com/user-attachments/assets/f99a38d0-fbf5-4a25-9503-3a0ec4f68bf9)


---

## Notes

- This project is designed for educational and testing purposes.
- Ensure the ChromeDriver path is configured properly if not in the system's PATH.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Authors

- FullName: PHAM BAO NHI 
- SID: BIT220127
- Class: 22IT-SE2

Feel free to reach out for questions or feedback!
