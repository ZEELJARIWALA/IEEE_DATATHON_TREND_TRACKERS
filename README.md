# Electric Vehicle Population Analysis

## Overview
The transition to electric vehicles (EVs) is crucial for a sustainable future. This project focuses on analyzing EV population data to provide actionable insights for policymakers, businesses, and consumers. By leveraging data-driven techniques, we aim to improve charging infrastructure, forecast EV adoption trends, and enhance overall accessibility.

## Objectives
- **GOAL-1 > EV Adoption Trends Across Locations:** Identify cities and regions with high or low EV adoption to help policymakers and automakers strategize incentives and marketing efforts.
- **GOAL-2 >Forecast Future EV Growth:** Predict EV registration growth to assist in planning infrastructure and supply chain requirements.
- **GOAL-3 >Optimal Charging Station Placement:** Locate areas needing new charging stations to minimize range anxiety and improve accessibility.
- **GOAL-4 >EV Price Trend Analysis:** Study MSRP trends over different years and brands to inform consumers and manufacturers.
- **GOAL-5 >Performance & Range Analysis:** Evaluate which EV models provide the best range and efficiency to guide consumers.
- **GOAL-6 >Environmental Impact Estimation:** Assess CO2 emissions reductions due to increased EV adoption.

## Challenges
1. **Fragmented Data Sources:** EV adoption trends vary across different locations, requiring consolidation of multiple datasets.
2. **Predictive Modeling Complexity:** For now, our forecasting model does not consider external policies, subsidies, or economic shifts. It is solely based on past trends in the dataset. Our accuracy is approximately 72%. If we were to incorporate policy changes and economic factors, prediction accuracy would increase. We use the Prophet model for forecasting, which impacts results by identifying seasonality and trend shifts in historical data.
3. **Infrastructure Gaps:** Determining optimal charging station locations involves analyzing traffic patterns, energy grid constraints, and regional EV density. We use **GeoPandas**, **Folium**, and **K-Means clustering** to identify the most appropriate locations for new charging stations and determine the required number of stations based on the dataset.
4. **Consumer Decision Support:** Providing real-time, insightful data for consumers to make informed EV purchasing choices.

## Dataset
The project utilizes publicly available EV population data:
[Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data/resource/fa51be35-691f-45d2-9f3e-535877965e69)

## Technology Stack
- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, K-mean, Prophet
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Geospatial Analysis:** GeoPandas, Folium

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/EV-Population-Analysis.git
   cd EV-Population-Analysis
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Download the dataset and place it in the `data/` directory.

## Future Roadmap
- Expand dataset coverage to global EV adoption data.
- Develop an interactive **dashboard** for real-time EV insights.
- Integrate **real-time data feeds** from government sources.
- Implement **API endpoints** for third-party applications.
- Incorporate **advanced machine learning models** for better predictions.

## Conclusion
The transition to electric vehicles is a global imperative, requiring coordinated efforts from policymakers, businesses, and consumers. This project provides a **data-driven solution** that enables stakeholders to make informed decisions by leveraging insights from EV population data.

- **Policymakers** can use our forecasting and clustering techniques to determine optimal locations for new charging stations, enhance EV infrastructure, and create policies that support widespread adoption.
- **Businesses** can utilize our price trend analysis, growth forecasts, and infrastructure recommendations to invest wisely in EV-related opportunities, including manufacturing, charging networks, and fleet electrification.
- **Consumers** benefit from insights on pricing trends, vehicle performance, and charging station availability, empowering them to make smarter purchasing decisions that align with sustainability goals.

By integrating machine learning, geospatial analytics, and predictive modeling, this project contributes to the acceleration of EV adoption, reducing dependency on fossil fuels, and promoting a cleaner and more sustainable transportation ecosystem. Through ongoing improvements, real-time data integration, and expanded global insights, this initiative will continue to shape the future of electric mobility.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors
- [JARIWALA ZEEL](https://github.com/ZEELJARIWALA)
- [PRATHAMESH RAJPUT](https://github.com/Prathamesh603)
- [JEEL DONGA](https://github.com/JEELDONGA18)


---
This project leverages data-driven insights to accelerate EV adoption, optimize charging infrastructure, and support sustainable transportation.
