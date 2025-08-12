# Aerocruise Pilot Shop Web Scraping Project

 Objective
This project involves scraping product information from **[aerocruisepilotshop.com](https://www.aerocruisepilotshop.com/)**, a specialized e-commerce site for aviation supplies.  
The goal is to gather structured data on various products across different categories, including:

- Aircraft Parts  
- Avionics  
- Pilot Supplies  
- Pilot Training  
- Safety and FBO  



Use Cases
The data collected can be valuable for:

- **Retail Businesses & E-commerce Stores**: Competitive pricing strategies, inventory management, and product discovery.
- **Market Researchers & Data Scientists**: Market trend analysis and building forecasting models for supply chain optimization.
- **Aviation Startups**: Competitive tracking and identifying gaps in the market.
- **Plane Owners & Pilots**: Finding the best prices for parts, checking availability, and sourcing rare items.



## Features
- Scrapes multiple aviation-related product categories.
- Extracts key product details:
  - Category  
  - Product Name  
  - Product URL  
  - Price (single values & ranges)  
  - Availability status  
  - SKU / Part Number  
  - Short Description  
  - Detailed Specifications  
- Handles pagination for multi-page categories.
- Saves results as:
  - **Category-specific CSV files**.All categories data have been seperated
  - **Combined CSV file** containing all categories. There is combined data for the 5 categories.

    This shows aircraft parts output.
    https://github.com/nguyaisharon/Web-scraping-/blob/main/pilot%20shop%20scraped%20data.PNG?raw=true


## Tools & Libraries Used
- **Python**
- **Requests** – for sending HTTP requests.
- **BeautifulSoup** – for parsing HTML content.
- **Pandas** – for structuring and saving data.
- **Regex (re)** – for price cleaning.
- **time** – for delays between requests.



## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/nguyaisharon/Web-scraping-.git
   cd Web-scraping-
