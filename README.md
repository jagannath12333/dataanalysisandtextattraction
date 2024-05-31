

# Data Extraction and Text Analysis

This Python script extracts textual data from URLs provided in an Excel file and performs text analysis to compute various metrics such as sentiment scores, readability metrics, and other textual properties. The script uses libraries like BeautifulSoup for web scraping, NLTK for text processing, TextBlob for sentiment analysis, and Textstat for readability analysis.

## Features

- Extracts article text from URLs, excluding headers, footers, and other non-relevant content.
- Cleans and tokenizes the text, removing stop words and converting to lowercase.
- Calculates sentiment scores (positive, negative, polarity, subjectivity), readability metrics (average sentence length, percentage of complex words, Fog index), and other metrics (average word length, complex word count, syllable count per word, personal pronouns).
- Outputs the computed metrics to a CSV file for further analysis.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/data-extraction-and-analysis.git
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place the input Excel file (`Input.xlsx`) in the same directory as the script.
2. Run the script:

   ```bash
   python data_extraction_and_analysis.py
   ```

3. The output will be saved in `Output.csv` in the same directory.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

---


