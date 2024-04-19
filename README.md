
Website Sentiment Analyzer
==========================

Program Description
-------------------
The Website Sentiment Analyzer is a GUI-based application developed in Python, 
utilizing libraries such as tkinter, BeautifulSoup, requests, and vaderSentiment.
It allows users to analyze the sentiment of text on websites by entering a URL 
and subject (optional) and then presents the sentiment results as either positive
or negative along with a compound score.

Features
--------
1. Extracts text from any provided URL.
2. Performs sentiment analysis using the VADER sentiment analysis tool.
3. User-friendly graphical interface for easy operation.
4. Displays sentiment as a score and a label (positive or negative).

Requirements
------------
- Python 3.6 or higher
- tkinter library
- requests library
- bs4 (BeautifulSoup) library
- vaderSentiment library

Installation
------------
1. Ensure Python 3.6 or higher is installed on your system.
2. Install required Python packages using pip:
   pip install requests beautifulsoup4 vaderSentiment

Usage
-----
1. Run the script to start the application.
2. Enter the complete URL of the website you wish to analyze in the 'Enter Website URL' field.
3. Optionally, enter a subject related to the text being analyzed in the 'Enter Subject' field.
4. Click 'Analyze Sentiment' to retrieve and analyze the website content.
5. View the sentiment analysis results displayed in the output box at the bottom of the application.

Developers
----------
- Alexis Martinez MS548

License
-------
This software is released under the MIT License.
