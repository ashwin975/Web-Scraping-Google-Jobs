# Web-Scraping-Google-Jobs

![Python Badge](https://img.shields.io/badge/Made%20with-Python-blue.svg)
![Selenium Badge](https://img.shields.io/badge/Selenium-Web%20Scraping-green.svg)
![Pandas Badge](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow.svg)

- This Python script uses the Selenium library to automate a web browser (in this case, Chrome) to scrape job listings from Google's job search results. 🌐🔍

- It takes a list of job roles and companies, constructs a Google search URL for each combination, and navigates to that page. 📝🔗

- It then scrolls through the page to load all job listings, and for each listing, it clicks on the listing to load the job details. 🔄💼

- The details are then extracted and stored in a dictionary, which includes the job ID, company, role, location, posted date, description, and the URL of the job listing. 📋🔍📝

- This process is repeated for each combination of job role and company. Finally, all the collected job data is converted into a pandas DataFrame for further analysis or storage. 🔁📊🔍
