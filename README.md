# Nevada Latinos have more voting power than ever. Here's what that means for 2024
### The Nevada Independent

## Data Collection:

The Nevada Independent analyzed the political behaviors and growth of the Latino population in Nevada using two datasets from the U.S. Census. 

First, the Citizen Voting Age Population By Race and Ethnicity Database allowed us to analyze how the voting-age population of Latinos in Nevada has changed since 2009, which is the first year the data was collected. We used the R package cvap_get to import this data annually for the following geographies: Clark County, Washoe County, Nevada and the United States. By filtering this data to only include those who reported being Hispanic or Latino, we were able to analyze changes in the voting-age numbers across those geographies from 2009 to 2022. In addition, we also analyzed changes in other swing states, enabling us to compare Nevada's Latino population growth with the other states that will determine the winner of the presidential election.

The voting-age data also is reported on the Census tract level. To analyze how specific tracts of the Las Vegas Valley's Latino population changed over time, we imported shapefiles of Southern Nevada Census tracts from 2010 and 2020, and then joined those datasets with the corresponding Latino population in each census tract for both 2010 and 2020.

The other database we used was the Census' Current Population Survey, a frequent Census poll that looks at demographics, income levels voting behaviors and more. Specifically, we pulled online results of the survey taken after each presidential election since 2008. We used this data to create multiple datasets based on a respondent's race and ethnicity, which allowed us to determine how voting and registration behaviors differed across race and ethnicity in the past four presidential elections.

## Analysis:

Our findings underscore the growing power of the Latino vote in Nevada, particularly in Clark County, which is the epicenter of the state. However, the Latino voting bloc remains untapped given its lagging registration and voter rates compared to white and Black voters. Additionally, the Latino population is also growing immensely in other swing states — especially in Georgia and North Carolina, states that are not known for having a robust Latino population. This emphasizes the importance of the Latino vote in not only this election, but in future elections, as thier political power strengthens.
