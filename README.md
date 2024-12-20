Google Form Autofill Using Selenium
This project demonstrates the use of Selenium WebDriver to automate the process of filling out a Google Form and submitting it programmatically. The script dynamically populates form fields like name, contact number, email, address, and a verification code, then submits the form and takes a screenshot of the confirmation page.

Features
Automates Google Form filling using Selenium WebDriver.
Supports dynamic input for multiple fields, including:
Full Name
Contact Number
Email Address
Full Address
Verification Code
Captures a screenshot of the confirmation page after submission.
Error handling for smooth execution.
Installation and Setup
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/google-form-autofill.git
cd google-form-autofill
Install Dependencies: Ensure you have Python installed. Install the required Python packages using:

bash
Copy code
pip install -r requirements.txt
Download ChromeDriver:

Download the version of ChromeDriver compatible with your Chrome browser from ChromeDriver Downloads.
Update the CHROMEDRIVER_PATH in the script with the path to your ChromeDriver executable.
Usage
Update the Google Form URL and input data in the script as required.
Run the script:
bash
Copy code
python autofill_google_form.py
After the form is submitted, a screenshot of the confirmation page will be saved as confirmation_page.png.
Project Structure
bash
Copy code
|-- autofill_google_form.py  # Main script for form automation
|-- requirements.txt         # Python dependencies
|-- confirmation_page.png    # Screenshot generated after form submission
Requirements
Python 3.7+
Selenium 4.x
Google Chrome
ChromeDriver
Example Inputs
The script is pre-configured with the following inputs:

Name: Yash Singh
Contact Number: 810419470
Email: yash@gmail.com
Address: 400074
Verification Code: GNFPYC
You can modify these values in the script for different use cases.

Output
After successful execution:

The Google Form will be submitted.
A screenshot of the confirmation page (confirmation_page.png) will be saved.
