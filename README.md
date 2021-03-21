# NetOnNet_Photoshop_scraper
This is a small project created to scrape data and picture from the Swedish NetOnNet website.

# What do you need
- Latest Python version (Today version is 3.9.2 and can be download from python.org)
  - I have also used Pycharm just because I am used to it, so I will instruct according to my way
- Photoshop

# Steps to make the program run
- Install python
- Install Pycharm
  - You can download the latest version Free from https://www.jetbrains.com/pycharm/download/
- Install needed libraries:
  - Open the python terminal and write these commands to install these libraries:
    - pip install bs4
    - pip install requests
    - pip install photoshop_python_api
    - pip install jupyterlab (Not needed but I think it is easier to visualize at jupyter lab)
- At the terminal write jupyter lab to open a browser for programming
- Copy the file (and import) Netonnet_scraping.ipynb or copy the code to jupyter lab
- When everything is done, all you need is to write:
  - import_to_ps(article code)
    Example: import_to_ps(1013353)
    
# Observations:
- The program will download the main picture of the article code to the python folder
