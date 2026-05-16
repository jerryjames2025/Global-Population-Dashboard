# Global-Population-Dashboard

📌 Project Overview
 
This project presents an interactive Power BI dashboard analyzing global population trends across 195+ countries and 6 continents over a span of 55 years (1970–2025). It explores growth patterns, population density, continental distribution, and future projections — translating raw demographic data into actionable visual insights


🎯 Objectives

Identify countries with the highest population growth over 55 years
Analyze continental population distribution over time
Highlight countries with extreme population density relative to land area
Forecast which nations will be the biggest contributors to future global growth
Compare population trends between developed and developing countries


📁 Dataset Information

Field         Description

Country       Nation-level records for all continents
Continent     Grouped into 6 global regions
Population    DataYear-wise figures from 1970 to 2025
Growth Rate   Annual percentage increase per country
Area (km²)    Land area for density calculations
Density       Population per km² of land area

Source: Kaggle – World Population Dataset


🛠️ Tools & Technologies

Tool                            Purpose    

Power BI Desktop                Dashboard creation & interactive visualization
Power Query (M)                 Data import, cleaning & transformation
DAX(Data Analysis Expressions)  Custom KPIs, calculated columns & measures
Kaggle                          Source dataset


🔄 Data Preparation Steps

Import — Loaded the Kaggle dataset into Power BI via Power Query
Cleaning — Removed null values, corrected data types, standardized country/continent names
Transformation — Unpivoted year columns into rows; added calculated growth columns
DAX Measures — Built custom KPIs: Total Population, Growth Rate %, Density per km², YoY Change
Dashboard Design — Structured report pages with slicers, filters, charts, and KPI cards


❓ Analytical Questions Addressed

Q1 — Highest Population Growth (1970–2025)

Which countries experienced the highest population growth?

India and China recorded the largest absolute gains over 55 years
Developing nations contributed the majority of global growth
Rapid expansion puts pressure on food, water, and infrastructure

Q2 — Continental Population Distribution

How does population distribution vary across continents?

Asia dominates with 60%+ of global population
Africa shows the steepest upward trajectory
Europe's growth is the slowest among all continents

Q3 — Population Density vs. Land Area

Which countries have high density despite smaller land area?

Bangladesh and Singapore have extreme density relative to size
High-density nations face critical urban and resource challenges
Infrastructure management becomes a top national priority

Q4 — Future Population Contributors

Which countries will drive future global population by 2025?

India surpasses China as the world's most populous nation
Nigeria and Pakistan are among the fastest-growing large countries
Sub-Saharan Africa will drive the majority of 21st-century growth

Q5 — Developed vs. Developing Countries

What are the trends between developed and developing nations?

Developing countries grow significantly faster than developed ones
Developed nations show near-flat population curves post-2000
Economic development strongly correlates with declining fertility rates


📊 Dashboard KPIs
KPI                           Value
🌍 World Population (2025)    8.1 Billion
📅 Data Start Year            1970
🗺️ Countries Covered          195+
🧭 Continents Analyzed        6
📈 Time Span                  55 Years


📂 Repository Structure

📦 global-population-dashboard
 ┣ 📊 Global_Population_Dashboard_JerryJames.pptx   # Project presentation
 ┣ 📁 data/
 ┃ ┗ 📄 world_population.csv                         # Raw dataset (from Kaggle)
 ┣ 📁 dashboard/
 ┃ ┗ 📄 population_dashboard.pbix                    # Power BI dashboard file
 ┣ 📄 README.md                                       # Project documentation
 

 💡 Key Takeaways

📊 The dashboard successfully highlights demographic trends and regional shifts over 55 years
🌍 Asia leads in absolute numbers; Africa shows the steepest growth trajectory
🏙️ Nations like Bangladesh & Singapore face critical urban and resource pressures
🔮 India, Nigeria, and Pakistan will be key drivers of future global population growth


🚀 How to Use

Clone this repository :   git clone https://github.com/your-username/global-population-dashboard.git
Open population_dashboard.pbix in Power BI Desktop
Refresh the data source if needed (point to data/world_population.csv)
Explore the interactive visuals, slicers, and filters

👤 Author
Jerry Jame
📧 jerryjamesjerryjames923@gmail.com
🔗 www.linkedin.com/in/jerry-james-2791791b9
🐙 github.com/jerryjames2025


📜 License
This project is open-source and available under the MIT License.


"Data is the new oil — refined well, it powers the world."

