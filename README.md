# How Hotel Demand Builds: Booking Pace & Pickup Analysis

A step-by-step hospitality revenue analytics learning guide and empirical study examining how hotel demand builds across lead times, pace curves, pickup heatmaps, market segments, and group booking blocks, using **75,166 stayed reservations** across a City Hotel and a Resort Hotel[cite: 5, 6].

---

## Repository Contents

* **`Hotel_Pace_and_Pickup_Learning_Guide.pdf`**: A 14-page step-by-step learning guide covering core revenue management vocabulary, worked examples, a 10-step analytical methodology, executive interpretations, and a self-check quiz[cite: 5, 18].
* **`hotel_bookings demand.csv`**: The underlying booking dataset containing **119,390 total reservations** and **32 variables** for arrival dates from **July 2015 to August 2017** (Antonio, Almeida & Nunes, 2019)[cite: 5, 8].

---

## Key Analytical Findings

* **Booking Window Distribution:** Half of all stayed bookings are made within **45 days** of arrival (median), while the mean lead time is **80 days** due to a long tail of early bookings[cite: 6, 9]. Nearly **1 in 4 bookings (23.7%)** arrives within 7 days of check-in, and **7.9%** are booked on the arrival day[cite: 9].
* **City Hotel vs. Resort Hotel:** The City Hotel (`46,228` stayed bookings; `EUR 105.7` avg ADR) has a median lead time of **50 days**, whereas the Resort Hotel (`28,938` stayed bookings; `EUR 90.8` avg ADR) books closer to arrival with a **38-day** median lead time and **28.9%** last-7-day pickup[cite: 12].
* **Weekend vs. Weekday Arrivals:** Weekend arrivals (Fri to Sun) commit roughly 10 days earlier at the median (**51 days**) than weekday arrivals (**41 days**)[cite: 13].
* **Market Segment Timetables:** Median lead times separate customer segments sharply, ranging from **3 days** (Aviation and Complementary) and **6 days** (Corporate) to **11 days** (Direct), **43 days** (Online TA), **90 days** (Offline TA/TO), and **107 days** (Groups)[cite: 15]. Online TA and Direct achieve the highest average ADR (**EUR 113.9**)[cite: 15].
* **ADR Across the Booking Window:** Same-day bookings carry the lowest average rate (**EUR 82.8**), while rates peak for bookings made **8 to 180 days** ahead (**EUR 104.0 to EUR 106.2**)[cite: 16].
* **What Drives Peak Arrival Dates:** Analysis of the 10 busiest arrival dates (`181 to 255` bookings per day) reveals that peak demand is driven by single contracted **Groups** or **Offline TA/TO** blocks ranging from **26 to 122 rooms** booked on a single day[cite: 17].

---

## Guide Structure

1. **Part 1: Foundations.** Core revenue management definitions (`Stayed Booking`, `Lead Time`, `Pace`, `Pickup`, `Pace Curve`, `Block Booking`, `Heatmap`) and worked examples[cite: 5, 6, 7].
2. **Part 2: Ten-Step Analysis.**
   * **Step 1:** Data preparation, date reconstruction (`booking_date = arrival_date - lead_time`), and filtering to realized `Check-Out` stays (`75,166` rows)[cite: 8].
   * **Step 2:** Booking window histogram and cumulative lead-time distribution[cite: 9].
   * **Step 3:** Single-date pace curve deep dive (`5 December 2015`, `255` stayed bookings)[cite: 10].
   * **Step 4:** August 2017 daily pickup heatmap (`0 to 120` days out)[cite: 11].
   * **Step 5:** City Hotel vs. Resort Hotel timing and ADR comparison[cite: 12].
   * **Step 6:** Weekend vs. weekday arrival behavior[cite: 13].
   * **Step 7 & 8:** Market segment pickup curves and one-page segment profiles[cite: 14, 15].
   * **Step 9:** ADR behavior across lead-time buckets[cite: 16].
   * **Step 10:** Decomposition of the 10 busiest arrival dates and block-booking spikes[cite: 17].
3. **Part 3: Putting It Together.** Revenue manager decision matrix, methodological caveats, and a 6-question self-check quiz with solutions[cite: 5, 18].

---

## Data Source & Attribution

* **Dataset Reference:** Antonio, N., Almeida, A., & Nunes, L. (2019). *Hotel booking demand datasets*.
* **Author:** Hosea Ngo Sali, Hotel Revenue Analyst (M.A. International Tourism Development)
