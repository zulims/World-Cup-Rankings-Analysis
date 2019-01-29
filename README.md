# World-Cup-Analysis
### Looking for Relationship Between FIFA Rankings and Actual World Cup Performance - 1994-2018

Prior to the World Cup, each team receives an algorithmically generated FIFA ranking that is connected to the perceived strength of the team. We were interested in visualizing how predictive these rankings tend to be of a team's later performance in the World Cup.

We analyzed and mapped the rankings of every country from around the world since 1994 to see changes over time. We then compared those rankings to tournament performance in order to observe whether a strong correlation exists between ranking and performance, and whether some countries tend to over or underperform their rankings.

## Final Web Page
We built a web page to visualize our findings using HTML, CSS, and JavaScript running on a Python Flask app. The choropleth primarily leveraged Leaflet.js, while the scatterplot primarily used D3.js. Both were controlled with the year slider you can see between them.

I was primarily responsible for the dynamic scatterplot and had to dig deep into understanding D3's logic in order to build it. The size of the datapoints on the plot are indicative of a nation's legacy as a world cup contender. If the user selects a different year using the slider, these datapoints drift to their new appropriate coordinates in a 1.5 second transition. Teams that later failed to qualify are shown falling off the plot, while new contenders emerge onto it. The closer a team appears to the diagonal line across the plot, the more predictive their FIFA Ranking was prior to the tournament.

![full dashboard](images/full_dashboard.jpg)

