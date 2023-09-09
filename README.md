# Google Scholar Web Scraping and CSV Creation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/mirsadra/google-scholar-parser.svg)](https://github.com/mirsadra/google-scholar-parser/stargazers)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat&logo=github&logoColor=white)](https://github.com/mirsadra/google-scholar-parser)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)

This Jupyter Notebook allows you to scrape Google Scholar search results, extract paper information, and create a CSV file with the following columns: Paper Title, Year of Publication, Author, Publication Journal, and URL of the Paper.

<!-- Add Google Scholar Logo -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Google_Scholar_logo.svg/1024px-Google_Scholar_logo.svg.png?20200110094142" alt="Google Scholar Logo" width="200">
</p>

## Sample Output
![Sample Table](table.png)

## Prerequisites

Before using this notebook, make sure you have the following:

- Python 3.10 installed
- Required libraries installed (you can install them using `pip`:
  - `requests`
  - `beautifulsoup4`
  - `pandas`

## Usage

1. Clone or download this repository to your local machine.

2. Open the Jupyter Notebook `parsing.ipynb` in your Jupyter Notebook environment.

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

### Buy me a coffee!
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/miirsadra)
