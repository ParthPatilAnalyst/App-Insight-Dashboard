#  App Insight Dashboard – Power BI Project

##  Project Overview

This project analyzes Google Play Store app data to uncover insights about app success factors such as ratings, installs, reviews, category performance, pricing impact, and size optimization.

The interactive Power BI dashboard helps stakeholders understand market trends and make data-driven decisions for app development and marketing strategy.


![image alt](https://github.com/ParthPatilAnalyst/App-Insight-Dashboard/blob/f5c798f41da433ec9d08ad1ea3c49f468f662a3e/1.png)
![image alt](https://github.com/ParthPatilAnalyst/App-Insight-Dashboard/blob/cb31a75ce4849cc2b2293c64c872eb0d71dea0c4/Screenshot%202026-02-19%20072231.png)
![image alt](https://github.com/ParthPatilAnalyst/App-Insight-Dashboard/blob/f5c798f41da433ec9d08ad1ea3c49f468f662a3e/3.png)
---


##  S – Situation

The company acquired a large dataset from the Google Play Store containing 10,000+ apps with attributes such as ratings, installs, reviews, size, category, type (free/paid), and update information.

Management wanted to understand:

* What drives app success?
* Which categories dominate the market?
* Does app size affect installs?
* How do ratings relate to installs and engagement?
* What insights can improve development and monetization strategy?

The dataset required cleaning, transformation, and structured visualization for business-level interpretation.

---

##  T – Task

As a Power BI Developer, my objective was to:

1. Clean and transform raw data for analysis.
2. Develop key performance metrics (KPIs) to measure app success.
3. Build an interactive dashboard with multiple insight pages.
4. Identify actionable insights for product managers and senior leadership.
5. Present findings in a simple and executive-friendly format.

---

##  A – Action

###  1. Data Preparation

* Removed duplicates
* Handled missing ratings
* Converted installs and price columns into numeric format
* Standardized size column (MB conversion)
* Created calculated columns for:

  * Rating Category (Poor, Average, Good, Excellent)
  * Size Category (Small, Medium, Large)
  * Install Segments (Niche, Emerging, Growing, Viral)
  * High Rating Flag (Rating ≥ 4)

---

###  2. Key Measures Created (DAX)

* Total Apps
* Average Rating
* Total Installs (Billions)
* Total Reviews (Millions)
* High Rating %
* Success Score
* Engagement Rate
* Category Install Share

These measures allowed dynamic filtering across all dashboard pages.

---

###  3. Dashboard Pages Designed

###  Page 1 – Executive Overview

* KPI Cards (Apps, Rating, Installs, Reviews, High Rating %)
* Top 10 Categories by Installs
* Free vs Paid Distribution
* Installs by Rating Category
* Size Distribution
* Success Score Gauge

Purpose: High-level market performance summary.

---

###  Page 2 – Category Insights

* Category-level Install & Review Analysis
* Rating Distribution by Category
* Install Segmentation Funnel
* App Type Breakdown (Free vs Paid)
* Top Apps Performance Table

Purpose: Identify strong and weak categories.

---

###  Page 3 – Size vs Installs Analysis

* Scatter Plot (Size vs Installs vs Reviews)
* Category-level comparison
* Insight summary panel

Purpose: Analyze whether app size impacts installs.

---

###  4. Advanced Enhancements

* Interactive slicers (Year, Rating Category, Category)
* Drill-through functionality
* Conditional formatting for ratings
* Log-scale analysis for better visualization
* Custom theme for professional UI
* Insight narration for executive presentation

---

##  R – Result

The dashboard revealed several key insights:

###  1. Market Concentration

Game and Communication categories dominate total installs and engagement.

###  2. Size Does Not Directly Drive Success

Large apps (Games) succeed due to value, not size alone.
Some large categories show moderate installs, proving size alone does not guarantee growth.

###  3. Free Apps Dominate the Market

Over 95% of apps are free, indicating ad-based or freemium models are dominant.

###  4. High Rating Correlates with Install Growth

Apps with ratings ≥ 4 contribute significantly to total installs.

###  5. Medium-Sized Optimized Apps Perform Well

Balanced size apps show better adoption compared to very heavy apps.

---

#  Business Recommendations

* Focus on high-demand categories (Games, Communication).
* Optimize app size for better adoption.
* Maintain rating above 4.0 for competitive advantage.
* Leverage freemium models for higher market penetration.
* Monitor engagement rate alongside installs.

---

#  Tools & Technologies Used

* Power BI Desktop
* DAX
* Data Modeling
* Data Cleaning & Transformation
* Visual Analytics

---

#  Dashboard Preview

The dashboard includes:

 Executive KPI Overview
 Category-Level Deep Dive
 Install Segmentation
 Rating Impact Analysis
 Size vs Popularity Insights

---

#  Key Skills Demonstrated

* Business Intelligence Development
* Data Cleaning & Transformation
* KPI & Metric Development
* Interactive Dashboard Design
* Analytical Storytelling
* Executive-Level Reporting

---

#  Conclusion

This project demonstrates how raw app marketplace data can be transformed into meaningful strategic insights. The dashboard provides a structured and visual decision-support system for product teams, marketing departments, and senior management.

The analysis confirms that app success is driven more by category demand, engagement, and rating quality rather than size alone.


