# Faculty-Editor-Scraper
A web scraper built to gather information about NC State faculty members who edit Elsevier journals.

This scraping tool searches ScienceDirect and pulls information about journal editors affiliated with NC State University. Uses selenium and pandas to scrape and store information. Users wishing to run this script should ensure these packages are installed. To run, it requires a list of journal titles in either XLSX or CSV format. Spaces in journal titles (ex: Applied Numerical Mathematics) should be replaced with '-' to make titles compatible with URL strings (ex: https://www.journals.elsevier.com/applied-numerical-mathematics). 

This specific code scrapes ScienceDirect, but can be changed to accomodate other publisher websites with basic web scraping knowledge.

For questions, please email kfrazie2@ncsu.edu.
