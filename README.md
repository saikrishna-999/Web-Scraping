Web Scraping and Data Analysis of Fortune 500 Companies using Python
📌 Project Overview

This project demonstrates how to extract and analyze data from Wikipedia's list of the largest U.S. companies by revenue. Utilizing Python libraries such as BeautifulSoup and Pandas, the script scrapes the table, processes the data, and exports it into a CSV file for further analysis.

🛠️ Technologies Used

Python: Programming language used for scripting.

BeautifulSoup: Library for parsing HTML and XML documents.

Requests: Library for making HTTP requests to fetch web pages.

Pandas: Data manipulation and analysis library.

🔗 Wikipedia Source

List of largest companies in the United States by revenue

📁 Project Structure
/Web-Scraping
│
├── WebScrapingproject.ipynb       # Jupyter Notebook containing the scraping and analysis code
├── largest_companies_2023.csv     # Output CSV file with the scraped data
└── README.md                     # Project documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/saikrishna-999/Web-Scraping.git
cd Web-Scraping


Install the required libraries:

pip install requests beautifulsoup4 pandas


Execute the script:

python WebScrapingproject.py


The output will be saved as largest_companies_2023.csv in the project directory.

📊 Sample Output

The CSV file contains the following columns:

Rank: Position of the company.

Company: Name of the company.

Revenue: Annual revenue in USD.

Profit: Annual profit in USD.

Assets: Total assets in USD.

Market Value: Market capitalization in USD.

🔄 Future Enhancements

Automate the script to run periodically and fetch the latest data.

Implement error handling for network issues or changes in the webpage structure.

Extend the analysis to visualize trends over time using libraries like Matplotlib or Seaborn.
