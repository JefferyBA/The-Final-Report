# The-Final-Report

## FINAL REPORT
### Business Analytics Skills Workshop, Group 8

#### Jordan Fischer
#### Austin Frazer
#### Tingyu Xie
#### Jingbo Zhang
#### Junfei Zheng

As the world becomes more urbanized, understanding urban logistics and maximizing resources in urban settings will be ever more important. Bike sharing systems are a form of public transportation that is cheap and environmentally friendly; it also lessens traffic congestion and even improves public health. They are being implemented in a growing number of cities around the world. Even automotive companies are trying their hand in this form of transportation, such as Ford with it’s GoBike  in San Francisco.

Particularly in DC, the recent influx  of competition in the automated short-term bike rental market makes this study particularly timely. Dockless bike companies like LimeBike, ofo, Mobike, Spin, and Jump have all set up shop in the DC area in late 2017, which could make the city’s original automated bike rental company, Capital Bikeshare, fearful for their slice of the market. However, subtle differences in operation mean that dockless bikes, which rent per hour, are most useful for short-term visitors to the city, while Bikeshare, which rents per trip OR with week-long or year-long memberships, is more useful for longer-term residents of the city. This means that the two systems could theoretically share the market comfortably. 

This analysis studies Capital Bikeshare bike use based on geography, user type, weather conditions, and surrounding demographics to determine usage patterns. The biggest challenges we faced in this task was the sheer size of the dataset. At 771,068 lines, the initial data cleaning and the geocoding of the stations was quite burdensome. We found another file at opendata.dc.gov that had the geolocations of the bikeshare docks. We used Excel (this being done prior to our instruction in R and Python) to match the station ID number in both tables so that we could append the Latitude and Longitude to the rest of the data. Even once we finished adding data points and cleaning the data, some visualizations, like the bike trip path map, were too dense for us to draw out any patterns.

Here is an example of our early attempts at mapping using a Tableau template to map the routes:
![picture7](https://user-images.githubusercontent.com/21350380/32204546-3fa7a4c6-bdc0-11e7-9c8b-b16d104439f1.png)

We eventually managed this by looking at single bikes’ trips over time, which reflected similar patterns as we found elsewhere in the analysis, and was much more intelligible. This technique can be seen in our final Tableau storybook. 

Overall, we found that Capital Bikeshare use is highest among longer-term residents, for whom it is more economically sensible to purchase a year-long membership. While casual users are common in the downtown areas and near the National Mall, where many tourist attractions are located, the company has strong infrastructure in DC’s neighborhoods and periphery, which is where they attract their many registered, long-term users. This means that competition from dockless competitors like LimeBike might not have a very strong impact on their business model – casual users only make up about 20% of Capital Bikeshare’s total customers.  

Perhaps a group next year could examine 2017 Q4 data to examine the change in Capital Bikeshare utilization once its dockless competitors entered.  That group could see if the number of total rides decreased.  They could examine the member/non-member distribution to see if the new services are primarily siphoning off casual users.  That team could look at the distribution of trips to see if the services are competing with each other or are being used in tandem.  For example, if most of the trips for a dockless bike began (or ended) near a bikeshare and ended (or began) in an area not served by the bike stations, then these two services could end up being employed in a complementary manner.  (This is the user experience of a member of this team.)  The dockless bikes would be solving the “last mile ” problem.  But if the dockless bike trips begin and end near bike docks, then these trips are directly competing with the established order of bikesharing.  And finally, if the dockless bikes begin and end nowhere near bike docks, then these two systems are neither helping nor hurting each other; their use would be considered completely orthogonal.

### We here in Group 8, 2017, look forward to that future group’s findings.  In the meantime, our complete story visualization can be found here:  https://public.tableau.com/profile/jordan.fischer4857#!/vizhome/DCBikeshareAnalysisBASkillsgroup8/BikeshareStory






