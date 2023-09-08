<!-- Add Google Scholar Logo -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.png" alt="Google Scholar Logo" width="200">
</p>

# Google Scholar Web Scraping and CSV Creation

This Jupyter Notebook allows you to scrape Google Scholar search results, extract paper information, and create a CSV file with the following columns: Paper Title, Year of Publication, Author, Publication Journal, and URL of the Paper.

<!-- Add Jupyter Notebook Logo -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/518px-Jupyter_logo.svg.png" alt="Jupyter Notebook Logo" width="200">
</p>

## Prerequisites

Before using this notebook, make sure you have the following:

- Python 3.x installed
- Required libraries installed (you can install them using `pip`):
  - `requests`
  - `beautifulsoup4`

## Usage

1. Clone or download this repository to your local machine.

2. Open the Jupyter Notebook `Google_Scholar_Web_Scraping.ipynb` in your Jupyter Notebook environment.

3. Modify the `url` variable to specify your Google Scholar search query. For example, you can change `"tirzepatide"` to your desired search term.

   ```python
   url = "https://scholar.google.com/scholar?start=0&q=tirzepatide&hl=en&as_sdt=0,5"
