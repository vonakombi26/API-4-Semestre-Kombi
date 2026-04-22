# 📈 MVP SPRINT 2 - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP presents a consolidated view of port movements from the 2024 to 2025, converting raw data into strategic indicators such as total volume, operational efficiency, and geographic distribution.

- *What hypothesis will be validated?*

The hypothesis being validated is that presenting initial analyses and extracted data is sufficient to generate an initial understanding and guide the next steps of the project. Additionally, it validates that a centralized visualization of berthing metrics and cargo volume allows for the quick identification of the most productive ports and main navigation types.

- *What value will be delivered to the end user?*

A clear and structured summary of preliminary analyses, enabling users to validate work progress and plan future actions. A monitoring tool highlighting a Total Volume of 2.75 Billion tons and activity across 220 active ports.

---

## 🚚 Solution Description
The interface focuses on four main pillars of data as seen in the prototype:

- Performance Metrics: Total volume (ton), total berthings (223k), and average operation time.
- Temporal Analysis: A "Berthing per Month" graph comparing the years 2024 and 2025.
- Market Segmentation: Breakdown of volume by "Navigation Type" (highlighting Long Haul and Cabotage) and by "Geographic Region".
- Performance Ranking: Top 10 Ports by Volume, led by the Ponta da Madeira Maritime Terminal and the Port of Santos.

---

## ✈️ User Stories (MVP Backlog)
| ID  | User Story                                                                 | Priority | Partner Requirement|
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | As an analyst, I will collect and filter data from 2024 to 2025 to ensure the information is ready for future analysis.         | High      | 5    |
| US2 | As an analyst, I will develop a draft of the home screen with key indicators to have a clear view of the final Dashboard version.         | Medium     | 1  |
| US3 | As an analyst, I will select specific products for deep data analysis.         | Low      | 1   |
| US4 | As an analyst, I will develop Python code to unify the data used for analysis.         | High     | 5   |

---

## 📊 Key Indicators (Visualized in Dashboard)
- Total Volume (ton): 2.75 Billion.
- Total Berthings: 223 Thousand.
- Active Ports: 220 units.
- Navigation Distribution: "Long Haul" (Longo Curso) represents the vast majority at 70.99% (1.96 Bi).
- Regional Leadership: The Southeast region leads in gross cargo weight, followed by the Northeast and South.

---

## 🚢 Next Steps
- Refine the analyses based on the feedback received.
- Refine the "Average Operation Time" metric to resolve visual overlaps in the interface.
- Expand regional analysis to include state-level details within the North, South, Northeast, and Southeast regions.

---

## 📂 Attachments / Evidence
#### Presentation

> The slide provides the project introduction, outlines the activities undertaken during the first sprint, presents the initial data collected, and includes the preliminary draft of the dashboard under development.

[Click here](https://github.com/user-attachments/files/22686384/Sprint1_presentation.pdf)

  
#### Initial code developed

> The developed code is designed to process and organize port data from 2024 to 2025. The implemented structure consolidates information on cargo handled, weight in kilograms, and other relevant variables for the analysis. This initial processing serves as the foundation for building indicators, conducting port comparisons, and subsequently applying analytical models such as DEA, ensuring consistency and reliability in the results obtained.

[Click here](https://colab.research.google.com/drive/1sNtuEzzTN0U7ebukQkAQdC3Vsa7XqpeQ)   
