## SCRAPERTRON1000, a Python Amazon Web Scraper/Tracker

### Preface:
This project was originally designed with VSCode in mind for a high school project. Changes are coming soon™️!
### Usage:
IMPORTANT!! The files `urls.txt` and `priceLog.txt` are OPTIONAL downloads with 7 example Amazon links and a few example logs. `scrapertron.py` can work as a standalone program and will create any needed files.

Make sure you `cd` to the correct folder where scrapertron.py is located before running. Otherwise, the program may not be able to read files.

To add links to `urls.txt` via console, use `CTRL + Shift + V` to paste links when prompted.

Always leave an extra empty line at the bottom of the text files so the program can properly append new info.

If you intend to use your own email bot, you will need to use your own email & app password (2fa required).
(https://support.google.com/accounts/answer/185833?hl=en)

### Command line:
- Make sure you `cd` to the correct folder where scrapertron.py is located before running.
- Enter 0 or 1 to skip first prompt and go straight to scraping/adding urls
- Add your email (2nd arg) to skip email prompt

`python3 scrapertron.py` `python3 scrapertron.py 0` `python3 scrapertron.py 1 johndoe@gmail.com`

### Dependencies:
- BeautifulSoup4 `pip install bs4`
- urllib
- smtplib
- datetime
- sys
  
### Rubric (52/50)
- [x] Writeup (10)
     - [x] Research (8)
     - [x] Works Cited (2)
- [x] Presentation (20)
     - [x] Well-Designed Slides (5)
     - [x] Engaging (10)
     - [x] Responds to questions well (5)
- [x] Program (18)
     - [x] Version Control (4)
     - [x] Demonstration (10)
     - [x] Run via comand line and add arguments (4)
- [x] README.md (2)
     - [x] Dependencies (1)
     - [x] Commands and arguments to run (1)
- [x] Extentions (2)
     - [x] Sends email when alert is triggered (2)
