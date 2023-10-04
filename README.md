-----> First Scraped the data from the different sites, and cleaned it, and done some visualization.<-----

# **:Web Scraping:** 
Web scraping is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications.

<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Web-Scraping/assets/112754746/da82a879-c3f7-406f-8ba1-65924df7094a"  height="350" width="800"/>
</div>

## Web scraping can be useful for a variety of purposes, including:
- **Data aggregation:**
    - Gathering data from multiple sources for analysis, such as news articles, product prices, or social media posts.
  
- **Research and monitoring:**
    - Collecting data for academic or market research, tracking prices of products or services, or monitoring changes on websites.
  
- **Content extraction:**
    - Extracting specific information from websites, such as contact details, reviews, or job postings.
  
- **Machine learning training data:**
    - Gathering data to train machine learning models, such as collecting images or text from various sources.

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48"> Aim:
The project's core aim centers on the extraction of data from static HTML pages and dynamic websites. This undertaking seeks to proficiently acquire information from a variety of online sources, facilitating the retrieval of valuable data for subsequent analysis and the generation of actionable insights.

##  <img src="https://github.com/yasmeenustad/ML-Housing-Habitability-Project/assets/112754746/f028cb01-2b46-4803-9876-9600d9d87b7b"  width="48" height="48">Libraries used for Web Scraping are:
### 1. Requests:
The Requests library is used for sending HTTP requests in Python. It simplifies the process of making GET and POST requests to a web server and receiving responses. It allows you to download the HTML content of web pages.

### 2. BeautifulSoup: 
BeautifulSoup is a Python library for parsing HTML and XML documents. It provides methods to extract data from parsed documents using various techniques, such as searching by tags, attributes, or CSS selectors. BeautifulSoup helps in navigating and manipulating the HTML structure of web pages.

## Data Cleaning:
Data cleaning, also known as data cleansing or data scrubbing, refers to the process of identifying and correcting or removing errors, inconsistencies, and inaccuracies in datasets. It involves transforming raw data into a clean and reliable format suitable for analysis or other data-driven tasks. 

## Data 1:- Amazon Women dresses:
This project is all about the Women's Dresses data, extracted from the Amazon website. The data is extracted by using the BeutifulSoup Python library. The scraped things are Name, Price, Rating, and Link of the particular product. And after scrapping the data, done the data cleaning.

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/Web-Scraping/assets/112754746/7fce33e0-169c-453f-be6c-25f2d5a12875"  height="500" width="1000"/>
</div>

## Data 2:- Swiggy Restaurants Data (Bangalore):
In this extensive project, successfully scraped a diverse dataset comprising around 1,300 Bangalore restaurant entries, encompassing crucial information like restaurant names, ratings, cuisine types, locations, delivery review numbers, and corresponding URLs. This valuable collection lays the foundation for in-depth analysis and exploration of Bangalore's vibrant culinary landscape.

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/Web-Scraping/assets/112754746/ab46d12a-ae3a-42ba-85ab-fc9f57388f86"  height="500" width="1000"/>
</div>

## Data 3:- Internet Movie Database (IMDb):
Utilizing the Beautiful Soup library, meticulously scraped and compiled a dataset showcasing IMDb's top 250 movies. This dataset encompasses critical details including movie titles, durations, ratings, IMDb ratings, release years, and convenient links for each movie.

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/Web-Scraping/assets/112754746/94755b32-f5a1-4380-9848-06dd5c686d14"  height="500" width="1000"/>
</div>

## Data 4:- Flipkart Mobiles Data:
Utilized the Beautiful Soup library to scrape data from around 400 mobile phones on the Flipkart website. The dataset includes variables such as mobile name, MRP, price, ratings, links, reviews, and the number of ratings.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/603ad77e-2212-4b07-a75a-ffcabb0538f4" width="70" height="50"> Challenges:

- **Website Changes:**
    - Websites evolve, altering their structure and code, which can disrupt scraping scripts. Maintaining adaptable code is crucial to ensure consistent data extraction.

- **Anti-Scraping Measures:**
    - Websites use tactics like CAPTCHAs, IP bans, and rate limiting to thwart scrapers. Overcoming these while staying ethical and legal demands advanced strategies.

- **Data Volume:**
    - Accumulating vast amounts of data can be overwhelming. Efficient storage, processing, and analysis solutions are essential for handling large datasets.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2e256cec-1421-4c5f-9913-052a53dc470f" width="70" height="50"> Learnings:

- **Data Management:**
    - Organize and store your scraped data efficiently using databases, CSV, or JSON files.

- **Handling Dynamic Websites:**
    - Learn how to scrape data from websites that use JavaScript or dynamic content with tools like Selenium.

- **Web Scraping Ethics:**
    - Always respect website terms of service and robots.txt files. Avoid aggressive scraping that may disrupt the website or violate legal and ethical boundaries.

