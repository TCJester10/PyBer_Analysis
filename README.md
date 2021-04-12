# PyBer_Analysis
Analysis of ridesharing data

   ## Overview of the analysis: Explain the purpose of the new analysis.
   In order to address the deiparities among the three city types PyBer operates in (rural, suburban, and urban), I have created an analysis in Jupyter Notebook 
   that looks into some basic differences in the three city types and will explain what I believe can be done to adress the differences between them. 
   ## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
   
   The first peice of data is the total rides that occured in each of the three. This will let us see where the bulk of the rides PyBer served were coming from. \
 ```  
Rural        125

Suburban     625

Urban       1625
```
What we see here is that Urban had by far the largest share of the rides, with Sububan coming a distant second and rual coming last. This tells us that urban environments are where PyBer is currently most used. 


Next, I looked at the total number of drivers in each city type.
```
Rural         78

Suburban     490

Urban       2405
```
What is noticeable is that Urban environments again are where the bulk of PyBer's resources are allocated. There are far more drivers in Urban environments than either Suburban or Urban environments. This already can let us begin to think. Perhaps Urban environments have more rides because there are more drivers there to do it. 

Before going too deep with two peices of data, I then looked at the total fare money coming from each of the city types. 
```
Rural       $4,327.93

Suburban   $19,356.33

Urban      $39,854.38
```
There is already a little different trend appearing. Urban environments still dominate this subset, but they do not quite dominate to the same extant as they did in previous ones. This shows that perhaps Urban environments are mainly full of shorter rides than Suburban or Rural areas. 

To follow up on that thought, I looked at the average fare per ride and driver.  
```
Rural      $34.62

Suburban   $30.97

Urban      $24.53
```
What we see is that Urban rides are indeed shorter than the other two if you go by pricing. It's interesting how Rural and Suburban are closer to each other than they are to Urban areas. You would think that rural areas would have far greater fares per ride considering how spread out they are. 

When looking at the average fare collected by driver, we see a different set of numbers. 
```
Rural      $55.49

Suburban   $39.50

Urban      $16.57
```
This shows the split one would expect. Distant Rural communities have long rides from point A to point B, suburban areas occupy a medium space, and urban areas are primarely used for shorter trips. 

and total fare by city type. 
![Graph I made](https://github.com/TCJester10/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

This chart showcases the total fare by city type over the course of January 2019 to May 1st, 2019. During this time wee see consistent placing between the three city types, the trends tend to differ a bit, but they never leave the pattern of Urban areas being by far the biggest share, suburban areas having the second biggest, and rural taking up the least. 

   ## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
   My first suggestion would be looking at where these rides are going. Perhaps there is a certain event or location that is a bigger draw than others like say from their home to the airport or a stadium on gameday. All of these are static events that have an important constant, paid parking. In rural and suburban areas, the biggest obsticle facing a rideshare company is that most citizens of these communities own a vehicle of their own, but even so, nobody likes to pay for parking. What Pyber can do is look for events that require parking to be paid and run specials for longer rides from the suburbs and rural areas to them. Another suggestion would be seeing if more drivers for these areas could be recruited. It is very noticeable that urban areas have far more drivers in them than suburban and rural communities. Perhaps if service was more certain in these areas, there would be more rides originating in them. A final idea, is perhaps offer different rates in each area. I'm less on board with this one, as each ride in the suburbs and rural areas tends to be longer than the others and thus generate more money per ride than the shorter urban areas, but nonetheless it is an option to charge more per mile in certain areas that don't bring in as big of a share of the overall income. 
