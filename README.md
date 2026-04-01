🚦 Road Accident Analysis Dashboard (2018–2020)

📘 Overview
This project presents an interactive Power BI Dashboard designed to analyze road accident data from 2018 to 2020.  

The dashboard follows a data storytelling approach, where users can quickly understand accident trends, severity, causes, and geographical distribution - all in a single-page view for fast decision-making.

🎯 Objectives
  - Quantify total number of accidents (events)  
  - Analyze accidents by hour, day of week, and season
  - Evaluate fatalities and injury severity levels  
  - Identify the Top 7 causes of accidents  
  - Highlight high-impact accidents (>3 victims)  
  - Visualize accidents using geographical mapping  
  - Enable filtering by year, month, and classification  

🧩 Dashboard Structure (Story Flow)

  🔝 1. KPI Summary (Top Section)
      - Total Accidents  
      - Fatalities  
      - Total Injuries  
      - Minor Injuries  
      - Serious Injuries  
      - No Injuries  
      - Accidents with >3 Victims  
  👉 KPI cards are placed at the top for quick overview


  ⏱️ 2. Time-Based Analysis
      - Accidents by Hour (Area Chart) → Identifies peak hours  
      - Accidents by Day of Week (Line Chart) → Highlights risky days  
      - Accidents by Season (Donut Chart) → Shows seasonal variation  

  📊 3. Cause Analysis
      - Top 7 Causes of Accidents (Bar Chart) → Helps identify major contributing factors  

  ⚠️ 4. Severity Analysis
      - Stacked Column Chart:
      - Fatalities  
      - Serious Injuries  
      - Minor Injuries  
      - No Injuries   
    👉 Enables comparison of accident impact levels  

 📍 5. Geographical Analysis
      - Map Visualization (Latitude & Longitude) → Shows accident-prone locations  

  🔄 6. Comparison Analysis
      - Clustered Bar Chart: Accident Type vs Classification → Compare all accident types in one view (diversification requirement)  

  📈 7. Trend Analysis
      - Monthly Accident Trend (Line Chart) → Detect patterns and seasonal spikes  

  🛣️ 8. Additional Insights
      - Accidents by Road Direction  
      - Accidents by Location Type  


🧠 Key KPIs

  🚗 Total Accidents → Number of accident events 
  ☠️ Fatalities → Total deaths
  🤕 Total Injuries → Total injured persons 
  🟡 Minor Injuries → Non-critical injuries 
  🔴 Serious Injuries → Critical injuries 
  🟢 No Injuries → Safe cases 
  ⚠️ Accidents >3 Victims → High-impact accidents 


⚙️ Tools & Technologies
  - Power BI Desktop  
  - DAX (Data Analysis Expressions)  
  - Power Query (ETL & Data Cleaning)  
  - Microsoft Excel  


📊 Design Principles Applied
  - Single-page dashboard (no scrolling)  
  - KPI-focused top layout  
  - Clean and minimal visuals  
  - Consistent color theme  
  - Proper chart selection (bar for comparison, line for trends)  

  👉 Bar charts are used for comparison and line charts for trends as recommended in best practices  


📂 Dataset Includes
  - Date & Time  
  - Location (State, Municipality)  
  - Latitude & Longitude  
  - Accident Type & Classification  
  - Cause of Accident  
  - Road Direction  
  - Number of People Involved  
  - Fatalities, Injuries, Uninjured  


📌 Key Insights
  - Identified peak accident hours and high-risk days  
  - Major accident causes highlighted  
  - Severity distribution analyzed  
  - High-impact accidents (>3 victims) tracked  
  - Accident hotspots visualized  


📌 Conclusion
  - This dashboard provides a **complete analytical solution** by combining **time, severity, cause, and location analysis** into a single interactive view.  

  It enables stakeholders to quickly identify risks, patterns, and areas for safety improvement.
