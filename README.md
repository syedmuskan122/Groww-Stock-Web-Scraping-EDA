# 📈 Web Scraping and Stock Market Data Analysis

A Python-based web scraping and exploratory data analysis project that collects stock market information from Groww and transforms it into structured data for analysis and visualization.

## 🎯 Project Overview

This project uses web scraping techniques to extract stock-related information from [Groww](https://groww.in/stocks), organize the collected data into a Pandas DataFrame, and analyze stock market metrics using Python.

The project focuses on understanding stock prices, market capitalization, trading volume, financial ratios, and price movements through statistical analysis and visualizations.

## 🔍 Key Analysis

- Web Scraping of Stock Information from Groww
- Extraction of Stock Names and Stock URLs
- Collection and Structuring of Stock Market Data
- Data Cleaning and Missing Value Analysis
- Duplicate Record Detection
- Data Quality Checks and Validation
- Univariate Analysis of Stock Market Metrics
- Bivariate Analysis of Financial Variables
- Multivariate Analysis and Correlation Analysis
- Identification of Top Stocks by Market Capitalization
- Analysis of Top Gainers and Losers by Percentage Change
- Ranking Stocks by Return on Equity (ROE)

## 🛠️ Tools & Technologies

- **Python** — Data collection and analysis
- **Requests** — Sending HTTP requests to retrieve webpage content
- **Beautiful Soup** — Parsing HTML and extracting stock information
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive development and analysis

## 📊 Key Metrics Analyzed

- Current Stock Price
- Price Change and Percentage Change
- 52-Week High and Low
- Opening Price and Previous Closing Price
- Trading Volume
- Market Capitalization
- Return on Equity (ROE)
- Price-to-Earnings (P/E) Ratio
- Earnings Per Share (EPS)
- Price-to-Book (P/B) Ratio
- Dividend Yield
- Industry P/E Ratio
- Book Value
- Debt-to-Equity Ratio
- Face Value

## 📈 Visualizations

The project includes multiple visualizations to explore stock market data and relationships between financial variables.

- Histograms for understanding data distributions
- Box plots for identifying potential outliers
- Scatter plots for analyzing relationships between financial metrics
- Correlation heatmap for examining relationships among numerical variables
- Market capitalization vs. trading volume analysis
- Return on Equity vs. P/E ratio analysis
- Stock price vs. market capitalization analysis
- Top 10 stocks by market capitalization
- Top 10 stocks with the highest and lowest percentage changes
- Top 10 stocks ranked by Return on Equity

## 📂 Project Files

- `Web Scaraping Project.ipynb` — Jupyter Notebook containing web scraping, data cleaning, analysis, and visualizations
- `README.md` — Project documentation

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Jupyter Notebook.
3. Install the required Python libraries:

   ```bash
   pip install requests beautifulsoup4 pandas numpy matplotlib seaborn openpyxl
   ```

4. Open `Web Scaraping Project.ipynb`.
5. Run the notebook cells in sequence.
6. Review the scraped stock data, data quality checks, analysis, and visualizations.

**Note:** An active internet connection is required to scrape live webpage content. The website's HTML structure or access restrictions may change, so scraping code may need updates.

## 🎯 Learning Outcomes

This project helped develop practical skills in:

- Web scraping and HTML parsing
- Data collection and extraction
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical analysis and visualization
- Financial metric interpretation
- Python programming and Jupyter Notebook workflows

## ⚠️ Disclaimer

This project is intended for educational and analytical purposes only. Stock market data may change over time, and the results should not be considered financial or investment advice. Please respect the source website's terms of service, robots.txt rules, and applicable access restrictions when scraping data.

## 👩‍💻 Author

**Muskan**

Data Science | Data Analytics | Artificial Intelligence

---

⭐ If you find this project useful, feel free to explore the notebook and share your feedback.
