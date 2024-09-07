# **Allkpop & YouTube Data Scraping and Preprocessing**

### **Project Overview**
This project is designed to scrape data from allkpop.com and YouTube, preprocess the scraped data using Named Entity Recognition (NER) models and regular expressions (regex), and structure it for further analysis or machine learning projects. By leveraging a sophisticated tech stack including transformers for NER, pandas for data manipulation, Selenium and BeautifulSoup for web scraping, and regex for text cleaning, this project aims to provide a robust pipeline for extracting and refining web data.

### **Features**
- Data Scraping: Automated scraping of articles from allkpop.com and videos descriptions from YouTube.
  - [news article scraping](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/newspaper/Scroll_scrape_refined.ipynb)
  - [idol group & members scraping](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/newspaper/K_IDOL_db_scrape_tojson.ipynb)
  - [youtube data scraping](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/youtube/youtube_scrap.ipynb)
- Preprocessing: Utilizes a transformer-based NER model to identify and tag named entities in the scraped data. Additionally, employs regex for cleaning and structuring text data.
  - [Keyword Extract via NER](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/newspaper/Keyword_extract_NER_refined.ipynb)
  - [Keyword Extract via regex](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/newspaper/group_names_extract%26process_regex%26JSON.ipynb)
  - [Parsing & Assigning Group Name per title](https://github.com/Haikoo96/Kpop-related-dataset/blob/master/scraping%20and%20preprocess/newspaper/group_names_extract%26process_regex%26JSON.ipynb)
- Data Structuring: Organizes preprocessed data into a structured format using pandas, making it ready for analysis or machine learning applications.
  
### **Tech Stack**
- Transformers: For implementing NER models to identify named entities.
- Pandas: Used for data manipulation and structuring the preprocessed data.
- Selenium & BeautifulSoup: For dynamic and static web scraping from allkpop.com.
- Regex: For text cleaning and preprocessing tasks.
- Google API: for scraping data from Youtube
