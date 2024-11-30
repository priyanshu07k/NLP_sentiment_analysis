# Text Analysis URL Scraper

## Project Description
This project is a **Text Analysis URL Scraper** that extracts text content from a list of URLs, analyzes it for sentiment and readability metrics, and generates a detailed Excel report. It is ideal for processing online content, such as articles or blogs, to evaluate their linguistic and sentiment characteristics.

## Features
### Text Extraction:
- Scrapes and extracts the title and text content from each URL.

### Text Analysis:
- **Sentiment Analysis**: Calculates the polarity and subjectivity of the text using TextBlob.
- **Readability Metrics**:
  - Average Sentence Length
  - Percentage of Complex Words
  - Fog Index (readability score)
- **Other Linguistic Metrics**:
  - Word Count
  - Complex Word Count
  - Average Word Length
  - Syllable Count
  - Personal Pronouns

### Excel Output:
- Saves all results to an `Output.xlsx` file with columns detailing every metric.

## Prerequisites
### Python Version:
- Ensure Python 3.7 or later is installed.

### Required Libraries:
Install the following libraries using pip:

```bash
pip install pandas requests beautifulsoup4 textblob openpyxl readability

