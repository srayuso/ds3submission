# Southern is the most affected district by larceny and theft

Our target in the study of the sanfrancisco_incidents_summer_2014 dataset is to identify the district that is most affected by incidents and the type of incidents that are most common on it. This analysis tries to simulate what a local law enforcement group could do to plan a strategy.

This first graph shows the amount of incidents per district, ordered from highest to lowest rate. Southern jumps out very clearly as the district most affected by incidents.

![Incident distribution by districts](districts.png "Incident distribution by districts")

If we would like to tackle the incidents with highest impact, we would need to know what types of incidents are most common so that law enforcement can focus their efforts on it. The following plot shows the distribution of incidents by category and also by district. Larceny and theft (combined in a single category in the dataset) jump out at the first look. There is a single box that calls for attention: the amount of larceny and theft in the Southern district. The plot also shows that Northern and Central would also be on the radar.

![Incident distribution by districts and category](heatmap.png "Incident distribution by districts and category")

One key aspect required to tackle the problem is the surface area of the affected districts. The following map shows the relative amount of larceny and theft incidents across districts, compared with the extension of those districts. The district limits in underlying map are plotted by coloring individual incidents. Southern is not only the most affected one, but its incidents are restricted to a relatively small area compared to other districts such as Taraval or Bayview.

![Larceny and theft across districts](map_districts.png "Larceny and theft across districts")


*This document serves as the homework for the first assignment of [Communicating Data Science Results](https://www.coursera.org/learn/data-results/) as delivered by Coursera.*
