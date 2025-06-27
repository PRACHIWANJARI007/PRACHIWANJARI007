# 🛒 Web Scraping Based on Flipkart Data Analytics and Visualization

A data analytics project that focuses on extracting e-commerce data from Flipkart through automated web scraping, cleaning the collected data, and visualizing key product trends. This project helps understand pricing, ratings, product availability, and customer preferences across various categories like laptops and smartphones.

---

## 📌 Description

This project uses Python-based tools like Selenium and BeautifulSoup to scrape product listings from Flipkart. It collects details such as product names, prices, ratings, and review counts. The collected data is then processed using Pandas and visualized through Matplotlib and Seaborn to derive insights such as:

- What are the most affordable laptops?
- How do ratings correlate with prices?
- Which products have the highest reviews?

---

## ⭐ Key Features

- 🔎 Scrape dynamic content loaded with JavaScript using Selenium.
- 🧹 Clean and preprocess data using Pandas.
- 📊 Visualize data through histograms, bar charts, scatter plots, and box plots.
- 📁 Export cleaned data to CSV format for future use.
- 🧠 Insightful analysis of pricing trends, customer preferences, and product performance.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **BeautifulSoup** – HTML parsing
- **Pandas** – Data manipulation and cleaning
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📁 Project Structure

```bash
flipkart-data-analytics/
│
├── data/                    # Raw and cleaned datasets
├── images/                  # Saved visualizations
├── src/                     # Python scripts
│   ├── scraper.py           # Web scraping logic
│   └── clean_data.py        # Data preprocessing and cleaning
├── notebooks/               # Jupyter notebooks with full analysis
├── requirements.txt         # Required libraries
└── README.md                # Project documentation

# 🚀 How to Use the Code

1. Clone the Repository
git clone https://github.com/yourusername/flipkart-data-analytics.git
cd flipkart-data-analytics

2. Install Dependencies
Make sure you have Python installed, then run:
pip install -r requirements.txt

3. Run web Scraper
The script will open Flipkart in a browser, search for a product category (like "laptops"), and save the data.
python src/scraper.py

4. Analyze the Data
  Load the CSV file (laptop_data.csv)
  Use Jupyter notebook or scripts like analysis.py to visualize data.

5. Create Dashboard
  Import CSV into Power BI
  Use bar charts, pie charts, filters for insights(eg. price distribution, top-rated brands)
