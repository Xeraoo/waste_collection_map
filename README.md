# Selective Waste Collection Map Project

This project visualizes data on the selective waste collection across selected municipalities in the Mazowieckie, Lubelskie, and Podlaskie Voivodeships (2020). The maps present the tonnage and composition of the collected waste by type, including paper, glass, plastics, and biodegradable waste. The project involves two distinct approaches to visualization, one created using **ArcGIS** and the other using **QGIS**.

## Project Overview

The goal of this project is to present a clear and insightful comparison of selective waste collection data in the region using two different GIS software platforms, showcasing how both tools can represent the same dataset in varying visual styles. The dataset used includes data on waste categories such as:
- Paper and cardboard
- Glass
- Plastics
- Biodegradable waste

The visualized data is represented by pie charts proportional to the amount of waste collected in tons in each municipality. 

### Map 1: ArcGIS Version

![image](https://github.com/user-attachments/assets/63346a28-277b-4914-a2ee-2e0cf31ab8ba)


This map, generated in **ArcGIS**, emphasizes a detailed representation of the waste collected in various municipalities. The sizes of the pie charts are scaled to the total amount of waste collected in each region, with different colors representing the different categories of waste. The **legend** and visual elements have been tailored to maintain clarity at a scale of 1:500,000.

### Map 2: QGIS Version

![image](https://github.com/user-attachments/assets/6007076d-c663-403e-b973-c14acb0db144)


This map, generated in **QGIS**, presents the same data but with a slightly different visual approach. The pie charts again depict the relative proportion of waste types in each municipality, but the **QGIS** visualization includes additional scaling of visual elements and focuses on presenting the mean size and structure of the collected waste at a different scale of 1:600,000. The **legend** provides additional information about the specific percentage breakdown of the waste categories.

## Tools and Software

- **ArcGIS**: Used for the initial visualization of the dataset. ArcGIS offers robust tools for data visualization, which were employed to create proportional pie charts and ensure accurate representation of waste data at the municipal level.
- **QGIS**: Used for the secondary visualization. QGIS, as an open-source alternative, was utilized to replicate the same dataset while providing a different cartographic style and layout.
  
## Data Source

The dataset used for both maps comes from official reports on selective waste collection in 2020, covering the **Mazowieckie**, **Lubelskie**, and **Podlaskie** regions of Poland. Data was collected on the types of waste sorted in each municipality and aggregated to create meaningful visual representations of the data.

## Conclusion

This project demonstrates the flexibility of both **ArcGIS** and **QGIS** in visualizing geospatial data. While both platforms offer similar functionalities, the difference in styles and presentation in the final maps highlights the varied approaches to data visualization that these tools enable. This comparison can help decision-makers choose the most suitable software for their specific mapping and analysis needs.


