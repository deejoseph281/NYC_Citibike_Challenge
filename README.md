# NYC_Citibike_Challenge
# Overview of Analysis

The purpose of this analysis is to recommend a bike-sharing program in Des Moines, Idaho to investors. The bike trip analysis uses data from the Citi Bike program in New York City as requested by the investors to represent traffic during the summer months. 

This analysis required us to change the datatype of the 'tripduration' column from an integer to a datetime datatype to get the time in hours and minutes. We would not be able to use the Date and Time column in Tableau to represent the visualizations required for the analysis. 

Once we converted the datatype, we exported the DataFrame as a CSV file to complete the visualizations in Tableau. 

<img width="925" alt="tripcolumn_datetime_datatype" src="https://user-images.githubusercontent.com/115019829/215015608-17291fe8-14d8-4d57-b7cc-f304ff123edd.png">

# Results

Our initial analysis reviews our the count of trip durations for each trip. We noted that trip durations were most frequent between under 1 hour to two hours. 

<img width="1008" alt="checkout_times_by_gender" src="https://user-images.githubusercontent.com/115019829/215015389-e8e79bb4-aad2-4708-88cb-2bf4bf63bb2c.png">

We also noted the majority of our subscribers are male. We see a minority of female or unknown gender users. 

<img width="1008" alt="checkout_times_for_all_users" src="https://user-images.githubusercontent.com/115019829/215015402-6862aaca-763e-4dc7-b4bf-a3c2a85d4bab.png">

Utilizing the heatmap function we are able to visually note that the usage of the program is concentrated on weekends, weekday mornings between 8 and 9 am, and heaviest on weekday evenings between 5-8 pm. From this visualization, we can also note that the maintenance of the bikes can begin to occur between 9 pm and 6 am. We can conclude that there is little variability for bike utilization. 

<img width="578" alt="heatmap_by_minute_by_hr" src="https://user-images.githubusercontent.com/115019829/215015414-ddc4e692-8f8a-4936-8bf0-6add87458fda.png">

There is no distinct difference in the days and hours of usage of the program between genders. 

<img width="1171" alt="heatmap_time_by_gender" src="https://user-images.githubusercontent.com/115019829/215015434-d42f0260-182f-4e55-b854-bab51004b7a3.png">

The program with the likelihood of success in Des Moines will be the subscriber model. As the analysis shows, we see heavy usage by males who are subscribers more than any other demographic or user base. 
<img width="1147" alt="heatmap_user_gender" src="https://user-images.githubusercontent.com/115019829/215015519-0e2fbd38-6131-490f-a9dd-69f5cecdd78b.png">


# Summary

Our analysis shows the program is successful among a male demographic, who are most likely to utilize the bike-sharing program for commuter purposes. We can also plan maintenance and usage of the program based on a subscription sharing program that makes the bikes available for the peak morning and evening hours, with a turnaround time for each bike of under 2 hours. 

## Recommendations
We recommend reviewing the most frequently used bikes as they would require the most maintenance. 

We would also recommend expanding the analysis to 12 calendar months to understand the seasonality and additional probability of a successful bike-sharing program in Des Moines. 

# Link to Tableau Public

[link to dashboard](https://public.tableau.com/app/profile/deejoseph281/viz/NYC_Citibikes_Challenge/Dashboard1?publish=yes)
