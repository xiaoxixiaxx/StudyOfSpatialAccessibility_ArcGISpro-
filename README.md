# The Study of the Spatial Accessibility of Health Care Centers for the Population Below Poverty and the Elderly over 65 in Connecticut
## -- Using Buffer and Network Analyst in ArcGIS Pro

## Introduction
The report analyzes the geographic relationship between medical service centers and residents in Connecticut through two methods. The method uses buffer and network to analyze the distribution of residents 1-mile from the medical service center. Compare the results of these two analyses and evaluate whether the geographic distribution of Connecticut’s medical service providers is effective in serving residents. The study purpose of the report is to analyze and evaluate the spatial accessibility of people below the poverty line. The map specifically introduces and visualizes the population below the poverty line in Connecticut, as well as the spatial accessibility of medical facilities to the elderly over 65. In the study, I got two analysis methods in the research, and found that the analysis of the two methods of buffer and network play different roles, and they have different advantages and disadvantages. It will be introduced later in the report. In addition, I understand the importance of how to do geographic analysis in the real world through ArcGIS Pro.

### Map 1 displaying the FQHC sites and below poverty by census tract
![map1](https://user-images.githubusercontent.com/77243665/120581642-fcb86b80-c3df-11eb-8955-7c8a68b13559.png)

### Map 2 displaying the FQHC sites and people above age 65
![map2](https://user-images.githubusercontent.com/77243665/120581647-ffb35c00-c3df-11eb-84c5-f73c246a14b9.png)

### Map 3 conveying an accessibility measure of buffer
![map3](https://user-images.githubusercontent.com/77243665/120581653-02ae4c80-c3e0-11eb-8422-45ba92f7b2e6.png)

### Map 4 conveying an accessibility measure of both buffer and network
![map4](https://user-images.githubusercontent.com/77243665/120581658-05a93d00-c3e0-11eb-82d6-e1015ab3b229.png)

## Tables of accessibility measures

Accessibility Results
|-----------------|
|                 |
|Population Group |Count
|TotPop           |
|BelowPov         |
|Age65p           | 
|SinglFemHH       |
|WorkHome         |

## Note about the two measures used to assess geographic accessibility
The Buffer measurement method covers a wider range than the network, although they all measure 1 mile. The Buffer measurement method includes more people. This can also be seen from Tables of accessibility measures. Among the five variables I listed, the percentage of people selected by the buffer measurement method is always more than that measured by the network. But the network measurement method also has advantages. It uses a map of the transportation network available in the city to analyze complex routing issues around medical institutions. It can accurately express unique route network requirements. (Network Analyst, esri) In this way, we can plan the entire driving route of Connecticut, calculate driving time, find facilities, and solve other network-related problems. It is more accurate to give the traffic route range within 1 mile in the measurement map of Connecticut. Therefore, people can reduce mileage to reduce fuel costs and save time by reducing driving. Reduce vehicle wear. (Network Analyst, esri) This method is beneficial to the below poverty people. Buffer measurement method can include more people and service area, while network method gives detailed traffic information. They all have different specific functions.

## Specific call to action
I assume that my non-profit organization in Connecticut serves various socially disadvantaged groups listed in my table with medical needs, such as people below the poverty line, elders over 65, single women, and people working from home. People working from home are a special group of people. They may be inconvenient to move due to physical reasons. Or they are painters, writers. Such groups of people are likely to live in remote suburbs with inconvenient transportation. Therefore, the main service item of our non-profit organization is to provide transportation services for these people to the hospital.

Call-to action: 1. Comfortable home transportation 2. Get healthy quickly and go home quickly 3. Flying speed

## References 
[1] ArcGIS Network Analyst, esri. https://www.esri.com/en-us/arcgis/products/arcgis-network-analyst/overview#:~:text=ArcGIS%20Network%20Analyst%20provides%20network,represent%20their%20unique%20network%20requirements.
[2] Centers for Disease Control and Prevention. https://www.cdc.gov/dhdsp/maps/gisx/training/index.html 
[3] The numbers in the Tables of accessibility measures come from statistical analysis in ArcGIS Pro.
