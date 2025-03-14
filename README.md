# **Tamil Nadu Assembly Election Data Processing (1971-2016)**  

This project extracts, cleans, and processes Tamil Nadu Assembly election data from **Wikipedia** and **Elections India**, spanning from **1971 to 2016**. The data is then structured into Excel sheets for further analysis.  

## **Project Overview**  
The project consists of three main scripts:  

1. **Data Extraction (`overall_code.py`)**  
   - Scrapes election data from **Wikipedia** and **Elections India** for each election year.  
   - Extracts tables containing constituency-level and overall election results.  
   - Saves the raw data into structured Excel sheets.  

2. **Elections India Data Cleaning (`eli_clean.py`)**  
   - Loads raw **Elections India** data from Excel.  
   - Cleans, standardizes, and removes irrelevant data.  
   - Saves the cleaned results into a new Excel file with:  
     - **Consolidated Results**  
     - **Election Results**  
     - **All Party Categories**  

3. **Wikipedia Data Cleaning (`wiki_clean.py`)**  
   - Loads raw **Wikipedia** data from Excel.  
   - Cleans and structures the data into:  
     - **Leaders Table** – Party-wise leadership and seat share.  
     - **Alliance Table** – Political party alliances per election.  
     - **Brief Result Table** – Summary of contested seats, vote percentages, and party-wise performance.  
     - **Total Result Table** – Constituency-level candidate results, winners, and margin of victory.  
   - Saves cleaned data into a final structured Excel file.  

## **Technologies Used**  
- **Python**  
  - `requests`, `BeautifulSoup` (Web Scraping)  
  - `pandas` (Data Processing)  
  - `xlsxwriter` (Excel File Handling)  

## **How to Use**  
1. Run `overall_code.py` to extract election data and save raw Excel files.  
2. Run `eli_clean.py` to clean and consolidate **Elections India** data.  
3. Run `wiki_clean.py` to clean and structure **Wikipedia** data into useful tables.  

## **Output Files**  
- `elections_wiki_data.xlsx` (Raw Wikipedia Data)  
- `elections_india_data.xlsx` (Raw Elections India Data)  
- `Cleaned_Elections_Data.xlsx` (Final cleaned Elections India dataset)  
- `Cleaned_Wikipedia_Data.xlsx` (Final cleaned Wikipedia dataset)  

