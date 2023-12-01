# Web Scraping Project

This project scrapes data from website journeys using the Web Scraper Chrome Extension.

## Data

The data is stored in a CSV file named `data.csv`. It contains the following columns:

- `url`: the URL of the web page
- `last_modified`: the date and time when the web page was last modified
- `change_frequency`: how often the web page is likely to change
- `priority`: the priority of the web page relative to other pages on the site

## Sitemap

The sitemap is an XML file named `sitemap.xml` that lists all the web pages that are scraped by the project. It follows the standard sitemap protocol¹.

The sitemap was created using the Web Scraper Chrome Extension², which is a free and easy to use web data extraction tool. To use the extension, you need to:

1. Install the extension and open the Web Scraper tab in developer tools (which has to be placed at the bottom of the screen).
2. Create a new sitemap.
3. Add data extraction selectors to the sitemap.
4. Launch the scraper and export scraped data.

For more details, you can refer to the [Web Scraper documentation](^3^) or the [Web Scraper tutorial](^4^).

## Installation

To install the project, you need to have Python 3 and the pandas package installed.

You can install pandas using the command:

`pip install pandas`

## Usage

To run the project, you need to have the `data.csv` and the `sitemap.xml` files in the same directory as the project. Then, you can execute the following Python code:

```python
import pandas as pd

# read the csv file
df = pd.read_csv('data.csv')

# print the first 5 rows of the data
print(df.head())
```

This code will read the data from the CSV file and print the first 5 rows of the data.

## Contact

If you have any questions or feedback, please contact me.
