# How Hotel Demand Builds: Booking Pace and Pickup Learning Guide

A step-by-step educational resource for hospitality students, revenue analysts, and hotel professionals to master booking lead times, demand pace curves, pickup heatmaps, market segment clocks, and group block dynamics using real booking data (75,166 stayed reservations across a City Hotel and a Resort Hotel from July 2015 to August 2017).

---

## Repository Files and Direct Links

* **[Hotel Pace and Pickup Learning Guide (PDF)](Hotel_Pace_and_Pickup_Learning_Guide.pdf)** - Complete 14-page step-by-step handbook featuring plain-language definitions, worked mathematical examples, analytical walkthroughs, and a self-check quiz with answers.
* **[Hotel Bookings Demand Dataset (CSV)](hotel_bookings%20demand.csv)** - Raw dataset containing 119,390 booking records and 32 attributes used to build every metric and table in the guide.

---

## What You Will Learn

This guide requires no prior revenue management background. Every concept is introduced in plain language and applied directly to real hotel performance records:

1. **Part 1: Foundations and Worked Examples**
   * Why hotel inventory perishability makes pace and pickup essential for pricing and restriction decisions.
   * Core revenue vocabulary: stayed bookings, derived booking dates, lead time (booking window), cumulative pace curves, pickup velocity, ADR, and block bookings.
   * Worked step-by-step calculations for lead-time derivation, median vs. mean skewness, and cumulative booking shares.
2. **Part 2: Ten-Step Analytical Walkthrough**
   * **Step 1 - Data Preparation:** Filtering 119,390 raw rows to 75,166 honored stays (`Check-Out`) and deriving booking dates from lead times.
   * **Step 2 - Booking Window Distribution:** Understanding right-skewed lead times (45-day median vs. 80-day mean; 23.7% booked within 7 days; 14.1% booked over 180 days ahead).
   * **Step 3 - Single-Date Pace Curve:** Tracing how the busiest arrival date (05 Dec 2015, 255 bookings) built in discrete jumps from contracted group blocks.
   * **Step 4 - Pickup Heatmap:** Reading arrival-date by lead-time grids across August 2017 (3,109 stays) to spot volatile late-pickup dates vs. stable early-built dates.
   * **Step 5 - Property Comparison:** Comparing shares rather than raw counts to uncover why Resort Hotel books closer to arrival (38-day median) than City Hotel (50-day median).
   * **Step 6 - Day-of-Week Clocks:** Contrasting leisure-weighted weekend arrivals (Friday to Sunday, 51-day median) against weekday arrivals (Monday to Thursday, 41-day median).
   * **Steps 7 and 8 - Market Segment Profiles:** Benchmarking segment timelines from Corporate (6-day median) and Direct (11-day median) to Offline TA/TO (90 days) and Groups (107 days).
   * **Step 9 - ADR by Lead Time:** Separating revenue concentration from true rate realization (EUR 82.8 same-day ADR vs. EUR 104.0 to 106.2 between 8 and 180 days out).
   * **Step 10 - Peak Date Anatomy:** Diagnosing the ten busiest arrival dates (181 to 255 stays) to show how single-day Groups and Offline TA/TO blocks drive 38% to 57% of volume on six of the top ten days.
3. **Part 3: Synthesis and Self-Check Quiz**
   * A decision matrix mapping common revenue management questions to the exact analytical views that answer them.
   * Methodological guardrails (honored stays vs. cancellations, derived timestamps, and correlation vs. causation).
   * Six practice questions with worked solutions to test comprehension.

---

## Key Analytical Benchmarks Covered in the Guide

| Metric / Segment | Key Finding | Operational Takeaway |
| :--- | :--- | :--- |
| **Overall Booking Window** | 45-day median; 80-day mean; 7.9% same-day | Report both median and mean to capture late-booking volume and the 180+ day tail |
| **City vs. Resort Timing** | City: 50-day median (EUR 105.7 ADR); Resort: 38-day median (EUR 90.8 ADR) | Normalize by property booking share rather than raw counts to avoid size bias |
| **Weekend vs. Weekday** | Weekend: 51-day median; Weekday: 41-day median | Weekday inventory relies more on final-week pickup (26.5% vs. 20.0%) |
| **Fastest vs. Slowest Segments** | Corporate (6 days) and Direct (11 days) vs. Groups (107 days) | Track segment-level pace curves instead of a single blended hotel curve |
| **Rate by Booking Window** | Same-day: EUR 82.8 ADR; 8 to 180 days: EUR 104.0 to 106.2 ADR | Protect mid-window rates and account for lower same-day rate realization |
| **Top 10 Peak Dates** | 10 single-day blocks account for 683 of 2,203 bookings (31%) | Separate contracted group/trade blocks from transient pickup forecasts |

---

 
