Wealth & Health: 60 Years of Global Progress (1960-2023)
📊 Project Overview
This project is a visualization of the connection between economic success (GDP per capita) and human happiness 
(life expectancy) in 214 countries from 1960 to 2023. Through the use of data from the World Bank, this project
is an interactive animated scatter plot in the traditional Gapminder style, which shows how the world has changed over the last 60 years.
"Watch as countries move across the screen as they get richer and longer-lived—so you don't just see where we are, you see how we got here."

📁 Repository Structure
Midterm_Dataviz/
│
├── README.md                                                 # This file
├── Midterm_Dataviz.ipynb                                      # Complete analysis notebook
├── API_NY.GDP.PCAP.CD_DS2_en_csv_v2_46.csv                    # GDP per capita data
├── API_SP.DYN.LE00.IN_DS2_en_csv_v2_128.csv                   # Life expectancy data
├── Metadata_Country_API_NY.GDP.PCAP.CD_DS2_en_csv_v2_46.csv   # Country metadata (GDP)
├── Metadata_Country_API_SP.DYN.LE00.IN_DS2_en_csv_v2_128.csv  # Country metadata (life expectancy)
├── Metadata_Indicator_API_NY.GDP.PCAP.CD_DS2_en_csv_v2_46.csv # Indicator metadata (GDP)
└── Metadata_Indicator_API_SP.DYN.LE00.IN_DS2_en_csv_v2_128.csv # Indicator metadata (life expectancy)

🚀 How to Run
In Google Colab (Recommended)
Open Midterm_Dataviz.ipynb in Google Colab
Run all cells
Upload the required CSV files when prompted
The visualization will automatically be created
Required Files
All the CSV files present in the repository are required.

📈 Key Findings
Insight	What I Found
Global progress	Life expectancy: 52.3 → 73.8 years (+21.5)
Asia's miracle	East Asia gained 28.4 years (China: 36 → 78)
Africa's struggle	Still behind Europe 1960 levels despite gains
COVID-19 shock	Global life expectancy dropped 1.8 years
Money vs health	Cuba matches US life expectancy on 1/7 the budget

📊 Data Sources
All data from World Bank Open Data:
Life expectancy at birth – SP.DYN.LE00.IN
GDP per capita (current US$) – NY.GDP.PCAP.CD
Country metadata – Regional classifications
Time period: 1960-2023
Countries/regions: 214
Total observations: 11,366

How to View the Visualization
The main output is an HTML file that is interactive and is produced after the notebook is run. After the entire notebook has been run, the following files are produced:
gapminder_animation.html – Main Interactive Visualization
comparison_1960_2023.png – Static Image Comparison
To run the interactive version:
Run the entire notebook
Locate the file in your Colab environment
Download and open in any web browser

⚠️ Limitations
GDP per capita hides inequality within countries
Life expectancy doesn't capture quality of life
Conflict zones have missing data
COVID-19 data is still provisional
Regional averages hide outliers

💭 What I Learned
Data cleaning is 80% of the work
The story is in the outliers
Animation is necessary, not just cool
Context turns numbers into meaning
Progress is real but fragile



