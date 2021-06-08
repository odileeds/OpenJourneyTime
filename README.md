# OpenJourneyTime
MSOA to MSOA journey time pairs and MSOA-centred isochrones for North England (the English regions of North East, North West, and Yorkshire and the Humber). Calculated using the [Open Trip Planner for Great Britain](https://github.com/thomasforth/otp4gb) project. All journeys and isochrones are for arrival at the destination by 08:30am on 10 September 2019. Walking, cycling, and driving speeds are the default in Open Trip Planner v1.5 using the UK-specific routing rules. Road congestion is not considered. Public Transport is using the timetable on that day and includes journeys by all modes (train, tram, bus, metro, etc...).

Current outputs are,
1) Journey time matrix to the nearest minute between all road-snapped MSOAs in North England by walking, bicycle, car, and public transport. Journey times over 60 minutes are not reported.
2) Accessibility isochrones for all MSOAs in North England by walking, bicycle, car, and public transport. These are the starting points from which one can reach the road-snapped MSOA centroid within 15, 30, 45, and 60 minutes. 

Data can be explored in an interactive tool at https://www.imactivate.com/northernisochrones/.


## Further work
The [Open Trip Planner for Great Britain](https://github.com/thomasforth/otp4gb) has been tested beyond North England in Wales, Scotland, and the English Midlands. This data is used in our work here as journeys to points in North England can start in these countries and regions. Much of the development work for this project was done in Scotland and early versions of that output are online at https://www.imactivate.com/scotlandisochrones/. This project could be updated and completed to the same standard for Scotland as our work here for North England quickly and for a low cost. The same is true for Wales.

## Thanks
This is a project by Tom Forth at ODILeeds and ODILeeds. Final production of these isochrones and journey times was funded by [Transport for the North](https://transportforthenorth.com/). Multiple previous projects have contributed to this output including projects funded by Sheffield City Region, Network Rail in York, Greater Manchester Combined Authority, The University of Leeds (especially ITS), ARUP, Bradford City Council, Leeds City Council, Calderdale Borough Council, and many of the ODILeeds sponsors.

## License
Journey times are calculated from two main sources of data. Public transport timetables are [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). Open Street Map is [Open Data Commons Open Database License (ODbL)](https://www.openstreetmap.org/copyright). The resulting calculated journey times and isochrones are [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Tom Forth at ODILeeds and ODILeeds.
