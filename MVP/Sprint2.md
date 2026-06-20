# 📈 MVP SPRINT 2 - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP for Sprint 2 aims to deepen the analysis of port operations, focusing specifically on one priority cargo types — Soy — while maintaining a general overview of logistics performance from 2024 to 2025. This stage seeks to deliver a more refined and targeted analysis to the client, with improved visualizations that enhance the understanding of port movements and the main origin-destination routes.

- *What hypothesis will be validated?*

The hypothesis to be validated is that segmenting the analysis by cargo type and adding interactive visualizations and filters will lead to a better understanding of logistical and operational behaviors, generating more strategic insights for the client.

- *What value will be delivered to the end user?*

The user will receive a set of analyses and visualizations highlighting key trends, most relevant ports, and logistics flows. The ability to filter data by year, origin, and destination will support strategic decision-making and operational planning.

---

## 🚚 Solution Description
The interface focuses on four main pillars of data as seen in the prototype:

- eview and restructuring of the original dataset, generating a compiled file with the most essential and consistent information.
- Creation of visualizations focused on port activity, main ports, and behavior by cargo type. Implementation of interactive filters (year,boarding, landing) to enhance data exploration and navigation.
- Analytical focus on one main cargo categories: Soy
- Continuation of dashboard development, to be finalized in the next sprint.
- Limitations: the final interactive dashboard is still under construction; analyses at this stage are exploratory.

---

## ✈️ User Stories (MVP Backlog)
| ID  | User Story                                                                 | Priority | Partner Requirement|
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | As an analyst, I want to visualize the main reasons for operational stoppages to identify the major factors that impact productivity         | High      | 5    |
| US2 | As an analyst, I want to visualize which ports transport the most cargo to identify which ones are most relevant in port movement.         | Medium     | 1  |
| US3 | As an analyst, I want to visualize how many port operations are performed per month at each port to understand the volume of operational activities         | Low      | 1   |
| US4 | As an analyst, I will identify and analyze which were the most transported cargoes in the established period.         | High     | 5   |

---

## 📊 Key Indicators (Visualized in Dashboard)
- Total Soy Volume (Volume Total Soja): 105 Bi — Cumulative mass of grain transactions segmented exclusively for soybean markets.
- Total Embarkations (Total de Embarques): 33 Mil — Total outgoing shipping operations handling grain exports.
- Total Disembarkations (Total de Desembarques): 15 Mil — Inbound logistics transactions for domestic transfers or entry shipments.

---

## 🚢 Next Steps
- Refine the analyses based on the feedback received.
- Refine the "Average Operation Time" metric to resolve visual overlaps in the interface.
- Expand regional analysis to include state-level details within the North, South, Northeast, and Southeast regions.

---

## 📂 Attachments / Evidence
#### Presentation

> With the fundamental data structure and presentation layers defined for Sprint 3, future efforts will focus on backend optimization, automated ETL scheduling, and analysis of loads and downtime, as well as segregated export and import information.

[Click here](https://drive.google.com/file/d/1ZekO85eurcSNfDpPMdqZ8OuLUrpVp8tR/view?usp=drive_link)

  
#### Initial code developed

> Revised Python code adapted for cleaning, consolidation, and updating of port operation data.

[Click here](https://colab.research.google.com/drive/1sNtuEzzTN0U7ebukQkAQdC3Vsa7XqpeQ)   
