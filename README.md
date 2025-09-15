# Geospatial Flood Risk Analysis for Insurance Portfolio Assessment

An advanced data analysis project demonstrating a prioritized, data-driven approach to managing financial risk in an insurance property portfolio.

### Business Problem
An insurance firm needs to move beyond simple risk identification and develop a prioritized strategy to manage its financial exposure to flood events. The goal is to identify the most critical high-risk assets to inform underwriting policies and target mitigation efforts effectively.

### My Approach & Tools
* Developed a spatial risk model by integrating a simulated portfolio of 10,000 vector-based properties with **raster-based Digital Elevation Model (DEM)** data.
* Leveraged **Python** with **GeoPandas** for vector analysis (identifying assets in flood zones) and **Rasterio/rioxarray** for raster processing (extracting elevation data for each property).
* Created a **prioritized risk tiering system ('High', 'Medium', 'Low')** based on precise asset elevation, enabling a nuanced view of the portfolio's vulnerability.
* Calculated the **Monetary Value at Risk (MVAR)** for each tier to quantify the financial exposure at different levels of risk.
* Produced compelling data visualizations with **Matplotlib**, overlaying risk data on terrain maps to clearly communicate findings to stakeholders.

### Key Findings & Recommendation

![Risk Analysis Overlay Map](analysis_map.png)

* **Finding:** While a segment of the portfolio was identified as being within a flood zone, the elevation analysis revealed that the risk was highly concentrated. The **'High-Risk' tier (properties at the lowest elevations) alone accounted for the vast majority of the total Monetary Value at Risk.**
* **Recommendation:** The firm should **immediately prioritize the 'High-Risk' tier for policy review** and proactive client engagement regarding mitigation measures. This data-driven approach focuses resources on the most critical assets, optimizing the cost-benefit of risk management efforts.
