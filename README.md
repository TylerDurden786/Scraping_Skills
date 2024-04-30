# Skills Scraper

---

## Description

This Python script, named `skills_scrape.py`, utilizes Selenium, a powerful web scraping library, to extract job postings from LinkedIn related to a specified keyword, typically job titles like "data engineer". The script navigates through multiple pages of job listings, extracting key details such as job title, company name, and job description. 

### Features

1. **Headless Web Scraping**: The script runs in headless mode, meaning it operates without opening a visible browser window, thus improving efficiency.

2. **Dynamic Page Loading**: It dynamically scrolls through the LinkedIn job search page to ensure all relevant job postings are loaded, adjusting to the specified number of pages to scrape.

3. **Detail Extraction**: For each job posting, it captures essential information such as job title, company name, and job description.

4. **Description Expansion**: It automatically expands job descriptions by clicking the "show more" button, if available, to ensure comprehensive data extraction.

5. **Skill Extraction**: The script identifies relevant skills mentioned within job descriptions, utilizing predefined keywords to match against the text.

6. **Output Analysis**: It presents a summary of extracted skills, providing insights into the most sought-after skills within the job market for the specified role.

## Dependencies

- Python 3.x
- Selenium
- Chrome WebDriver
- Chrome Browser
- BeautifulSoup (Optional)

## Usage

1. Ensure Python and required dependencies are installed.
2. Download and install the Chrome WebDriver compatible with your Chrome browser version.
3. Adjust the `keyword` and `num_pages` variables within the script to match your search criteria.
4. Run the script using the command `python skills_scraper.py`.

## Notes

- This script is intended for educational and research purposes only. Ensure compliance with LinkedIn's terms of service and robots.txt guidelines.
- Consider incorporating rate limiting and error handling mechanisms to avoid server overload and potential blocking.
- Customize the list of skills to match specific job requirements or industries.
