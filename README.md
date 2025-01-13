# Python-


# Web Scraping Projects

This repository contains a collection of Jupyter notebooks designed for web scraping tasks focused on extracting data from Wikipedia's "List of largest companies in the United States by revenue" page. The extracted data is processed and saved in various formats, including DataFrames and CSV files.

## Notebooks Overview

### 1. **WebPage_to_DataFrame.ipynb**
This notebook demonstrates how to scrape data from the specified Wikipedia page and transform it into a pandas DataFrame for further analysis. Key steps include:
- Sending HTTP requests to fetch the webpage content.
- Parsing HTML using BeautifulSoup.
- Extracting relevant table data.
- Creating a well-structured pandas DataFrame.

### 2. **WebScrapping_to_CSV.ipynb**
This notebook extends the functionality of the first by exporting the DataFrame created from the scraped data into a CSV file. Steps include:
- Scraping data from the webpage.
- Converting the table into a pandas DataFrame.
- Saving the DataFrame to a CSV file for external use.

### 3. **WebScrapping_WebPage_to_CSV.ipynb**
This notebook integrates the complete workflow:
- Scraping data from the webpage.
- Processing and cleaning the data.
- Saving the final output directly to a CSV file.
- Ensuring proper handling of edge cases such as missing or malformed data.

## Requirements

The notebooks require the following Python libraries:
- `pandas`
- `requests`
- `BeautifulSoup4`

You can install the necessary dependencies using the following command:
```bash
pip install pandas requests beautifulsoup4
```

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Open the desired notebook in Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```

3. Run the cells step-by-step to execute the web scraping tasks.

## Output
- The extracted data is stored in pandas DataFrames within the notebooks.
- CSV files are generated in the project directory for easy access and further use.

## Disclaimer
Ensure that you adhere to the terms and conditions of the website being scraped. Excessive or inappropriate scraping may violate website policies or legal guidelines.

## Author
This project is created to demonstrate web scraping techniques using Python. Contributions and suggestions are welcome!
