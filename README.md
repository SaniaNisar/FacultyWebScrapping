# 📚 Faculty Web Scraping 
### 🔍 Overview
This project focuses on web scraping faculty data using Python, leveraging libraries such as BeautifulSoup, Selenium, and Pandas. The scraped data includes faculty details like ID, Name, Designation, Department, Extension, HEC Approved PhD Supervisor Status, Highest Education, and Profile Image URL. The final output is saved in CSV format, with additional tasks like data concatenation and sampling based on student ID.

### ⚡ Project Structure
```
WebScraping-Assignment/
│   # Contains all CSV files
│── lhr.csv
│── khi.csv
│── isl.csv
|── psh.csv
|── chin.csv
│── combined_file.csv
│── sample.csv

│   # Jupyter notebooks for scraping and analysis
│── LAHORE.ipynb
│── ISLAMABAD.ipynb
│── KARACHI.ipynb
|── PESHAWAR.ipynb
|── CHINIOT.ipynb

│   # Python scripts for modular code
│── CONCATENATOR.ipynb
├── README.md                  
```

### 🚀 Key Features
* 🌐 Web scraping using BeautifulSoup and Selenium
* 📄 Extraction of faculty details (designation, email, department, etc.)
* 📜 Department mapping for Lahore & Islamabad campuses
* 📊 Concatenation of multiple CSV files into a single file
* 🎯 Sampling data using sample() method based on student ID
* 💾 Final CSV export with cleaned and structured data

### 📝 Concatenation & Sampling
- All .csv files were loaded from the /data folder and concatenated into combined_file.csv.
- The sample() method was applied with frac=0.5 based on the last digit of Student ID (e.g., last digit = 5 → frac=0.5).
