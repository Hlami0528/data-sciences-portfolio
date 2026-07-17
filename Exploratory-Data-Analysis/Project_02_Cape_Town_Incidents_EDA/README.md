# 🚨 Cape Town Emergency Response Analytics: Decoding Incident Patterns for Smarter Interventions
![CPT Fire Cover Image](images/cpt_rescue.jpeg)

## Executive Summary
This project analyses emergency incident data published by the City of Cape Town to uncover patterns in urban crises across the metro. Using exploratory data analysis and visualisation, the project identifies where and when incidents are most concentrated, and which categories place the greatest demand on emergency services.
The original dataset contained over 3.1 million incident-category records, the majority of which represented categories for which no incidents were recorded. Following a structured data-cleaning process, the dataset was reduced to approximately 22,000 reported incidents and enriched through integration with suburb lookup and spatial boundary datasets.

The analysis identifies which suburbs experience the highest concentration of incidents, examines seasonal and temporal trends, and highlights the incident categories that place the greatest demand on emergency services. Spatial visualisations further reveal geographic patterns across the city, providing insights into the distribution of emergencies and potential areas requiring targeted resource allocation.

The resulting analytical dataset and findings demonstrate how municipal incident data can be transformed into actionable information to support evidence-based planning, service delivery, and emergency response decision-making.

---

## Business Problem
The City of Cape Town responds to thousands of emergency incidents each year, spanning fire, medical, and public safety events. Without a clear picture of incident distribution across time and location, resource allocation decisions are largely reactive. Emergency services and city planners need data-driven insight to anticipate demand, deploy resources efficiently, and reduce response times in high-pressure areas.

---

## Methodology
- **Data Source:** Open Data Portal published by the City of Cape Town
- **Data Overview:** Each record contains a unique incident ID, date, main category, subcategory, and location
- **Preprocessing:** Cleaned and standardised date fields, handled missing values, and categorised incident types
- **Analysis:** Examined incident frequency by category, subcategory, time of day, day of week, and month
- **Visualisation:** Produced distribution plots, time-series trends, and category breakdowns to surface key patterns

---

## Results & Business Recommendations

### Results
- `OTHER FIRE` was the most frequently reported incident category.
- Incident volumes peaked during `summer`, particularly for fire-related incidents.
- `Trauma` and `accident` incidents were concentrated in densely populated residential suburbs.
- `Medical` incidents occurred more frequently on `weekdays` than `weekends`.
- `Philippi`, `Hout Bay` and `Gugulethu` recorded the highest emergency service demand.

### Recommendations
- Allocate emergency response resources based on the dominant incident types within each suburb rather than applying a  uniform city-wide approach.
- Increase trauma and emergency medical response capacity in high-demand residential suburbs such as Philippi and Gugulethu.
- Strengthen traffic safety and accident prevention initiatives in the Cape Town City Centre, particularly during weekdays when incident volumes are highest.
- Expand fire prevention and public awareness campaigns before and during the summer season when fire-related incidents peak.
- Strategically position firefighting resources in suburbs with high concentrations of Other Fire incidents to improve response times.
- Maintain adequate residential fire response capacity throughout the year, as residential fires occur consistently across seasons.
- Use seasonal and spatial incident patterns to support data-driven deployment of personnel, vehicles, and emergency equipment.
- Continuously monitor incident trends to identify emerging hotspots and adjust resource allocation accordingly.

---

## Skills
`Python` · `Pandas` · `Seaborn` · `Matplotlib` · `Geospatial Analysis` · `Jupyter` · `Data Visualisation`
