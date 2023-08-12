# website_scraping

In my project titled "Website Scraping," I employed a comprehensive approach utilizing various libraries such as BeautifulSoup, regex, and pyphen to effectively clean and scrape data. My primary objective was to extract valuable information from the website 'blackcoffer' while ensuring data quality.

The process began with web scraping, extracting data through BeautifulSoup while also employing regex and pyphen libraries for targeted data cleaning. To prevent repetitive scraping, I saved the extracted data into an Excel file for future use.

Afterward, I implemented a data filtering step to isolate the relevant content. I initiated the filtering process from a specific sentence-containing row while excluding the last two rows containing citation information. This refined data was then saved into a CSV file, setting the stage for further processing.

In the subsequent phase, I performed data extraction from a stopword file and consolidated them into a single entity. This consolidation facilitated the subsequent removal of stopwords from the data. Additionally, I created separate files for positive and negative stopwords, which were instrumental in calculating positive and negative scores.

The project's pinnacle phase was marked by importing the previously generated website content data, stored as 'Website Content.csv.' Rigorous data cleaning was achieved through regex, enabling the removal of specific characters. Following the cleaning process, I conducted data analysis to derive essential variables as per the desired output format.

Finally, the processed and refined data was exported in CSV format, culminating the project's execution. The utilization of BeautifulSoup, regex, and pyphen, coupled with strategic data handling steps, allowed for the successful extraction, cleaning, and utilization of website data for valuable insights.
