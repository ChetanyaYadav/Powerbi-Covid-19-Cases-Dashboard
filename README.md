# Powerbi-Covid-19-Cases-Dashboard
Here i have power-bi project assignment based on covid-19 cases.This Power BI project focuses on analyzing and visualizing the impact of the COVID-19 pandemic using multiple datasets related to confirmed cases.

Report Title: COVID-19 Impact & Vaccination Progress Dashboard

1.	India_COVID_Cases.csv – Daily/total confirmed, active, recovered, and death cases in India.
2.	Global_Vaccination.csv – Vaccination doses administered worldwide by country.
3.	Case_Time_Series.csv – Timeline of confirmed, recovered, and death cases globally/India.
________________________________________
📊 Page 1: COVID-19 India Overview
KPIs:
•	🧪 Total Confirmed Cases (India)
•	💚 Total Recovered Cases
•	🏥 Active Cases (Calculated: Confirmed - Recovered - Deaths)
•	⚰️ Total Deaths
Visuals:
•	Line Chart: Daily trend of Confirmed vs Recovered vs Deaths
•	Stacked Area Chart: Active vs Recovered vs Deaths over time
•	Map (Optional): Indian states with confirmed cases (if state-wise data is available)
Filters/Slicers:
•	Date
•	State (if applicable)
________________________________________
📊 Page 2: Global Vaccination Progress
KPIs:
•	🌍 Total Doses Administered
•	💉 Countries with Highest Vaccination Rates
•	💯 Fully Vaccinated Population (if available)
Visuals:
•	Bar Chart: Top 10 countries by total vaccine doses
•	World Map: Vaccination data by country
•	Pie Chart or Donut Chart: Share of total vaccinations by region
Filters/Slicers:
•	Continent
•	Country
•	Date
________________________________________
📊 Page 3: COVID-19 Trends Over Time
KPIs:
•	📆 7-Day Moving Average of Cases (Optional DAX Measure)
•	⏳ Peak Infection Period
Visuals:
•	Line Chart: New cases per day (India + Global)
•	Bar/Column Chart: New deaths per day
•	Slicer: Country selector to compare multiple countries’ case trends
________________________________________
📊 Page 4: Comparative Analysis
Visuals:
•	Table or Matrix: Compare India vs USA vs Brazil (or any top affected countries)
•	Clustered Bar Chart: Vaccination Rate vs Case Fatality Rate (per country)
•	Bubble Chart: Cases vs Deaths vs Vaccination Rate (by population size)
________________________________________
📊 Page 5: Key Insights & Recommendations (Optional)
Text Cards or Tiles:
•	Insight 1: When did India reach peak daily cases?
•	Insight 2: Has vaccination reduced death rates?
•	Insight 3: Which countries controlled the spread most effectively?
You Can Add:
•	DAX measures like:
DAX
CopyEdit
ActiveCases = [ConfirmedCases] - [RecoveredCases] - [Deaths]
CaseFatalityRate = DIVIDE([Deaths], [ConfirmedCases])
VaccinationRate = DIVIDE([VaccinatedPeople], [Population])
________________________________________
🖌️ Design Suggestions
•	Use consistent color themes:
o	Red (Deaths), Green (Recovered), Blue (Confirmed), Yellow (Vaccinated)
•	Apply background gradients or card visuals for KPIs
•	Keep slicers at the top or left sidebar for clean interaction

