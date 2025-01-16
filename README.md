# SF-CycleInsight: Urban Mobility Analytics

This project analyzes the San Francisco bike share network using centrality measures from graph theory to understand the network's organization and evolution between July 2014 and July 2015.

## Background

The San Francisco bike share network has undergone significant changes since its inception. In 2013, the Bay Area Bike Share pilot project was launched, which has since expanded to cover approximately half the city with 320 stations and 4,500 bikes. The system, now known as Bay Wheels, operates at no capital or operational expense to taxpayers, thanks to private sector partnerships.

## Features

- Calculates and visualizes degree, betweenness, and closeness centrality
- Compares network changes over one year
- Identifies key stations and system dynamics

## Methodology

Our analysis employs various centrality measures from graph theory to understand the network's structure and evolution. We focus on:

1. Degree centrality
2. Betweenness centrality
3. Closeness centrality

These measures help us interpret the importance and roles of different stations within the bike share network.

## Results

Our analysis reveals interesting insights into the San Francisco bike share network's evolution from 2014 to 2015. While the specific results are detailed in the project files, we observed changes in network structure, key stations, and usage patterns.

## Discussion

The bike share network in San Francisco demonstrates characteristics of self-organization, with its structure emerging from user behavior. This analysis provides valuable insights for network optimization and expansion planning. It also reflects wider sociological, economic, and geographic factors influencing bike usage in different areas of the city.

## Conclusion

As we conclude our analysis of the San Francisco bike share network, it is evident that the past year has brought about notable changes. Although there was a slight decrease in the number of stations, the increase in trips suggests that the remaining stations are experiencing heightened usage and popularity. This trend indicates a strategic emphasis on enhancing service quality in areas with high demand. Additionally, the expansion of the network's diameter reflects a broader reach, facilitating longer rides and improved connections between neighborhoods. 

These insights illuminate how the bike share system is evolving to meet user needs and provide valuable information for future planning and enhancements. We trust that this analysis will deepen your understanding of the dynamics within our bike share network and inspire further improvements to make cycling in San Francisco even more accessible and enjoyable for all users.

## Future Work

Future analyses could explore:
- Impact of stationless bikeshare systems introduced in 2017
- Integration with other transportation modes
- Effects of the Bikeshare for All subsidized membership program on equity

## Requirements

R with the following packages:
- dplyr
- igraph
- ggraph
- ggplot2
- knitr

## Usage

1. Clone the repository
2. Open the R project
3. Run the R scripts

## License

#### Educational Project License

This repository contains an excerpt of academic assignment shared solely for professional portfolio demonstration and is not to be used as a reference or submission for academic coursework. Any reproduction, copying, or use of this code for educational assignments is strictly prohibited and may constitute academic misconduct.


## References

- Arino, J. (n.d.). *San Francisco bike share station information*. Retrieved November 22, 2024, from https://raw.githubusercontent.com/julien-arino/math-of-data-science/refs/heads/main/CODE/SF-bikeshare-station-info.csv

- Arino, J. (n.d.). *San Francisco bike share data: July 7, 2014 - July 13, 2014*. Retrieved November 22, 2024, from https://raw.githubusercontent.com/julien-arino/math-of-data-science/refs/heads/main/CODE/SF-bikeshare-1-week-2014-07.csv

- Arino, J. (n.d.). *San Francisco bike share data: July 6, 2015 - July 12, 2015*. Retrieved November 22, 2024, from https://raw.githubusercontent.com/julien-arino/math-of-data-science/refs/heads/main/CODE/SF-bikeshare-1-week-2015-07.csv
