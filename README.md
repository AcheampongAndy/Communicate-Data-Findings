# (Dataset Exploration Title)
## by (your name here)


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The start_time and end_time were object data type, I changed them to datetime data type and split the date and time into four variables start_time, end_time, start_date, and end_date.
I also remove all the NAN values to make the dataset ready for analysis.

## Summary of Findings
In the exploration, I found that there was a strong relationship between the
duration second of a GoBike and its bike id, with modifying effects from the member gender,
and bike_share_for_all_trip of the GoBike dataset. Interestingly, 
it appears that there are some negative relationships between the categorical 
variables and the two numeric variables of interest. The bike dataset with 
the best features (subscriber, female, no) seem to get the lowest duration seconds and bike_id, 
but also tend to be greatest on average. 

Outside of the main variables of interest, it doesn't seem to be that much interaction between 
df_bike user_id and member_gender, though proportionally it seems like there might 
be more subscriber user_type on the greatest member_gender (male and female). 
There are no interactions on the bike_share_for_all_trip and gender_member, 
the lower level for both yes and no is the other. 
It looks like there are more *male* in the member_gender.

## Key Insights for Presentation
For the presentation, I focus on just the influence of the on the three variables of 
GoBike: bike_id, member_gender, and bike_share_for_all_trip. I start by introducing the
duration second variable, followed by the pattern in bike id distribution, then plot the
transformed scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the violin plots of duration seconds and bike id. I'm only looking at
the clarity  plot here since it's the clearest example of how the
categorical variables affect GoBike duration seconds. The other two categorical
variables, member gender and bike_share_for_all_trip, are covered afterwards, using point plots. 
I've made sure to use different color palettes for each variable to make sure it
is clear that they're different between plots.
