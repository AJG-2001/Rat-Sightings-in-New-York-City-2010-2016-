**Rat Sightings in New York City (2010–2016)**

📌 Project Overview

This project analyzes New York City rat sightings recorded from 2010 to 2016, using the publicly available NYC 311 Animal Sightings dataset. The objective was to clean and structure the raw dataset (>100,000 rows) and use R with ggplot2 to create a clear, engaging visualization that highlights temporal and geographic trends in sightings
.

The final visualization shows borough-level trends with a clear highlight of the peak in 2016, illustrating how rat activity varies across NYC’s five boroughs.

🔎 Data Preparation
Cleaning & Preprocessing

Handled missing values (NA, N/A) during import.

Converted Created Date to proper datetime format using lubridate.

Extracted temporal features: sighting_year, sighting_month, and sighting_weekday.

Standardized dwelling/location types into four broader categories: Residential, Commercial, Public Spaces, Industrial/Other.

Aggregated sightings by borough and year for time-series visualization
.

🛠️ Visualization Design
Final Graphic

Type: Multi-line chart of yearly rat sightings by borough (2010–2016).

Highlights:

Vertical dashed line at 2016 peak.

Annotation label (“Peak in 2016”) for Brooklyn, the borough with the highest sightings.

Distinct colors per borough for easy comparison.

Larger points on each year for emphasis
.

Design Principles Applied

CRAP Framework:

Contrast: Distinct borough colors, red highlights for peak year.

Repetition: Consistent font styles, axis labels, and gridlines.

Alignment: Titles, subtitles, and legends consistently aligned.

Proximity: Peak annotation placed close to Brooklyn’s line without clutter.

Kieran Healy’s Principles:

Clear, truthful, functional, and insightful visualization of borough-level trends.

Alberto Cairo’s Five Qualities:

Truthful, functional, beautiful, insightful, and educational
.

📊 Key Insights

Overall Trend: Rat sightings rose steadily from 2010, peaking in 2016 across most boroughs.

Brooklyn & Manhattan: Consistently reported the highest sightings.

Staten Island: Lowest sightings, but still exhibited upward trends.

Urban Context: Peaks may align with construction activity, seasonal conditions, or reporting changes in NYC
.

🗂️ Deliverables

Assignment_A1.Rmd – R Markdown with full code, cleaning, and visualization.

A1_final.pdf – Memo report with analysis, visualization, and discussion of design principles.

A1_final.png / A1_final.pdf – Final standalone visualization outputs.

README.md – This project overview (this file).

🚀 Key Takeaways

Data visualization is most effective when cleaning, aggregation, and storytelling are integrated.

Rat sightings in NYC showed a clear upward trend, emphasizing urban rodent management challenges.

By applying visualization best practices, the project transforms raw 311 data into actionable urban insights.
