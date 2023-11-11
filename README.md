# JSsniper.py
"JSsniper" The script is a Python program designed to extract information from JavaScript files obtained from either a single URL or a list of URLs provided in a text file.
JS Sniper

Features
Asynchronous processing of URLs for efficient extraction.
Detection of various sensitive information, including API keys, access tokens, and more.
Support for both single URL input and batch processing from a file containing multiple URLs.
Getting Started
Prerequisites
Python 3.x

Install required dependencies using the following command:
```bash
  pip install aiohttp colorama
  pip install request
  pip install aiohttp
  pip install asyncio

Usage
python js_sniper.py
Choose an option:
Enter a single URL.
Enter a file path containing multiple URLs.

Examples
Single URL
python js_sniper.py

Multiple URLs from File
python js_sniper.py

Recommendations
If errors occur during processing, review and check the affected URLs manually.
No sensitive information identified in the processed URLs if no valid pages.
