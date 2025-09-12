## SCRAPERTRON1000, a Python Amazon Web Scraper/Tracker

### Preface:
This project was originally designed with VSCode in mind. Changes are coming soon™️!
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
