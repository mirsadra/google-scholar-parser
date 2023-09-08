<!-- Add Google Scholar Logo -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Google_Scholar_logo.svg/1024px-Google_Scholar_logo.svg.png?20200110094142" alt="Google Scholar Logo" width="200">
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

Execute the notebook cell by cell. The notebook is divided into sections, each responsible for a specific task:

1. Scraping the Google Scholar search results page.
2. Extracting paper tags, citation links, and other relevant information.
3. Parsing and formatting the data.
4. Creating a CSV file with the extracted information.

After executing the entire notebook, the CSV file containing the paper information will be generated. You can find this file in the same directory as the notebook.

## Customization

You can customize the notebook by modifying the following functions:

- `get_paperinfo(paper_url)`: This function retrieves the content of a Google Scholar page. You can use it to scrape other search results.

- `get_tags(doc)`: Modify this function to select different tags or elements from the page source based on your requirements.

- `get_papertitle(paper_tag)`: If you want to extract additional information from the paper tags, customize this function.

- `get_author_year_publi_info(authors_tag)`: Adjust this function to extract different information from the author tags.

## Issues and Contributions

If you encounter any issues or have suggestions for improvements, please [open an issue](URL_to_repository_issues) in this GitHub repository. Contributions and pull requests are welcome!



