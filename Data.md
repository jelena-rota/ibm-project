
<h2>The Battle of Neighborhoods - Data section</h2>

<p>Data used in the project will contain information about 59 neighborhoods in total, 40 Manhattan neighborhoods and 19 Downtown Toronto neighborhoods.</p>

Sources used for the data will be:
- New York University 
(https://geo.nyu.edu/catalog/nyu_2451_34572)
- Wikipedia
(https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)
- Cognitive Class
(http://cocl.us/Geospatial_data)

<p>Starting dataframe that needs to be prepared will have 59 rows and 4 columns (borough, neighborhood, latitude, and longitude). </p>
<p>It will be used by Foursquare API to explore the neighborhoods and return a json file with certain number of venues based on a defined limit and radius. </p>
<p>Resulting json file will be then cleaned and structured into a final dataframe with top 10 venues for each neighborhood. </p>
<p>Final dataframe with top 10 venues for each neighborhood will be used to group the neighborhoods into 5 clusters with k-means algorithm. </p>
<p>The neighborhoods that find themselves in the same cluster will be the one that are similar. </p>
