# Cyclistic Bike-Share Analysis: Converting Casual Riders to Annual Members

## 📌 Executive Summary
This case study analyzes 84,776 distinct trip records from April 2020 to uncover behavioral differences between casual riders and annual members. The primary goal is to provide data-backed marketing strategies to convert high-value casual riders into annual subscribers.

* **Live Tableau Dashboard:** [Insert Your Tableau Public URL Here]
* **Tools Used:** Microsoft Excel (Data Cleaning & Validation), Tableau Public (Aggregations & Interactive Visualization)

---

## 🛠️ Data Pipeline & Methodology
1. **Cleaning & Validation:** Verified row completeness and confirmed `ride_id` serves as a unique primary key across all 84,776 records.
2. **Feature Engineering:** Built time-of-day helper fields and generated a concatenated `Route` field (`Start Station Name` to `End Station Name`).
3. **Safe Aggregation:** Applied `COUNTD(Ride Id)` in Tableau Public to prevent duplicate counting while visualizing top station and route activity.
4. **Interactive Visualization:** Constructed a 3-panel dynamic dashboard with cross-filtering to highlight station and route performance.

---

## 📊 Key Analytical Insights
* **Overall Volume:** Annual members accounted for 73% of top-station trip volume, using major transit hubs consistently.
* **Top Start & End Hubs:** `Clark St & Elm St` led all stations with 850 start rides and 893 end rides.
* **Casual Route Concentration:** Casual riders accounted for 45% of total rides across the top 10 routes.
* **Leisure Patterns:** All top 10 popular routes were same-station round trips, indicating recreational usage by casual riders compared to point-to-point commuter usage by members.

---

## 🎯 Strategic Recommendations
1. **Location-Based Onboarding:** Place physical QR-code signage and conversion offers at top casual start stations, starting with `Clark St & Elm St` (246 casual rides).
2. **Route-Based Upgrade Incentives:** Trigger post-ride digital upgrade discounts for users completing rides on top casual routes like `Wells St & Elm St`.
3. **Targeted Push Notifications:** Schedule promotional conversion messaging during peak casual usage hours identified via time-of-day tracking.

---

## 📁 Repository Structure
