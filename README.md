# Company Data Analysis – Web Scraping & Exploratory Data Analysis (EDA)

## Project Overview

This project demonstrates a data analysis workflow using Python, starting with web scraping for data collection and continuing with data cleaning, feature engineering, and exploratory data analysis (EDA).

The project is divided into two main stages:

1. **Web Scraping:** Collecting company-related information from a website using Python.
2. **Exploratory Data Analysis:** Cleaning, processing, analysing, and visualising the collected company data to identify meaningful insights.

## Project Structure

```text
Company-Data-Analysis/
│
├── Web_Scraping/
│   └── Web_Scraping.ipynb
│
├── EDA/
│   └── EDA_Company_Analysis.ipynb
│
├── Companies.csv
├── Cleaned_Companies.csv
└── README.md
```

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- BeautifulSoup / Requests (if used in scraping)

## Stage 1: Web Scraping

The first stage focuses on collecting company-related information from a website using Python.

Activities:
- Sending HTTP requests.
- Extracting relevant webpage information.
- Parsing HTML content.
- Collecting company data.
- Saving the extracted data into a CSV file.

**Source Website:** [Add your actual website URL]

## Stage 2: Exploratory Data Analysis (EDA)

The collected company dataset is analysed to understand its structure, characteristics, and patterns.

### Data Cleaning
- Checked missing values and duplicate records.
- Converted numerical columns into appropriate data types.
- Removed unnecessary formatting characters.

### Feature Engineering
- Converted company revenue into INR crores using an assumed exchange rate.
- Calculated revenue per employee.
- Created revenue share percentages.
- Created revenue, employee-size, growth, and rank categories.

### Exploratory Analysis
- Univariate analysis.
- Bivariate analysis.
- Industry-wise analysis.
- Correlation analysis.
- Outlier detection using the IQR method.
- Multivariate analysis.

## Key Insights

- The dataset contains 100 companies.
- Financials is the most represented industry, with 16 companies.
- Revenue and employee count have a positive correlation of approximately 0.69.
- Revenue and revenue growth have a very weak linear correlation of approximately 0.05.
- The average revenue growth is approximately 7.69%.
- Outliers were identified in revenue, revenue growth, and employee count.

## Project Outcome

This project demonstrates the complete workflow of collecting, cleaning, transforming, analysing, and interpreting company data using Python.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Web Scraping notebook and run its cells.
4. Generate or use the company CSV dataset.
5. Open the EDA notebook.
6. Run the analysis cells to explore the dataset.
