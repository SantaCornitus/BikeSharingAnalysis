# (FordGoBike Tripdate Exploration)
## by (Torben Mulitze)


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

The dataset consists out of tripdata gathered by an bikesharing serverice which has rental bikes all over the city. 
In total it consisted of  183.412 rows and 17 columns with  mainly string an float and some integer values.
Since the dataset was quite clean the wrangling efforts where overseeable. 
	-Removing rows with missing values. Since there are only 8000 entrys with missing values those were removed.
	-Convert data columns from string to datetime object.
	-Converting birt_ year to integer type.
	-Columns as station_id should be integers to instead of floats. Since they were not used during the analyses they were left as where.
	-Created a day of week columns as wel as hour of the day column to make visualizing more easy.



## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

In[9] Since there where some outliers far beyond the mean Travel time all outliers above 2.5 times duration-sec mean's where removed to make a clear visualization is show in the  4th image in de plot.
	Most trips done with the rented bikes have aduration between 100 and 1000 seconds
In[10]The Data consist data from the motnh February in 20019
In[11]The most used starting staion is named 'Market St at 10th St' with a total of almost 3500
In[12]The least used station as starting station is '16th St Depot' with only 2 rides
In[13]The most used ending stations is named 'San Francisco Caltrain Station 2' with  more then 4500 rides
In[14]THe least used end station is named '21st Ave at International Blvd' for only 5 bikes
In[15]Listed here are the top 10 Bikes with the most rides. The bike with an ID of 4794 made over 175 rides already
In[16]The rental service by far is most used by subscribers
In[17]For the most part most of the rides are made by Males
In[18]The average birthyear of the ride was 1984. Most riders are born between 1980 and 1992
In[19]Most rides are made  on Thurstdat. In the weekend the service gets used the least
In[20]The most bikes are started around 8 in the morning and 17 in the evening
In[21]Looking at this graph the share of customers vs subribers during certain ours of the day seem te be the same.
In[22]Subribers make on average only half as long rides as 'customers'
In[23]Although there are les trips made during the weekends the duration per trip on average is longer.
In[24]The age of customer and subscribers does not vary very much adn is between 20 and 60
In[25]Subscribers who are male make out over 60 % of the rides
In[26]During the week between 6 and 20 a clock most rides are made with peaks around 8 in the morning and 17 in the evening
In[27]Under the top stations there are no abvious difference in use between male and female




## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
In[21] The visualisation shows the most bussy ours on average split up over the customer types. You can see that the share of customer compared to subscribers stay prettymuch the same.
In[26] The heatmap shows during which day of the week during with hour the most rides take place.
In[25] In this visualisation the customer are split up in 6 groups. We see Male who are subscriber to the service make the most use of the service. (over 60%)
