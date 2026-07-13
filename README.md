# NYC Restaurant Inspections Data Analysis
---
## Introduction 
New York City is home to thousands of restaurants inspected annually by the Department of Health and Mental Hygiene (DOHMH). This project analyzes DOHMH inspection records from 2016–2026 to understand how often Critical Violations occur, what drives them, and where NYC's food-safety efforts should focus next.

---
## Data Source
The dataset used in this project is sourced from the official **NYC Open Data** portal:
[NYC Open Data - DOHMH Restaurant Inspections](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/data_preview)

---
## NYC DOHMH & Scoring System
The **NYC DOHMH** (the New York City Department of Health and Mental Hygieneconducts) strict, unannounced field inspections of restaurants to enforce food safety codes and protect public health. 
* During inspections, observed failures are converted into **sanitary penalty points**.
* Cumulative points directly determine the restaurant's public letter grade (**Fewer points = Cleaner kitchen**):
  * **Grade A :** 0 – 13 pts
  * **Grade B :** 14 – 27 pts
  * **Grade C :** 28+ pts
---
 ## Key finding
-  Critical Violations are not a small issue — they're the biggest factor behind low hygiene scores, raising penalty scores by over 35%
- Food safety issues aren't limited to one area — all five boroughs fall within a close 51%–56% range for Critical Violations
- Critical violations jumped to their highest point in 2022 (52.4%), then dropped and leveled off around 49.6% in 2023–2025. The data doesn't show why this happened, so it's worth looking into further.
-  Violation rates stay steady all year (47%–52%), suggesting the time of year doesn't have a big effect on kitchen compliance.
-  Large brands like McDonald's and Starbucks kept steady, low-risk scores over time. Smaller chains like Kennedy Fried Chicken saw a sharp drop in compliance, with scores jumping from about 7.5 to 28.3.

  ---
## Recommendations
- **Focus on the top 3 violation types (10F, 08A, 10B)** they make up the bulk of all violations, so targeted training here goes further than blanket inspections.

- **Treat this as a citywide problem** not a borough problem. Critical violation rates only vary by 4.5 points across boroughs (51.3%–55.8%), so borough-specific fixes won't move the needle much.

- **Keep a closer eye on chains like Kennedy Fried Chickenand Golden Krust** Their scores are high, and some are getting worse — checking one location at a time isn't catching the full problem.

- **Figure out what changed around 2023** that brought violation rates down from a 2022 peak (52.4%) to a stable ~49.6% — and double down on it.
