🛍️ Amazon Product Scraper
A Python script that scrapes product information from Amazon based on search results. The script uses BeautifulSoup, requests, and pandas to collect and save details about products such as the title, price, rating, number of reviews, and availability.

📌 Features
Extracts:

Product Title

Product Price

Product Rating

Number of Reviews

Availability Status

Saves data to a CSV file (amazon_data.csv)

Handles missing data gracefully

📁 Project Structure

.
├── amazon_scraper.py        # Main Python script
├── amazon_data.csv          # Output file with scraped data
└── README.md                # Project documentation
🔧 Requirements
Install the required Python libraries using pip:

bash
Copy
Edit
pip install requests beautifulsoup4 pandas numpy
🚀 How to Run
Clone the repository:

git clone https://github.com/yourusername/amazon-product-scraper.git
cd amazon-product-scraper
Add your User-Agent in the script under HEADERS. (You can get it from your browser's developer tools.)

Run the script:

python amazon_scraper.py
The scraped product data will be saved as amazon_data.csv.

⚠️ Disclaimer
This script is for educational purposes only.

Scraping Amazon may violate their Terms of Service.

It’s recommended to use the Amazon Product Advertising API for production use.

🧑‍💻 Author
Jesika
3rd Year CSE Student

📃 License
This project is licensed under the MIT License - see the LICENSE file for details.

