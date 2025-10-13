+++
title = "Metra Ridership Project"
date = "2025-10-05T20:08:40-05:00"

#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."

tags = ["QGIS","transit","ridership"]
+++
A friend recently shared [an interesting article](https://citythatworks.substack.com/p/build-the-tunnel) with me which discussed their proposal for a set of cost effective measures to improve transit in the Chicago region. The article titled "Build the tunnel" supposes that significant expansions to the CTA L network, beyond the Red Line extension to 130th St, are inplausible in our current transit landscape. Their solution, unsurpisingly, was to #BuildTheTunnel, two in fact, one under Columbus and Ohio connecting the Metra Electric 18th St station to the three Metra Union Pacific lines just north of Ogilvie, and the other under Clinton connecting the BNSF line to the UP lines. I have included their map below for visual clarity.

<!-- Here I am commenting out a bunch of shit I was trying for formatting that I don't want to quite let go of

(![Map showing where the Build the tunnel crew would build their tunnel](/images/MetraRidershipBlogPost/BuildTheTunnelTunnnels.png) )
<div class="row">
    <div class="column">
        <img src="/images/MetraRidershipBlogPost/BuildTheTunnelTunnnels.png" alt="Map showing where the Build the tunnel crew would build their tunnel" width="50%">
    </div>
    <div>
        <img src="/images/MetraRidershipBlogPost/BuildTheTunnelPretty.png" alt="Pretty map showing where the Build the tunnel crew would build their tunnel" width="50%">
    </div>
</div>-->
<!--style="float:left; margin-right:10px;"
<img src="/images/MetraRidershipBlogPost/BuildTheTunnelPretty.png" alt="Pretty map showing where the Build the tunnel crew would build their tunnel" width="54%" style="float:left
;">-->
<img src="/images/MetraRidershipBlogPost/BuildTheTunnelTunnnels.png" alt="Map showing where the Build the tunnel crew would build their tunnel" width="60%" >
<br><small>Fig 1. A map from the article graphically illustrating the tunnels they would build</small>



I found this proposal fairly compelling, it is well established that transit capital costs in America are out of control. The Red Line Extension is shaping up to be one of the most expensive per mile of any subway project in the country. Barring wholesale reform of transit funding in this country, we will need to invest in precise and tacticle projects to improve service. Essentially, the article proposes that if we build 5.25 miles (slightly less than the RLE) of tunnel through downtown, it would allow us to optimize how we utilize our extensive existing infrastructure. Today Metra serves suburbanites who want to get downtown, and provides dissapointing service for folks trying to get around the city. This proposal would see the addition of "Crosstowner" service (Similar to the RER or S-Bahn), along the Metra ROW. This new Crosstowner service would utilize the new tunnels and a few infill stations in the city to unlock the potential of our existing regional rail network. They would provide a conveinient service for suburbanites travelling thru Chicago and a quicker way for Chicagoans to get to the further stretches of their city. They also propose that these Crosstowners would take over service to many of Metra's current inner ring suburb stations, allowing Metra trains to much more quickly ferry Aurorans and Elginers into the city.

This seems like an excellent use of our limited capital budget to me, but it left me with a lot of questions about the current use patterns of the Metra network. When studying their proposed routing options, I wanted to have a visual reference for what stations were more used and why they chose to certain service patterns for the crosstowners, and why the chose the stations to continue receiving metra service that they did. I figured ridership would be a driving facotr in where one would choose to maintain Metra service, so to crosscheck my assumptions I sought out a visual representation of Metra stations by ridership. The best I could find was, the [RTAMS report](https://rtams.org/ridership/metra/stations) of Metra ridership by station, in a spreadsheet. I love spreadsheets, but they're not a quick reference, and since I wasn't immediately finding the map I wanted, I decideded to create my own. All I needed was a visualization of  the Metra stations by ridership, and to add context, I added an OpenStreetMap layer, found the official shapefiles for the Metra and CTA networks, and put it all together in a map. For so few data points I find it easier to input the ridership by hand than to clean up my CSVs, so after an afternoon I had the map I was looking for.

![Map of Metra ridership](/images/MetraRidershipBlogPost/MetraRidership.png)
Fig 2. My map of Metra ridership

I think on its own this provides a valuable resource of a quick to digest Metra map.  The downtown stations are the buisiest by far, and surprisingly few of the inner city stations receive much ridership. Very few stations outside of the loop even have a direct L connection, even where the Orange line shares ROW with the Heritage Corridor, which strikes me as a bit of wasted potential. I see the demand spoken of in the article, of Suburbanites trying to get downtown, and I see how reducing the number of stops that Trains from Aurora to the Loop benefits commuters, and having more frequent crosstowners would benefit those in the city and inner suburbs. Right now there are 25 stops between Aurora and Union station, and this proposal would see that number cut down to 10.