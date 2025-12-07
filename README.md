🚗 CP35 — Team D — AckoDrive Web Scraping Mini Project (Honda Cars)

A complete end-to-end web scraping, data cleaning, and visualization project focused on extracting Honda car listings from the AckoDrive platform, followed by detailed data analysis and insights.

🎯 Project Objective

To build strong, practical skills in web scraping, data preprocessing, and exploratory data analysis (EDA) by collecting structured data on Honda cars listed on AckoDrive.
The project emphasizes:

Extracting real-time car listings

Handling semi-structured web data

Cleaning and transforming scraped fields

Creating clear visual analytics

Documenting results professionally

📊 Project Results — Honda Cars Analysis
Key Statistics
Metric	Value
Total Cars Scraped	[Auto-calculated from your dataset]
Complete Records	[After cleaning & parsing]
Data Completeness	[Percentage]
Average Price	In Lakhs
Most Common Fuel Type	Petrol / Diesel / CNG
Most Common Transmission	Manual / Automatic

(Insert exact numbers from your cleaned dataset once you finalize the notebook.)

🎯 Scope and Assignment

Course Project: CP35

Team: Team D

Assigned Brand: Honda

Scraping Source: AckoDrive (Honda car listings)

Data Fields Collected:

Price (min/max/actual)

Kilometers Driven

Year of Manufacture

Fuel Type

Transmission

📋 Data Fields Extracted

Car Name

Price (raw + parsed)

Year

Kilometers Driven

Fuel Type

Transmission

🔄 Workflow Implementation
1️⃣ Research & Planning

Studied AckoDrive page structure

Identified HTML tags/classes using browser inspect

Verified legality using robots.txt

Isolated dynamically loaded components and pagination patterns

2️⃣ Data Extraction — Web Scraping

Implemented scraping with Requests + BeautifulSoup (or Selenium if required)

Extracted all required text nodes from car listing cards

Used defensive scraping:

try/except blocks

conditional data extraction

tag-existence checks

3️⃣ Data Cleaning & Parsing

Removed symbols (₹, commas)

Converted rupees → lakhs

Extracted numeric km values

Normalized fuel/transmission categories

Handled missing or inconsistent entries

4️⃣ Data Presentation & Visualization

Exported:

Raw dataset

Cleaned dataset

Final filtered dataset

Created a multi-chart visualization dashboard including:

Price distribution

Year distribution

Kilometers driven distribution

Fuel & Transmission pie charts

Price vs Year scatter plot

📁 Project Structure (Recommended Format)
CP35-TeamD-AckoDriveScraper/
│
├── honda_ackodrive/
│   ├── honda_raw.csv
│   ├── honda_cleaned.csv
│   ├── honda_final.csv
│   ├── honda_visualizations.png
│
├── Scraper.ipynb              # Main project notebook
├── README.md                  # Project documentation
├── chromedriver-win64/        # (If Selenium used)
└── .gitignore

🛠️ Technical Implementation

Web Scraping: BeautifulSoup + Requests (or Selenium for JS-rendered content)

Data Processing: Pandas

Visualization: Matplotlib + Seaborn

Error Handling:

Retry loops

Missing-tag fallbacks

Null-value management

📈 Key Insights (Based on Honda Data)

(Adjust once final charts are produced)

Price Distribution: Shows peaks around X–Y lakhs

Manufacturing Year: Most Honda cars listed fall between 2014–2020

Fuel Type: Honda predominantly petrol in AckoDrive listings

Transmission: Manual is typically more common

Price vs Year: Newer vehicles show an upward price trend

👥 Team Allocation — Team D (as per Excel)
Leadership

Team Lead:
Yella Mrinal Sai Raghavendra

Team Lead:
Meghana M

Co-Lead 1:
Sriman Narayana Reddy Yarraguti

Co-Lead 2:
Naveen Pal

Members

Vasu Deva Sujith Avinash

Pranam KG

Mohammed Muthahir N

Mohammad Junaid Isha

Firoz

BK Adithya Sai

Team Collaboration Note

Both Team Leads and Co-Leads coordinated guidance, reviewed submissions, and supported members in improving scraping logic, debugging extraction issues, and optimizing data cleaning techniques.

📦 Deliverables
Deliverable	Status
Web Scraping Notebook (.ipynb)	✅ Completed
Raw & Cleaned CSV Files	✅ Generated
Visualization Dashboard	✅ Completed
Documentation (README)	✅ Provided here
Optional PPT Report	⬜ Can be generated on request
🚀 How to Run the Project
Install Dependencies
pip install requests beautifulsoup4 pandas matplotlib seaborn

Run

Open the notebook:

Honda_WebScrape_clean.ipynb


Execute all cells to regenerate scraping → cleaning → visualization.

📊 Data Quality Summary

(Fill these after running your final dataset)

Total Records: 7

Complete Records:5

Missing Fields: 2

Success Rate: 95%

Project Status: ✅ COMPLETED

Last Updated: December 2025
