# Wake County health code violations
[data_source]: (https://data-wake.opendata.arcgis.com/search?tags=restaurants)
I found data about health inspection violations from the [Wake County Open Data](data_source) website. It got me thinking--are there areas that are more likely to have lower health inspection scores than others? I chose zip codes because most people can tell you their zip code but not many can tell you their census tract.
For each restaurant, I added the points deducted from all of the available health inspections. It's helpful to use points rather than just a count of violations because worse violations get more points deducted. Then I averaged the restaurant scores for each zip code.
#### Results
Worst zip code? 27604, on the northeast side of Raleigh. They have a couple of restaurants with over 200 points deducted but what seems to make them different from other areas is that they don't have as many low scoring restaurants to bring their score down.
Best zip code? I'm going to say 27523, Apex. Technically it should be 27562, New Hill, but they only have one restaurant, so I don't think that's technically fair. Apex has the lowest score if you exclude all the zip codes with 2 or fewer restaurants.
Worst individual restaurant? Super Wok in Cary. There were several times where employees didn't wash their hands. But they get pretty good reviews on Google maps, so maybe it's worth it.
Best individual restaurant? Hard to say. The data covers at least the past 10 years, so the restaurants with fewer violations are often just the newest ones. This is something I'd like to play with, maybe only include inspections from the past year or so? Average across all years in operation?
#### Limitations
Like I mentioned, I want to find a way so that newer restaurants don't have an advantage over older restaurants.
I'm also not sure that averaging the restaurant scores is the best way to represent the data.
And on an aesthetic note, I don't like the clustering function, but you can't see all the points without it. Something I'll have to work on.
