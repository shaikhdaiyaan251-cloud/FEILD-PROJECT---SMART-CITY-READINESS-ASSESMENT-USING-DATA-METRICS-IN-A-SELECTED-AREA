# 🏙️ Smart City Readiness Assessment Using Data Metrics in a Selected Area

### 📍 Andheri West, Mumbai

> **A data-driven field study that measures how "smart" Andheri West really is — using citizen perception, physical field observations, and municipal data.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Visualization-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)

---

## 📍 The Question

### How ready is Andheri West for a smarter, more connected urban future?

Andheri West is a major suburban area of Mumbai, combining residential neighbourhoods, commercial zones, transportation corridors and dense urban infrastructure.

But a city can have strong digital connectivity while still facing challenges in:

- 🚇 Mobility
- 🛡️ Safety
- 🌱 Environment
- 🗑️ Waste & sanitation
- 🏗️ Infrastructure
- 📱 Digital services
- 👥 Citizen satisfaction

This project uses **data instead of assumptions** to measure that gap.

---

# 🎯 Project Snapshot

| Metric | Result |
|---|---:|
| 📊 **Overall SCRI** | **64.3%** |
| ⭐ **Weighted Score** | **3.21 / 5.0** |
| 👥 **Survey Respondents** | **30** |
| 📋 **Metric Variables** | **30** |
| 🏙️ **Urban Dimensions** | **7** |
| 🚶 **Field Observation** | **30 hours** |
| 📈 **Survey Scale** | **5-point Likert** |
| 📍 **Study Area** | **Andheri West, Mumbai** |
| 🐍 **Analysis Language** | **Python** |

### Overall Readiness

```text
0%                    50%                 64.3%                 100%
|----------------------|---------------------●--------------------|
                       Emerging             Developing
```

## **SCRI: 64.3% — DEVELOPING**

The project framework classifies **50%–79.9%** as the Developing tier.

---

# 🔎 What Makes This Project Different?

Instead of depending on a single source of information, the study combines **three independent data streams**.

```text
                    ┌─────────────────────┐
                    │   PRIMARY SURVEY    │
                    │      n = 30         │
                    │  Citizen Perception │
                    └──────────┬──────────┘
                               │
                               ▼
┌─────────────────────┐  TRIANGULATION  ┌──────────────────────┐
│  FIELD OBSERVATION  │◄───────────────►│   SECONDARY DATA     │
│    30 Field Hours   │                 │  Municipal / AQI     │
│ Physical Reality    │                 │   Data Validation    │
└──────────┬──────────┘                 └──────────┬───────────┘
           │                                       │
           └────────────────┬──────────────────────┘
                            ▼
                   ┌─────────────────────┐
                   │       SCRI          │
                   │     64.3%           │
                   │    Developing       │
                   └─────────────────────┘
```

This allows the project to ask a more important question:

> **Does what people perceive actually match what exists on the ground?**

---

# 📊 Seven Dimensions

The Smart City Readiness Index evaluates Andheri West across seven dimensions:

| # | Dimension | Weight |
|---|---|---:|
| 🚇 1 | Transportation & Mobility | **20%** |
| 🗑️ 2 | Waste & Sanitation | **15%** |
| 🏗️ 3 | Infrastructure & Utilities | **15%** |
| 📱 4 | Digital Connectivity & E-Governance | **15%** |
| 🛡️ 5 | Safety & Security | **10%** |
| 🌱 6 | Environment & Sustainability | **10%** |
| 👥 7 | Citizen Satisfaction | **15%** |
| | **Total** | **100%** |

---

# 📈 Dimension Results

| Dimension | Score / 5 | Deficiency |
|---|---:|---:|
| 📱 Digital Connectivity & E-Governance | **4.33** | 13.4% |
| 👥 Citizen Satisfaction | **3.60** | 28.0% |
| 🏗️ Infrastructure & Utilities | **3.38** | 32.4% |
| 🗑️ Waste & Sanitation | **3.08** | 38.4% |
| 🚇 Transportation & Mobility | **2.87** | 42.6% |
| 🛡️ Safety & Security | **2.85** | 43.0% |
| 🌱 Environment & Sustainability | **2.40** | 52.0% |

### The contrast is clear:

**Digital infrastructure performs strongly.**

While:

**Environmental, safety and mobility dimensions show larger gaps.**

---

# ⚡ The Most Interesting Finding

## Public Wi-Fi: Perception ≠ Reality

One of the strongest findings came from triangulation.

```text
CITIZEN PERCEPTION
███████████████████░  4.83 / 5


FIELD OBSERVATION
████░░░░░░░░░░░░░░░░  1.00 / 5

          ↓

     3.83 POINT GAP
```

Residents rated public Wi-Fi availability at **4.83/5**, while physical field audits recorded **1.00/5**.

### Difference: **3.83 points**

This demonstrates why combining survey responses with physical observation matters.

---

# 🏆 Highest & Lowest Indicators

## 🟢 Highest-rated Indicator

### D1 — Mobile Network Connectivity

> **4.83 / 5.0**

This reflects the strong availability of mobile connectivity reported in the study.

---

## 🔴 Lowest-rated Indicator

### S4 — Visible Safety Measures

> **1.57 / 5.0**

This indicator covers visible security measures such as CCTV surveillance and police patrols.

---

# 🌱 Environmental Challenge

Environment & Sustainability recorded:

## **2.40 / 5.0**

with a:

## **52.0% deficiency gap**

The study identifies limited green spaces and poor environmental quality as major contributors.

Secondary information cited in the report includes:

- 🌳 **6 public parks**
- 🌫️ **AQI: 225**
- 🌧️ **High drainage/flood-risk concerns around identified locations**

---

# 🧠 Research Methodology

The project follows a **mixed-methods research design**.

## 1️⃣ Primary Survey

- **30 respondents**
- Residents and local commuters
- **5-point Likert scale**
- **30 standardized variables**

## 2️⃣ Physical Field Observation

- **30 field hours**
- Infrastructure audits
- Transit locations
- Footpaths
- Drainage
- Street lighting
- Public Wi-Fi
- Cleanliness
- Parks and other civic infrastructure

## 3️⃣ Secondary Data

The research incorporates secondary information including:

- Municipal records
- BMC-related data
- MMRDA-related information
- Environmental / AQI data
- Infrastructure records

---

# 🧮 How SCRI Is Calculated

The project uses weighted dimension averages.

### Weighted Score

```text
Weighted Score =
(D₁ × 0.20) +
(D₂ × 0.15) +
(D₃ × 0.15) +
(D₄ × 0.15) +
(D₅ × 0.10) +
(D₆ × 0.10) +
(D₇ × 0.15)
```

The resulting weighted score is converted into a percentage:

```text
SCRI (%) = (Weighted Score / 5.0) × 100
```

For traffic congestion, the negatively oriented variable is reverse-scored:

```text
T5(Reversed) = 6 − T5(Raw)
```

This keeps the direction of all variables consistent before aggregation.

---

# 🔄 Analytical Pipeline

```text
                         RAW DATA
                            │
                            ▼
                ┌─────────────────────────┐
                │ 1. DATA PREPARATION     │
                │ • Cleaning              │
                │ • Validation            │
                │ • Reverse scoring       │
                └────────────┬────────────┘
                             ▼
                ┌─────────────────────────┐
                │ 2. DESCRIPTIVE ANALYSIS │
                │ • Variable means        │
                │ • Dimension averages    │
                └────────────┬────────────┘
                             ▼
                ┌─────────────────────────┐
                │ 3. SCRI CALCULATION     │
                │ • Dimension weights     │
                │ • Weighted score        │
                │ • Final percentage      │
                └────────────┬────────────┘
                             ▼
                ┌─────────────────────────┐
                │ 4. GAP ANALYSIS         │
                │ • Actual vs Ideal       │
                │ • Deficiency %          │
                └────────────┬────────────┘
                             ▼
                ┌─────────────────────────┐
                │ 5. TRIANGULATION        │
                │ • Survey vs Field       │
                │ • Secondary validation  │
                └────────────┬────────────┘
                             ▼
                       FINAL FINDINGS
```

---

# 📊 Visual Analytics

The project uses multiple visualization techniques to make the analysis easier to interpret.

### 🍩 Donut Gauge
Overall SCRI score.

### 📍 Line-Dot Chart
Actual dimension scores compared with the ideal benchmark.

### 🔵 Lollipop Chart
Highlights major deficiencies.

### 🔥 Heatmap
Visualizes all 30 metric variables.

### 🕸️ Radar Chart
Compares Andheri West against the ideal benchmark.

### 📊 Grouped Bar Chart
Visualizes triangulation between different data sources.

---

# 🛠️ Tech Stack

### Programming
- 🐍 Python

### Data Analysis
- 🐼 Pandas
- 🔢 NumPy

### Data Visualization
- 📊 Matplotlib
- 🎨 Seaborn

### Environment
- 📓 Jupyter Notebook

---

# 📁 Repository Structure

```text
FEILD-PROJECT---SMART-CITY-READINESS-ASSESMENT-USING-DATA-METRICS-IN-A-SELECTED-AREA/
│
├── 📓 FEILD_PROJECT.ipynb
│
├── 📄 FP Report.pdf
│
└── 📖 README.md
```

> Additional project files or datasets can be added here if they are part of the final submission.

---

# 🔬 Research Scope

The study focuses specifically on:

## 📍 Andheri West, Mumbai, Maharashtra

The assessment considers major residential, commercial and transit areas, including locations around:

- 🚉 Andheri Railway Station
- 🚇 Metro corridors
- 🛣️ Juhu Lane
- 🏢 Major commercial zones
- 🏘️ Residential clusters
- 🚶 Key transit locations

---

# ⚠️ Limitations

The findings should be interpreted within the scope of the research design.

### 👥 Sample Size

The survey contains:

> **n = 30 respondents**

Therefore, the results provide localized insights rather than a complete representation of every resident of Andheri West.

### ⏱️ Field Observation Duration

Physical observations were conducted during the prescribed:

> **30-hour fieldwork period**

Long-term seasonal variations cannot therefore be fully captured through direct observation alone.

### 💭 Perception Bias

Survey responses represent individual perceptions and may differ from physical conditions.

This difference is one of the reasons **triangulation** was included in the methodology.

---

# 🎓 Academic Context

This project was developed as a:

**B.Sc. Data Science Field Project**

under the **NEP 2020 academic framework**.

The project demonstrates how data science can be applied beyond conventional datasets to investigate:

- 🏗️ Urban infrastructure
- 🏛️ Civic services
- 🌱 Environmental conditions
- 🚇 Transportation
- 📱 Digital connectivity
- 🛡️ Public safety
- 👥 Citizen satisfaction

---

# 💡 What This Project Demonstrates

This project brings together several practical data-science concepts:

```text
             DATA COLLECTION
                    ↓
              DATA CLEANING
                    ↓
           DESCRIPTIVE ANALYSIS
                    ↓
            METRIC AGGREGATION
                    ↓
             WEIGHTED INDEX
               CALCULATION
                    ↓
               GAP ANALYSIS
                    ↓
              TRIANGULATION
                    ↓
             DATA VISUALIZATION
                    ↓
          EVIDENCE-BASED INSIGHTS
```

It demonstrates that data science can be used to analyze **real-world civic problems**, not just business datasets.

---

# 📌 Key Takeaway

> ## **A smart city is not defined by technology alone.**

Urban readiness needs to be examined through multiple dimensions — combining:

```text
WHAT PEOPLE EXPERIENCE
          +
WHAT EXISTS PHYSICALLY
          +
WHAT AVAILABLE DATA INDICATES
          ↓
     BETTER INSIGHT
```

The final **SCRI of 64.3%** provides a quantitative baseline for the selected study area and highlights where further investigation and improvement may be needed.

---

# 📚 Project Documentation

The complete project documentation is available in:

### 📄 `FP Report.pdf`

The report contains the project's methodology, research design, calculations, charts, findings, recommendations and appendices.

The complete Python-based analysis is available in:

### 📓 `FEILD_PROJECT.ipynb`

---

# 👥 Project

## Smart City Readiness Assessment Using Data Metrics in a Selected Area

📍 **Andheri West, Mumbai**

🎓 **B.Sc. Data Science**

🐍 **Python Data Analysis**

📊 **Smart City Readiness Index**

---

# ⭐ Explore the Project

Explore the notebook, inspect the calculations, study the visualizations, and understand how real-world urban observations can be transformed into measurable data.

```text
        DATA
         ↓
     ANALYSIS
         ↓
      EVIDENCE
         ↓
      INSIGHT
```

### 🏙️ From field observations to data-driven urban insights.

---
