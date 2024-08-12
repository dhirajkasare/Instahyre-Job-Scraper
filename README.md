# Instahyre-Job-Scraper
Web Scrapping | Selenium | Python | Pandas

## Objective: 
Web scraping to extract more than 300 job listings related to Python roles from the Instahyre website followed by EDA on the dataset generated. The task is to create a dataset comprising specific details for each job listing and then find meaningful business insights.

## Website Url :
[Instahyre Python Jobs](https://www.instahyre.com/python-jobs)

## Data Description :

1. **Company Name**:
    - **Data Type**: String
    - **Description**: Title or name of the job position.
    
2. **Location**:
    - **Data Type**: String
    - **Description**: Location or city associated with the job posting.
    
3. **Founded**:
    - **Data Type**: Integer or String
    - **Description**: Year of establishment of the company offering the job.
    
4. **Employees**:
    - **Data Type**: Integer or String
    - **Description**: Number of employees in the company.
    
5. **About**:
    - **Data Type**: String
    - **Description**: Brief information or description about the company.
    
6. **Skills**:
    - **Data Type**: List of Strings
    - **Description**: Skills or requirements for the job position.
    
7. **Link**:
    - **Data Type**: String (URL)
    - **Description**: Link to the job listing for additional details or application.


## Features
- **Web Scraping**: Utilized Selenium to automate the extraction of job listings from Instahyre.
- **Data Cleaning**: Processed and cleaned the scraped data, including formatting skill sets into a consolidated string and merging job titles with positions.
- **Data Storage**: The cleaned data is saved in a CSV file for easy analysis and sharing.


## Ethical Scraping Practices

* Always adhering to ethical scraping practices and respecting the terms of service of the website.
* Being mindful of web scraping etiquette to avoid putting unnecessary load on the website's servers.