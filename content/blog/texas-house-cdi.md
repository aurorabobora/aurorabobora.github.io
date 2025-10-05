+++
title = "Texas House Cdi"
date = "2025-10-04T19:51:45-05:00"

#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."

tags = ["markdown","syntax",]
+++

![CDI Map](/images/CDIMap.png)

The Congressional Density Index was developed by Citylab to gauge the Urban or Rural character of Districts in the US house of representatives, following along with their work I utilized QGIS to apply the same type of model to the Texas State House. The naive way to guage how urban a house district would be to look at its population density, but this fails to account for the distribution of that population. if 80% of a districts population lives in a dense city, but that only accounts for 20% of its land area, it seems more fair to classify this as a largely urban district than as a rural one, as the naive population density would indicate. To mollify this issue, I found the population density of every census tract in Texas, then assigned those tracts to a state house district. According to research by Jed Kolko, the density cutoff for which people were likely to describe their neighborhoods as rural was 102 households per sq mi, and for Urban it was 2,213. So I classified every tract into one of four density categories (two being in between), and found what share of a house district lived in the four levels of density. I then compared my results to that of citylabs CDI for the US house, and gave each district a CDI based on what house districts shared the most similar breakdown of density characteristics.
