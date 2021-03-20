# UI_Automation

Automation suite for UI functional testing.

Basically the project contains Automation scripts for different website like  e-commerce(which runs on local system , and even on Mobile browser using Sauce labs ) and Maharashtra state govt website which basically consists of personal details along with Captcha enabled.

# Note :
1.	Karnataka state govt website still under progress (not yet completed).
Maharashtra   state govt website Automation Completed so one can run Maha_govt.py script to get the results.
2.	Here we are not submitting any data here since it’s a govt website and its asking Pan (one can easily get Income tax details) details so we didn’t took chance of submitting and PAN here we are using in this script is random strings .
3.	While running the script , please don’t uncomment the submit button xpath and make it click .


# Pre-requisites 
In order to run the automation script Python3 and pip should be pre-installed  and below libraries should be installed.
  ```pip install pytest-html```
  ```pip install selenium```
  ```pip install pytest```
  ```pip install PIL```
  ```pip install pytesseract```
  ```pip install logging```
  ```pip install opencv-python```
     
 Web Browsers & Web Drivers: Web Browsers: Safari, Chrome, Firefox, IE, Opera, Download webdrivers for the above browsers & put them in the Path variables.

 IDE: PyCharm, Visual Studio Terminal(MacOS) & Command Prompt(Windows)

# Steps to run the Automation Script
1. Cloning the repo from GitHub
  ```
  https://github.com/rajeevpatil24/UI_Automation.git
  ```
2. Go to the path where above repo has been cloned, open the repo in an IDE Open terminal in IDE and run below command

  ```
  pytest Amazon_flow.py --browser_name chrome -vss  --html=happy_path_flow.html
  ```
  ```
  pytest Maha_govt.py  -vss  --html=happy_path_flow.html
  ```
  
happy_path_flow.html file which you one can open in a browser of their choice, log file is also hosted here and screen shots also.
