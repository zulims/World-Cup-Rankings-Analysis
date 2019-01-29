# World-Cup-Analysis
### Looking for Relationship Between FIFA Rankings and Actual World Cup Performance - 1994-2018

Once every four years the best soccer (football) teams from around the world gather to compete for the FIFA 
World Cup. Each team receives an algorithmically generated ranking from FIFA that is connected to the perceived strength of the team; a ranking is
also given to countries not in the tournament.

We analyzed and mapped the rankings of every country from around the world since 1994 to see changes over time. We then compared those rankings to 
tournament performace in order to observe whether a strong correlation exists between ranking and performance, and whether some countries tend to over 
or underperform their rankings.

## Final Web Page
We built a web page to visualize our findings using HTML, CSS, and JavaScript. The chloropleth primarily leveraged Leaflet.js, while the scatterplot primarily used D3.js. Both were controlled with the year slider you can see between them.

I was primarily responsible for the dynamic scatterplot and dug deep into D3's logic in order to build it. The size of the datapoints on the plot are indicative of a nation's legacy as a world cup contender. If the user selects a different year using the slider, these datapoints drift to their new appropriate coordinates in a 1.5 second transition.

![full dashboard](images/full_dashboard.jpg)

