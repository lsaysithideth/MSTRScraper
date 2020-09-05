# MSTRScraper
Do you ever come across a project that requires you to go into hundreds, even thousands, of websites to find the same information?  This is what I tasked myself to do for a personal project to try and find the dozens of MicroStrategy Knowledge Base articles I authored in a sea of hundreds of thousands.

This code runs for approximately 30 minutes to an hour to open and extract 1,000 MicroStrategy Community Site links and saves to a csv file.  While the code runs, progress percentage is also displayed in the IDE.

Code Requirements:
-------------------------
Separate from Python, you will need the following downloads installed:

•	Google Chrome internet browser
•	ChromeDriver

Make sure the following Python packages are installed:

•	pandas - will allow us to save data to a csv, text, or excel file
•	selenium – will allow us to control a webpage using CSS tags
•	bs4 – will format and parse page source data neatly
