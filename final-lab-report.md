---
title: Final Lab Report
---

## Fundamentals of Geographic Information Systems

This page represents my work over the course of the semester and highlights three maps that demonstrate my ability to solve spatial problems and develop narratives using Geographic Information Systems (GIS). Throughout the semester, I primarily used ArcGIS Pro to create and analyze visual maps that communicate complex geographic patterns. At the beginning of the course, I did not anticipate using GIS beyond the classroom; however, by the end of the semester, I applied GIS concepts to topics such as chronic kidney disease for senior design problem statements and societal relevance.

GIS has broad applications beyond public health, including supply chain analysis, housing affordability, urban planning, and decisions related to where to live or raise a family. As an engineering student, learning GIS has added depth to my technical skill set and strengthened my ability to analyze spatial data as a prospective graduate student or future professional. Although I wish I had been more present during some of the analytical processes instead of rushing, this course expanded my perspective on how mapping and spatial analysis can support real-world decision-making.

---

## Map 1 — 2020 Presidential Election Results (Pennsylvania)

<img src="{{ site.baseurl }}/assets/images/map1.jpg" width="900">

### Narrative

Figure 1 depicts Pennsylvania voter turnout and the percentage concentration of voters by political party, based on which party was leading in each district. The primary purpose of the map is to illustrate that political affiliation is geographically localized and varies across the state, with different levels of concentration by district. The map also highlights how political ideologies are favored differently across regions.

Importantly, this map should not be interpreted as portraying political homogeneity within districts. This aligns with the concept of the ecological fallacy, in which a single dominant narrative is incorrectly used to judge all individuals within an area. Instead, interpretation should acknowledge the multiple social and political dynamics that exist within each district. This perspective shifts the mindset away from viewing areas as uniformly Democratic or Republican.

### GIS Tools and Skills Used
- Choropleth mapping  
- Attribute joins  
- Classification and symbology  

---

## Map 2 — Homicide Density by Police District (Chicago)

<img src="{{ site.baseurl }}/assets/images/map2.jpg" width="900">

Figure 2. Homicide density by police district in Chicago with individual homicide locations overlaid.

### Narrative

Figure 2 illustrates the spatial distribution of homicide density across Chicago police districts, revealing clear geographic clustering rather than a uniform pattern across the city. Higher homicide densities are concentrated in certain districts on the west side of Chicago, while districts along the eastern portion of the city exhibit comparatively lower homicide rates. These lower-rate areas also correspond to higher tourism activity and more expensive Airbnb listings.

This spatial visualization challenges broad political narratives that portray Chicago as uniformly dangerous. By visualizing homicide density per square mile, the map demonstrates that crime is localized and that citywide generalizations obscure meaningful spatial differences between districts. The map reinforces the importance of neighborhood-scale analysis when evaluating urban crime patterns.

### GIS Tools and Skills Used
- Spatial join  
- Density calculations  
- Overlay analysis  
- Map design principles  

---

## Map 3 — Philadelphia Schools and Bike Network

<img src="{{ site.baseurl }}/assets/images/map3.jpg" width="900">

Figure 3. Philadelphia School District schools with enrollments over 1,200 students located within 0.1 miles of the city bike network.

### Narrative

Figure 3 demonstrates how geographic data can be used to identify neighborhoods in Philadelphia that contain large public schools which are well connected to the city’s bike network. To address this problem, school enrollment data and bike network data were analyzed together to move beyond a tabular format and better understand how location influences accessibility.

By filtering schools with enrollments greater than 1,200 students and examining their proximity to bike infrastructure, the analysis revealed that only a small number of schools meet both criteria. Mapping these results showed that well-connected, high-enrollment schools are distributed across several neighborhoods rather than clustered in a single area. This spatial analysis supports informed decision-making related to transportation access, urban planning, and school commuting options. The visualization helps education leaders, families, planners, and policymakers better understand how biking infrastructure interacts with school catchment areas.

### GIS Tools and Skills Used
- Select by attribute  
- Select by location  

