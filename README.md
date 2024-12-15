# Electric Vehicle  Analysis and Visualization

This project provides an analysis and visualization of electric vehicle (EV) adoption trends using a comprehensive dataset. 
The focus is on understanding market size, growth patterns, technological advancements, and consumer preferences in the EV industry.

---

## Key Performance Indicators (KPIs)
The analysis focuses on the following metrics:

1. **Total Vehicles**:
   - Quantifies the overall landscape of electric vehicles, encompassing both Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).

2. **Average Electric Range**:
   - Calculates the average electric range of vehicles, offering insights into advancements in EV technology.

3. **Total BEVs and % of Total BEVs**:
   - Total count of Battery Electric Vehicles and their share as a percentage of the overall EV market.

4. **Total PHEVs and % of Total PHEVs**:
   - Total count of Plug-in Hybrid Electric Vehicles and their share as a percentage of the overall EV market.

---

## Visualization Insights
The project incorporates the following visualizations for deeper insights:

1. **Total Vehicles by Model Year (From 2010 Onwards)**:
   - A line/area chart illustrating the growth pattern and adoption trends of EVs over time.

2. **Total Vehicles by State**:
   - A map chart showcasing the geographical distribution of EVs across states to identify regions with higher adoption rates.

3. **Top 10 Total Vehicles by Make**:
   - A bar chart highlighting the most dominant EV manufacturers based on the number of vehicles.

4. **Total Vehicles by CAFV Eligibility**:
   - A pie/donut chart depicting the proportion of vehicles eligible for Clean Alternative Fuel Vehicle (CAFV) incentives.

5. **Top 10 Total Vehicles by Model**:
   - A tree map visualizing the most popular EV models, reflecting consumer preferences.

---

## Dataset Details 
The dataset includes information about:
- Vehicle specifications (Make, Model, Year, Type, Range, MSRP).
- Geographic and demographic details (State, County, City, Legislative District).
- Performance metrics (Electric Range, CAFV Eligibility).

---

## Tools and Technologies
- Power BI
- DAX

---

## Methods 
**1.Data Preparation:**
- Non-essential columns were removed to streamline the dataset and ensure relevance to the analysis objectives.
- The dataset was thoroughly inspected for errors, discrepancies, and missing values. Necessary data cleaning procedures were applied to maintain accuracy and consistency.

**2.Measure Creation:**
- Custom measures were developed using DAX queries to align with the analytical requirements. These measures facilitated detailed insights and supported advanced visualizations.

**3.Dashboard Development:**
- A variety of visual charts, including line charts, bar charts, pie charts, and maps, were created to address the specified requirements.
- Each visualization was designed to present the data in an intuitive and insightful manner, ensuring clarity and ease of interpretation for end users.
---

## Key Observations and Insights

**1. Adoption Trends:**
- The adoption of electric vehicles (EVs) was relatively low at the start of 2011. However, it has shown significant growth over the years, indicating a steady shift in consumer preferences toward sustainable transportation.

**2. Top Manufacturers:**
- Tesla has emerged as the leading manufacturer, producing over 69,000 EVs, showcasing its dominance in the electric vehicle market.
- In contrast, Jeep has the lowest production numbers among the top 10 EV manufacturers, highlighting its smaller footprint in the EV segment.

**3. Geographical Distribution:**
- The state of Washington leads in EV adoption, with significantly higher usage compared to other states, reflecting strong regional demand for electric vehicles.

**4. Consumer Preferences:**
- A noticeable trend is the consumer preference for hybrid vehicles (Plug-in Hybrid Electric Vehicles or PHEVs) over fully electric models (BEVs). This suggests a transitional approach as consumers adapt to electric mobility.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/electric-vehicle-analysis.git
