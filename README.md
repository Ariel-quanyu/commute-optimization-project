# Melbourne Traffic Pattern Analysis

## 1. Data Source
- **Dataset**: Simulated SCATS traffic detector data (V00–V95) for Melbourne intersections.
- **Note**: The station IDs and locations are anonymised and randomly generated to protect real SCATS site data.
- **Time Coverage**: Multiple weeks of 15-min interval counts.
- **Metrics**: Detector counts, aggregated into `total_volume` per site per interval.

---

## 2. Methodology
1. **Data Cleaning**
   - Filled missing values with 0 and set negative counts to 0.
   - Aggregated detector counts (`V00–V95`) into `total_volume`.
   - Removed duplicate site–timestamp records.
   - Validated data consistency with summary statistics and histograms.

2. **Exploratory Analysis**
   - Ranked sites by total traffic volume.
   - Selected top 2 busiest intersections for deeper analysis.
   - Generated hourly–day-of-week heatmaps to identify congestion patterns.

---

## 3. Key Insights

### Location A
- Peak congestion during weekday **morning (7–9 AM)** and **evening (4–6 PM)** commute hours.
- Traffic pattern suggests **commuter and school-related** demand.
- Low weekend volumes.

### Location B
- Consistently high traffic from **morning to evening**, across **all days**.
- Sustained **weekend peaks**, likely due to **shopping centres or event venues**.
- Traffic pattern suggests a **mix of commuter, commercial, and recreational** demand.

---

## 4. Applications
- **Location A**: Optimise weekday peak-hour signal timings to improve commuter flow.
- **Location B**: Implement adaptive signal control to handle prolonged high traffic volumes.
- Use patterns for **event planning, targeted congestion relief, and road maintenance scheduling**.

---

## 5. Summary
This analysis highlights two distinct congestion profiles:
- **Location A** – Short, high-intensity commuter peaks.
- **Location B** – All-day, multi-purpose traffic demand.

Understanding these patterns allows traffic authorities to **apply location-specific strategies**, improving network efficiency while minimising unnecessary interventions.


