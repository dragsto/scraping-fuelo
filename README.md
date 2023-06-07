# Scraping fuelo.net

#### Scraping gas prices from Fuelo.net

Little Python script for scraping and downloading gas prices from the Fuelo website. The scraped data is stored as a CSV file for easy analysis and manipulation. It can be configured to download data for different types of gas and for various countries available on the website.

Instructions

- Visit Fuelo and navigate to the gas prices page.

- At the top left corner of the website, select the country for which you would like to scrape gas prices.

- Next, select the type of gas you are interested in.

- Once the webpage has loaded with your selected country and gas type, copy the URL from your browser.

- Open the Python script Fuelo_net.ipynb from this repository.

- Locate the line:

> r = requests.get('https://de.fuelo.net/fuel/type/lpg/3years?lang=en') <--link goes here

- Replace the URL inside the requests.get() method with the URL you copied from your browser.

- Save your changes and run the script. 

The script will generate a CSV file called prices.csv within the Google Colab environment. This CSV file contains two columns: Date and Avg Price, representing the date and the average price of gas respectively.
