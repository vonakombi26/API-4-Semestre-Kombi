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
| US1 | As an analyst, I will use the DEA model to measure the efficiency of ports         | High      | 1    |
| US2 | As an analyst, I will develop a draft of the home screen with key indicators to have a clear view of the final Dashboard version.         | Medium     | 1  |
| US3 | As an analyst, I will select specific products for deep data analysis.         | Low      | 1   |
| US4 | As an analyst, I will develop Python code to unify the data used for analysis.         | High     | 5   |

---

## 📊 Key Indicators (Visualized in Dashboard)
| ID  | Indicators                                                                | Metrics |
|-----|-----------------------------------------------------------------------------|------------|
| Overview | Total Registered Stops:       | 453 Mil      |
| Overview | Cargo Natures Tracked:  | 4     | 
| Overview | Total Weight Handled: | 974.78 Bi      | 
| Export | Volume Exported:  | 460 Bi   | 5   |
| Export | Total Embarkations:  | 2.15 Mi     |
| Export | Active Destinations:  | 202     |
| Import | Volume Imported:  | 503 Bi     |
| Import | Total Disembarkations:  | 2.44 Mi     |
| Import | Active Destinations:  | 202     |

---

## 🚢 Next Steps
- Perform the final verification with the client to ensure the analyses and visualizations meet expectations.
- Apply final improvements and refinements based on the client’s feedback.
- Prepare all materials and visual outputs for the Solution Fair presentation, organizing the content clearly and professionally.

---

## 📂 Attachments / Evidence
#### Presentation

> TPresentation video created to showcase the product, demonstrate the dashboard’s features, and summarize the main activities developed throughout the project. And the Power BI dashboard for visualization.

[Power BI](https://drive.google.com/file/d/12TuiBrh-0i4f_EgogIeyap-d8yAdba7E/view?usp=drive_link)
[Presentation link](https://youtu.be/Ov3cBAG9-GM)
  
#### Initial code developed

> Updated Python code developed for calculating port efficiency using the DEA model, including the processing of berthing time relative to transported cargo.

[Click here](https://colab.research.google.com/drive/1sNtuEzzTN0U7ebukQkAQdC3Vsa7XqpeQ)   
