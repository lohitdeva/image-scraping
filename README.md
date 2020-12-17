# Image Scraping with Python *(for Windows only)*

This is a simple python script that takes in a search term and number as inputs, scrapes the images from Google Images and then returns them to a specified directory.

To run this, install **ChromeDriver** onto your system from [here](https://chromedriver.chromium.org/downloads). Make sure that the version of ChromeDriver installed is the same as the version of the [Google Chrome](chrome://settings/help) (This link is to check your Chrome browser for updates) web browser downloaded on the system.

In the command Terminal, use the following commands:
* pip install --upgrade pip - To upgrade pip to the latest version
* pip install selenium - To install the selenium package required to run the webdriver

If any of the other package throws an error, use either *pip install **package name*** or *pip install --upgrade **package name***

To use the image scraper, make the following changes to the code:
* *Line 20* - Change the DRIVER_PATH address to wherever the **webdriver.exe** file is stored
* *Line 97* - Change the target_path address to the destination folder where you want the images to be stored
