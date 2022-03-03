# surfs_up
Weather analysis with Python, SQLite, SQLAlchemy, and Flask

# Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

# Results
The following tables summarize June's temperature statistics over time.

![image](https://user-images.githubusercontent.com/95143562/156474773-cde96aac-499e-47cb-a942-f038ca90e9a9.png)

The following table summarizes Decembers temperature statistics over time.

![image](https://user-images.githubusercontent.com/95143562/156474534-9bda0503-2c85-4034-85f2-de06d2f8bbdf.png)

These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:

* Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
* The maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
* The minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

# Summary
Oevrall the weather in December and June are historically very similar, although December has a wider range of results, with its high being close to June's but its low well below June's.

Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
