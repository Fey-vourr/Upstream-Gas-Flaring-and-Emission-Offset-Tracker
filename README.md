# Upstream Gas Flaring & Emission Offset Tracker

An end-to-end data pipeline and interactive business intelligence dashboard designed to monitor upstream gas flaring operations, track monthly CO₂ emissions against decarbonization targets, estimate corporate financial liabilities, and evaluate gas-to-power energy transition opportunities.

---

## 📌 Project Overview

Gas flaring in upstream oil and gas operations remains a major contributor to greenhouse gas (GHG) emissions and energy loss. This project simulates an enterprise-grade Health, Safety, and Environment (HSE) & ESG monitoring system.

It provides executives and operations teams with real-time operational visibility into:

* Compliance tracking against Net-Zero 2030 target thresholds.
* Regulatory financial penalties derived from non-compliant flare volumes.
* Regional (LGA) emission hotspots.
* Value recovery potential through flare gas capture and monetization (Gas-to-Power).

---

## 📸 Dashboard Preview

---

## 🧰 Tech Stack & Architecture

* **Data Generation Pipeline:** Python (`pandas`, `numpy`) – Engineered a realistic synthetic dataset simulating multi-operator upstream flaring logs across multiple Local Government Areas (LGAs) and date ranges.
* **Data Modeling & Calculations:** Power BI & DAX – Multi-table data model with measures for carbon conversion factors, penalty scaling, utilization rates, and scenario analysis.
* **Data Visualization:** Power BI Desktop – Interactive 3-page report with custom dark-themed UI components and dynamic cross-filtering.

---

## 📊 Key Metrics & Features

### 1. Executive View (Atmospheric Emission & Carbon Footprint)

* **High-Level KPIs:** Tracks **Total Flared Volume (2.30 Bcf)**, **Total CO₂ Emitted (122.40 kTonnes)**, **Total Regulatory Fines ($4.61M)**, and **Avg Gas Utilization Rate (48.31%)**.
* **Net-Zero 2030 Target Line:** Tracks monthly CO₂ emissions against a fixed compliance threshold (0.10 kTonnes) to evaluate emission trajectory over time.
* **Spatial & Corporate Breakdown:** Identifies top-flaring Local Government Areas (LGAs) and assesses corporate liabilities across key operators (ExxonMobil, NAOC, NDPR, SPDC, TotalEnergies).

### 2. Operational View (Gas to Power & Energy Transition Potential)

* **Resource Loss Estimation:** Calculates lost commercial gas value ($4.61M) and total power potential (26.96K MWh).
* **Community Impact Metric:** Models household energy equivalent (power potential for up to 3M households) and avoided carbon credits ($3.06M).
* **What-If Scenario Analysis:** Dynamic parameter slicer enabling stakeholders to model penalty reduction, avoided CO₂, and unlocked power at varying gas capture target percentages.

### 3. Summary & Insights Page

* Centralized operational summary highlighting critical questions answered, target gaps, and strategic recommendations for decarbonization.

---

## 💡 Key Business Insights

* **Target Trajectory:** Monthly CO₂ emissions peaked early in the period (exceeding the 0.10 kTonnes threshold) but demonstrate a consistent downward trend approaching Net-Zero 2030 target limits.
* **Efficiency Gap:** Over half of produced gas (**53.54%**) is lost to routine flaring, with current capture utilization sitting at **46.46%**.
* **Scenario Value:** Incremental improvements in gas capture yield high returns—a **5% increase in capture target** avoids **6.12 kTonnes of CO₂**, reduces fines by **$230.41K**, and unlocks **1.35K MWh** of generation capacity.

---

## 🚀 How to Run & Explore

1. **View Live Interactive Report:** [Link to Power BI Dashboard](https://github.com/Fey-vourr/Upstream-Gas-Flaring-and-Emission-Offset-Tracker/blob/main/Upstream%20Gas%20Flaring%20and%20Emission%20Offset%20Tracker.pbix)
2. **Review Data Pipeline Code:** Inspect the Python script `Gas_flaring_tracker.ipynb` used to build the synthetic dataset.
3. **Open Power BI File:**
* Clone this repository:
```bash
git clone https://github.com/Fey-vourr/Upstream-Gas-Flaring-and-Emission-Offset-Tracker.git

```


* Open `Upstream Gas Flaring and Emission Offset Tracker.pbix` in Power BI Desktop.



---

## 📬 Contact & Connect

**Favour Chukwuemeka**

*HSE & ESG Data Analyst*

* [LinkedIn](www.linkedin.com/in/favour-chukwuemeka-hsedata)
* [Portfolio/GitHub](https://github.com/Fey-vourr)
