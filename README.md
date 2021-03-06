<p align="center">  portfolio_data_analytics
<br>
A description of the contents of this portfolio folder
<br>
<br>
<p align="center"><center>Determining_Eviction_Correlates</center>
<br><br>
Date: June 20 2018
<br><br>
Assignment for Geography Systems and Analysis, taught by Stephanie Rosoff
<br><br>
Central Question: How the amount of evictions and eviction filings in a census tract connected to the presence and number of CitiBike stations in that tract
<br><br>
Bike sharing is accessed much less by lower income populations, and the presence of bike sharing stations is thought to be correlated with the gentrification of a neighborhood.
<br><br>
Why it matters: According to availible research, bike sharing is accessed much less by lower income populations, and the presence of bike sharing stations is thought to be correlated with the gentrification of a neighborhood. A symptom of gentrification is the removal of previous residents from their neighborhoods due to increasing lack of affordable rent. 
<br><br>
Tools used: ArcGIS
<br><br>
Result: We found a slight decrease in eviction filing counts, eviction filings per person, eviction counts, and eviction counts per person with the increase in CitiBike stations. However, eviction rate showed no pattern. Clearer variations were seen in poverty rate and median household income, with poverty rate decreasing and median household income increasing with each progressively larger bin of CitiBike counts. This corroborates previous research. 
<br><br>
Next Steps: The slight negative correlation between eviction rates and CitiBike presence may be due to the census tracts, 217 out of Brooklyn’s total 841, having already undergone the population shift associated with gentrification. Additionally to honing our 2016 analysis, we would like to look at historical eviction data, and compare that to the current presence of CitiBike stations. This is to attempt a conclusion about evictions leading to a population
shift, which we can then correlate with CitiBike Station presence. 
<br>
<br>
<br>
<center>Unsolved_Homicides</center>
<br><br>
Date: July 1 2018
<br><br>
Assignment for Geography Systems and Analysis, taught by Stephanie Rosoff
<br><br>
Central Question: What populations were experiencing more unsolved homicide cases. Our research looked at median household income of census tract the homicide occurred in, if it was within .1 miles of subsidized housing, and the race of the victim to try to determine if any or all of these factors had an impact on percentage of cases that fell under a certain case status. The three case statuses we divided the data into were ‘open’, ‘closed by arrest’ and closed without arrest.
<br><br>
Why it matters: This research was inspired by an article in the Washington Post titled ‘Where Cases Go Unsolved’, published on June 6, 20181. This reporting sectioned out cities into high arrest and low arrest neighborhoods and found there are clear spatial variations in rates. Those from low arrest areas interviewed in various cities described feeling like the police are not trying hard enough, and the police say that cases are harder to solve in areas with low police trust and cooperation. This leads to a vicious cycle of people in neighborhoods where police trust is low, trusting the police even less as time passes as they see murderers committing crimes with impunity.
<br><br>
Tools used: ArcGIS
<br><br>
Data used: Washington Post dataset containing information about 52,000 homicides. Geodata for the cities of LA and NYC, including locations of public housing. ACS demographic data by census tract. 
<br><br>
Result: We did not find a clear connection between either of the location income variables and case-status. However, these seems to be compelling evidence for the race of the victim influencing case-status, with Whites and Asians having the highest percentage of cases cleared and Blacks the lowest, in both cities.
<br><br>
Next Steps: This research finds a compelling argument for racial disparity in arrest rates, but still more factors have to be examined. We hope to get funding and access to private police force data for further research into this topic, to look more at income and other demographic attributes of either the victims or the scene of the crime.
<br>
<br>
<br>

<center>Air_Quality_Sensors_NYC_Buses</center>
<br><br>
Date: Dec 14 2018
<br><br>
Assignment for Civic Analytics & Urban Intelligence, taught by Neil Kleiman and Alexander Shermansong
<br><br>
Abstract: Relevant city, state and private interests should install air quality sensors on a sample of MTA buses that cover all bus routes. These sensors will transmit real-time data on PM 2.5, Nitrous Oxide, and Black Carbon to a central database, which will be publically accessible as open data. This project will benefit environmental researchers, help set and monitor emissions standards, and lead to the improving of public health. In the long run it will provide a proof of concept to other cities, and allow for the expanding of mobile air quality monitoring across the globe.
<br><br>
<br>

<center>Hotel_Hubs</center>
<br><br>
Assignment for Applied Data Analytics for Public Policy, taught by Julia Lane and Daniela Hochfellner
<br><br>
Date: April 20 1018
<br><br>
Collaborators: Jacqueline Cafasso, Dahlia Darwiche, Timothy Hambridge, and Haoran Huang
<br><br>
Abstract: This study aims to predict the number of hotel hubs in a given zip code in New York City. Drawing on data from PLUTO and the American Community Survey (ACS), we use demographic and land-use variables to predict zip codes that have an above average number of hotels. Using a random sample of 30,000 observations from our overarching population, which contains over 30,000,000 records from 2011-2016, our analysis reveals that the mean score for hotel hub for the random sample was .155, suggesting that roughly 85% of the zip codes analyzed had a below average number of hotels. It follows that zip codes that have a below-average number of hotels, an abnormally high population, median household income, or assessed value may be prime spots to for future hotel establishments. Moreover, these initial results will serve as an enrichment tool for understanding the relationships between hotels and urban structure while also helping practitioners to identify tourism functional zones or potential sites for the establishment of new hotels.
<br><br>
Tools used: Python 
<br><br>
Related Code Snippet: counting_by_zip_codes.ipynb
<br><br>
<br>

<center>LaGuardia_Airtrain_Analysis</center>
<br><br>
Assignment for Applied Data Science, taught by Tim Savage
<br><br>
Date: Dec 18 2018
<br><br>
Collaborators: Zoe Martiniak and Katharine Voorhees
<br><br>
Abstract: 
A railway link to the LaGuardia airport has been a point of contention among city residents and travelers for two decades. The current AirTrain proposal will link to the 7 train and Long Island Rail Road (LIRR) at Mets-Willets point, claiming travel time of 30 minutes or less to Penn Station on the LIRR. Critics claim the LIRR is infrequent and will not provide reduced travel time to most parts of the city. To investigate this further, we test the hypothesis of whether the AirTrain will decrease Metropolitan Transit Authority (MTA) travel time for four origin points: Times Square, Harlem & 125th, Barclay’s Center and Flushing Library. For each origin location, real-time and scheduled travel data was obtained on the fastest routes to the airport, as determined by schedules. A Gaussian KDE distribution of wait times and travel times were produced for each leg of the journey and 1,000 random samples of total travel time were pulled for analysis. The travel times with and without the AirTrain were compared for each origin point using a Welsh 2 sample T-test. Our analysis concludes that out of the 4 locations we selected, the addition of the AirTrain solution would decrease travel time to the airport for those traveling from Times Square, Flushing Main Street, and the Barclay’s center.
<br><br>
Tools Used: Python
<br><br>
Related Code: https://github.com/zem232/LaGuardia-travel-times
<br><br><br>



