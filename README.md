# RKAM-Centre_Referral_Development_-STB_MTB-
## Data-Driven Referral Development and Optimization & Board Efficiency at RKAM Hospital (2022 - 2026)

This project delivers a data analysis pipeline and architecture designed to optimize regional referral networks, analyze clinical board transformation, and eliminate operational bottlenecks at the RKAM Cancer Centre over a 5-year period.

## 🛠️ The 3-Stage Data Analysis Architecture

• Stage 1 (Raw Data & Simulation): Processes raw clinical cancer tracking data, simulated datasets, and various external sources (e.g., WTZ Annual and Quality Reports). It addresses administrative anomalies, string formatting inconsistencies, and an 8% rate of missing records in the staging area.
• Stage 2 (Python ETL & Data Cleansing): Executes automated string operations (.strip(), casing standardizations) and statistical data imputation using Pandas to repair incomplete tracking profiles.
• Stage 3 (Relational Storage): Deploys an SQLite Engine (rkam_klinik_warehouse.db) as the central data warehouse. It aggregates all key data to easily generate statistics and evaluations for management later on.

## 📊 Tableau Visualization
The database was transformed into a single denormalized table tailored for Tableau. The resulting dashboard serves as a management cockpit, displaying the most relevant KPIs at a glance. It integrates various analyses, featuring:

• An interactive GeoMap for regional referral mapping

• Dynamic charts and widgets illustrating the development and trends of referrers over the 5-year period
