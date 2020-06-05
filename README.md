# UnsaverBot
## Instagram post unsaver bot built with selenium
This script automates the process of unsaving the saved posts of your instagram account. Just launch the script and it will do your work automatically.
- Note: Your internet speed must not be lacking, otherwise the program will fail to work because the elements of the page might not have been loaded before the program requests for those elements.
- Note: It will unsave 100 saved posts in one run, you can change it from code to whatever number you want on line 45.

## Requirements
1. Python
2. Selenium python library `pip3 install selenium`
3. tqdm python library `pip3 install tqdm`
4. [chromedriver_win32](https://chromedriver.storage.googleapis.com/index.html?path=80.0.3987.106/) for selenium

## This script works fine with
1. Windows 10
2. Python 3.7.4 or greater
3. chromedriver win32 (for windows)

## Getting Started
1. Downlaod `chromedriver` and put it in `C:\webdriver` directory. If you want to put it somewhere else then add that path in `webdriver.Chrome('C:\\webdriver\\chromedriver.exe')` on line 11.
2. Insert your username and password in `instaBot(username, password)` object on line 56.
3. Run the script `python UnsaverBot.py`
