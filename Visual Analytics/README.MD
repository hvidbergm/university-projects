# Course Name: Visual Analtyics (CDSCO1003E)
Project details:
* **Project title** Title: Web Scraping for Automated Market Analysis - Leveraging Google Maps for Decision-Making in the Nordic Hotel Market 
* **Deliverable**: Tableau dashboard based on data scraped from Google maps using a Python script 
* **Tools**: Tableau, Python (Beautiful Soup, Selenium, Pandas), Alteryx

**Exam deliverable**: To build an ETL pipeline and visualise the data using Tableau.

**Hand-in**: Report based on workflow of 1) data gathering, 2) data transformation and 3) dashboard visualisation
1. Using Python and BeautifulSoup4, we built a web-crawler to scrape data on hotels across Nordic capital cities from Google Maps, providing us with an interesting, real-life dataset complete with a large amount of features to derive insights from, as well as a lot of unstructured data which we could build a proper ETL pipeline on. 
2. With the data scraped, we created the ETL workflow in Alteryx, cleaning the data, combining different data sources to enrich the data and derived new features from existing variables.
3. The final dataset we used for our Tableau BI dashboard. The focus of the dashboard was to tailor the information to the target user, an experiened hotel entrepreneur looking to expand in the Nordics, while ensuring the UI and UX allowed for an intuitive and accessible interface. Link to the dashboard on Tableau Public: [link](https://public.tableau.com/app/profile/mads4252/viz/Nordichotelmarketanalysis/Dashboard) (please note that different screen sizes and browsers may interrupt with the layout - tested on a 27" monitor in Microsoft Edge).

**Dashboard**:
![Dashboard front page](imgs/VA_Dashboard_front-page.png)

**Dashboard with the map toggled on**:
![Dashboard map view](imgs/VA_Dashboard_map-view.png)
