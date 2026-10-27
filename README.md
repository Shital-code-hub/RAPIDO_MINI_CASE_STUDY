# 🛵 Rapido Ride-Hailing Data Analysis Case Study

## 📌 Project Overview

This repository contains a comprehensive SQL-based case study analyzing operational and transactional data for Rapido, a leading bike-taxi and ride-aggregator platform. The project explores user riding behavior, vehicle preferences (Cab AC vs. Non-AC), driver-customer interactions, and distance segmentations to derive actionable business insights.

📂 Repository Structure & Query Breakdown
The case study is solved across 15 analytical checkpoints covering various dimensions of the business:

User Travel Metrics (Q1, Q3): Evaluates total distance traveled and total ride frequency per user to identify power users (SUM(distance_km) > 20, COUNT(ride_id) > 2).

Vehicle Performance (Q2): Analyzes average trip distances grouped by vehicle types to isolate high-utilization segments (AVG(distance_km) > 8).

User Acquisition & Churn (Q4, Q13): Identifies inactive users who registered during specific promotional windows (e.g., April 2025) but never completed a ride, utilizing both LEFT JOIN and subquery approaches

