# Website Automation Test

This is a Robot Framework test suite for Website Automation Testing.

# Prerequisites

Before running this test suite, you'll need:

Python 3 installed on your system
The Robot Framework installed (pip install robotframework)
Selenium library installed (pip install robotframework-seleniumlibrary)
A web browser installed (e.g., Chrome or Firefox)
A Facebook account for testing

#  Setup

Clone this repository to your local machine.
Navigate to the facebook-login-automation directory.
Open the LoginTest.robot file in a text editor.
Replace the username and password variables with your Facebook login credentials.
Save and close the file.
Running the Test
Open a terminal or command prompt and navigate to the facebook-login-automation directory.
Run the command robot LoginTest.robot to execute the test suite.
Wait for the web browser to open and navigate to Facebook.
The test will automatically enter your login credentials and attempt to log in.
If the login is successful, the test will pass. If not, the test will fail.

# Customization

To customize this test suite for your specific use case, you can:

Modify the username and password variables to use different login credentials.
Update the test steps in the LoginTest.robot file to match your desired workflow.
Add additional test cases to the test suite for testing other features or scenarios.

# Troubleshooting

If you encounter any issues while running the test suite, you can:

Check that your web browser is up to date and compatible with Selenium.
Check that the username and password variables are set correctly in the LoginTest.robot file.
Increase the timeout value in the LoginTest.robot file if the test is timing out.
Check the Robot Framework and Selenium documentation for additional troubleshooting tips.
