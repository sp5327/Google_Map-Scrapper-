# Google_Map-Scrapper-
A Python web scraper using Playwright to extract business information from Google Maps and export it to Excel and CSV.

Google Maps Web Scraper
This Python script uses the Playwright library to extract business information from Google Maps and export it to Excel and CSV formats.

Requirements
Python 3.x
Playwright library
Installation
Clone the repository to your local machine
Install the required dependencies by running pip install playwright pandas argparse dataclasses
Install the Playwright drivers for Chromium, Firefox, and WebKit by running playwright install
Usage
To use the scraper, run the following command:

python gs.py [search term] [location] [number of listings]

For example:

python gs.py "cafe" "guwahati" 50

The above command will search for 50 cafe listings in Guwahati and export the results to Excel and CSV files.

Output
The scraper exports the following information for each business listing:

Name
Address
Phone number
Website URL
The data is exported to two files:

map_data.xlsx
map_data.csv
Both files contain the same information in different formats.

License
This project is licensed under the MIT License - see the LICENSE file for details.
