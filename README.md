Text Analysis URL Scraper

Project Description
This project is a Text Analysis URL Scraper that extracts text content from a list of URLs, analyzes it for sentiment and readability metrics, and generates a detailed Excel report. It is ideal for processing online content, such as articles or blogs, to evaluate their linguistic and sentiment characteristics.

#Features
Text Extraction:

-Scrapes and extracts the title and text content from each URL.
Text Analysis:

->Sentiment Analysis: Polarity and Subjectivity.
->Readability Metrics:
 -Average Sentence Length.
 -Percentage of Complex Words.
 -Fog Index (readability score).
->Other Linguistic Metrics:
 -Word Count, Complex Word Count, Average Word Length, Syllable Count, and Personal Pronouns.

Excel Output:

->Saves all results to Output.xlsx with columns detailing every metric.

#Prerequisites

-Python Version: Ensure Python 3.7 or later is installed.
-Required Libraries: Install the following libraries:

~pip install pandas requests beautifulsoup4 textblob openpyxl

#Input
Input File:
->Provide an Excel file (Input.xlsx) containing two columns:

 -URL_ID: A unique identifier for each URL.
 -URL: The webpage link to be analyzed.

#Output
->The script generates an Excel file named Output.xlsx containing the following metrics:

 -URL_ID, URL, Title, Positive Score, Negative Score, Polarity Score, Subjectivity Score etc.

#Usage
->Set Up the Input File:

 -Update the path to your input file in the script:

input_file = r'C:\Path\To\Input.xlsx'
->Run the Script:

 -Execute the Python script:

 ~sentiment_analysis.ipynb

->View Results:

 -Check the Output.xlsx file in the project directory for the results.

#File Structure

    project_directory/  
    │  
    ├── sentiment_analysis.ipynb  # Main script file  
    ├── Input.xlsx                # Input file with URLs  
    └── Output.xlsx               # Generated output file  

#Notes:

The script skips any URL that cannot be accessed or processed and logs an error message.
The text extraction may not work on heavily scripted or dynamic pages (e.g., JavaScript-heavy websites).
