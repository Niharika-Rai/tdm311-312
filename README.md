# Diesel Engine Performance Monitoring for Carnival Cruise Line

**The Data Mine Corporate Partners Program (TDM 311–312) · Purdue University**
**Role:** Undergraduate Data Science Researcher · **Industry partner:** Carnival Cruise Line

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)](#tools--technologies)
[![Domain](https://img.shields.io/badge/Domain-Maritime%20Engineering-0A66C2)](#project-overview)
[![Focus](https://img.shields.io/badge/Focus-Anomaly%20Detection-2E7D32)](#what-i-built)

> I built an interactive Power BI dashboard that Carnival Cruise Line can use to monitor diesel engine performance across **3 ships over 3 years**. It helps spot unusual engine component behavior early and supports data-driven decisions on reliability and operating efficiency.

📽️ **Symposium poster and video:** [datamine.purdue.edu/carnival-cruise-line](https://datamine.purdue.edu/carnival-cruise-line/)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [What I Built](#what-i-built)
- [My Approach](#my-approach)
- [Tools & Technologies](#tools--technologies)
- [Impact](#impact)
- [Skills Demonstrated](#skills-demonstrated)
- [About The Data Mine Corporate Partners Program](#about-the-data-mine-corporate-partners-program)
- [Data Confidentiality](#data-confidentiality)
- [Contact](#contact)

---

## Project Overview

| | |
|---|---|
| **Program** | The Data Mine Corporate Partners (TDM 311–312), Purdue University |
| **Partner** | Carnival Cruise Line (an industry mentor guided the project) |
| **My role** | Undergraduate Data Science Researcher |
| **Scope** | Diesel engine sensor and performance data from **3 ships** covering **3 years** of operation |
| **Deliverable** | An interactive **Power BI dashboard** for engine monitoring and anomaly detection |
| **Presented at** | The Data Mine Corporate Partners Symposium (poster and video) |

## Business Problem

Diesel engines are central to how a cruise ship runs. When an engine component starts to fail and nobody catches it, the result can be costly repairs, wasted fuel, schedule disruptions and a worse guest experience. Engine data is large and spread across many ships and years, so it is hard to see the warning signs by hand.

Carnival needed a clear way to:
1. **Monitor** engine performance across several ships in one place.
2. **Detect anomalies** in how engine components behave before they turn into failures.
3. **Improve reliability and operating efficiency** with insights drawn from the data.

## What I Built

An **interactive Power BI dashboard** that turns three years of multi-ship engine data into insights that engineers and stakeholders can act on:

- **Fleet-level view:** compare engine performance across all 3 ships side by side.
- **Trend analysis over time:** follow component behavior across the full 3-year period to find patterns, seasonality and slow degradation.
- **Anomaly identification:** bring unusual component readings to the surface so teams can investigate them early.
- **Interactive exploration:** filters and drill-downs let users go from a fleet-wide summary down to a single ship, engine or component.
- **Decision support:** visuals designed for both technical engineers and non-technical stakeholders.

<!-- Optional: add a screenshot or GIF of the dashboard (with sensitive values hidden), e.g.
![Dashboard preview](images/dashboard.png) -->

## My Approach

1. **Understanding the problem:** met with my Carnival mentor to learn how diesel engines work at sea, which components matter most, and what "abnormal" looks like in practice.
2. **Data preparation:** cleaned, combined and structured multi-year engine data from several ships so it could be analyzed reliably.
3. **Exploratory analysis:** studied distributions, trends and relationships between engine components to set baselines for normal behavior.
4. **Anomaly identification:** flagged readings and periods that departed from those baselines.
5. **Dashboard design and development:** built and refined the Power BI dashboard over several rounds, using mentor feedback to match real operational needs.
6. **Communication:** presented the findings at the Data Mine Symposium through a research poster and a recorded video.

<!-- Optional: add specifics such as the number of records or sensors, the anomaly method used
(e.g. statistical thresholds, z-scores, rolling averages), and key findings. -->

## Tools & Technologies

| Category | Tools |
|---|---|
| Business intelligence and visualization | Microsoft Power BI (Power Query, data modeling, DAX measures, interactive reports) |
| Data analysis | Data cleaning and transformation, exploratory data analysis, time-series trend analysis |
| Analytical methods | Anomaly and outlier detection, baselining of component performance |
| Collaboration | Iterative development with an industry mentor, Agile-style feedback cycles |
| Communication | Research poster, recorded video presentation, stakeholder-friendly reporting |

<!-- Add any other tools you used, e.g. Python (pandas, NumPy, Matplotlib), SQL, Excel, Jupyter, Git. -->

## Impact

- Gave Carnival **one central view** of diesel engine health across multiple ships, replacing manual, scattered review of the data.
- Made it possible to **catch abnormal component behavior early**, which supports predictive maintenance and lowers the risk of unplanned downtime.
- Supported Carnival's goals of **better engine reliability and operating efficiency** through data-driven insights.
- Delivered a **reusable tool** that can grow to cover more ships, components or time periods.

<!-- If you have numbers, add them here, e.g. "Analyzed X million sensor readings" or
"Identified N anomaly patterns across M engine components". Recruiters respond strongly to numbers. -->

## Skills Demonstrated

**Technical**
- Data visualization and dashboard development (Power BI)
- Data cleaning, transformation and modeling for large, multi-source datasets
- Time-series and trend analysis
- Anomaly detection and data-driven root-cause investigation
- Turning business requirements into analytical solutions

**Professional**
- Working directly with a Fortune 500 industry partner and mentor
- Explaining technical findings to non-technical audiences
- Ownership of a project from start to finish, from scoping through final presentation
- Learning a new domain (marine diesel engineering) quickly
- Research communication through posters and video presentations

## About The Data Mine Corporate Partners Program

[The Data Mine](https://datamine.purdue.edu/) is Purdue University's large living-learning community for data science. In the **Corporate Partners Program (TDM 311–312)**, undergraduate researchers work on real industry problems that partner companies sponsor. The work runs over the full academic year, and each team is guided by mentors from the partner company and by Data Mine staff. Teams finish the year by presenting their work at the Data Mine Corporate Partners Symposium.

## Data Confidentiality

This project used proprietary operational data that belongs to Carnival Cruise Line. **Raw data, the dashboard file and internal findings are not included in this repository** because of confidentiality agreements. This README describes the project's goals, methods and outcomes. The public poster and video are available at the [Data Mine symposium page](https://datamine.purdue.edu/carnival-cruise-line/).
