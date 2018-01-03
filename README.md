## Our team created predictive models at the Hack Austin event hosted by the City of Austin to answer the question: 
## How might we improve emergency response times within the city?

### A data-driven process for getting ahead of tragedy
### Team members:  Brandyn Adderly, Owen Temple, and Danielle Fenimore

https://austinstrategicplan.bloomfire.com/posts/1496098-2-winners-announced-at-civic-hackathon


### Predictive Mapping
Our time series model used past call volume and response times to forecast call volume and response times in 2018 and 2019. Our model forecasted trends and seasonality in average response times for all Austin areas combined.
![Average Response Time Forecast.png](https://media.data.world/MT7nqc9Seu9gk8nO8OdA_Average%20Response%20Time%20Forecast.png)

We also used the time series model to take a closer look at 3 specific response areas and employed ArcGIS to build an animated interactive map that shows our predictions for these areas: downtown, the eastern crescent, and Goodnight Ranch.

Click [here]((https://www.arcgis.com/home/webmap/viewer.html?webmap=d60ad3e973a545ef8f2d895b8b34d8e4&extent=-97.794,30.1425,-97.6786,30.176)) to view the interactive map for 3 response areas:
[Where is the fire going to be?](https://www.arcgis.com/home/webmap/viewer.html?webmap=d60ad3e973a545ef8f2d895b8b34d8e4&extent=-97.794,30.1425,-97.6786,30.176)

![Austin Fire Department Response Times.png](https://media.data.world/6ljiSKrTSOi3WPnwubUk_Austin%20Fire%20Department%20Response%20Times.png)


### Triage Response Areas:
Our random forest classifier model predicted late responses in some areas of the city  more than others. Perhaps we can use these insights to design very targeted interventions to reduce common causes of fires in these areas.

![Response Areas That Predicted Late Responses.png](https://media.data.world/aB4qNFIaTUGcF4164GIR_Response%20Areas%20That%20Predicted%20Late%20Responses.png)

Instead of raising priorities of problems through tragedies, we can help raise priorities through good data analytics. 
