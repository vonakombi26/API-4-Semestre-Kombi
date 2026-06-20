# 📈 MVP SPRINT 3 - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP for Sprint 3 focuses on delivering the first fully functional version of the port operations dashboard, integrating all analyses developed so far. In this stage, the goal is to provide the client with a clear, interactive environment to explore logistics behavior, port performance, and cargo dynamics between 2024 and 2025.

- *What hypothesis will be validated?*

The hypothesis is that a consolidated dashboard—containing segmented analyses, efficiency metrics, DEA modeling, and operational stoppage insights—will enable the client to easily identify patterns, bottlenecks, and strategic opportunities in port logistics.

- *What value will be delivered to the end user?*

The user will receive an interactive and intuitive dashboard with six structured analytical views:

1. General Analysis
2. Operational Efficiency
3. Soybean Analysis
4. Load Stops and Analysis
5. Export
6. Import
   
These visualizations allow for better strategic planning, improved understanding of port behavior, and more informed decision-making.
   
---

## 🚚 Solution Description
Development of six interactive visualizations, each addressing a key analytical perspective:

1. Overall port movement and trends
2. Behavior by job type
3. Port efficiency analysis
4. Main causes of operational stoppages
   
-Implementation of DEA (Data Envelopment Analysis) to measure port efficiency, using berthing time relative to transported cargo as the primary criterion.
- Integration of the consolidated dataset into all visualizations.
- Refinement of the dashboard layout to improve navigation and clarity.
- Documentation of analytical processes and methodological choices.
  
Limitations:

- Advanced comparative models and additional KPIs will be expanded in the next sprint.
- Some parameters of the DEA model may require refinement after client feedback.

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
- Perform the final verification with the client to ensure the analyses and visualizations meet expectations.
- Apply final improvements and refinements based on the client’s feedback.
- Prepare all materials and visual outputs for the Solution Fair presentation, organizing the content clearly and professionally.

---

## 📂 Attachments / Evidence
#### Presentation

> The slide provides the project introduction, outlines the activities undertaken during the first sprint, presents the initial data collected, and includes the preliminary draft of the dashboard under development.

[Click here](https://github.com/user-attachments/files/22686384/Sprint1_presentation.pdf)

  
#### Initial code developed

> The developed code is designed to process and organize port data from 2024 to 2025. The implemented structure consolidates information on cargo handled, weight in kilograms, and other relevant variables for the analysis. This initial processing serves as the foundation for building indicators, conducting port comparisons, and subsequently applying analytical models such as DEA, ensuring consistency and reliability in the results obtained.

[Click here](https://colab.research.google.com/drive/1sNtuEzzTN0U7ebukQkAQdC3Vsa7XqpeQ)   
