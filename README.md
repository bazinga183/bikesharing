# bikesharing

## Overview of the statistical analysis:

The purpose of this analysis is to determine whether or not a bike riding business would be a proper fit within the city of Des Moines, Iowa using data from NYC's [Citibike data](https://ride.citibikenyc.com/system-data#:~:text=The%20data%20includes%3A%201%20Trip%20Duration%20%28seconds%29%202,10%20Gender%20%28Zero%3Dunknown%3B%201%3Dmale%3B%202%3Dfemale%29%20More%20items...%20). I will be using the data from Citibike to disect: the total number of bikes and their usages as well as how these bike usages break down by gender. This is done with the purpose of demonstrating this current research to pave the way for future research that will be needed for Des Moines to know if this project is feasible and more imporantly, profitable.

This project directly utilizes a story created using Tableau. It features a series of 7 visualizations that will be explained [here](https://public.tableau.com/app/profile/eduardo.flores1791/viz/Book2_16337278155490/Challenge?publish=yes).

## Results:

To begin, here is just a basic map of NYC, a highly-dense, populated city that holds almost 9 million people. Within this map, there are points labeled that show where the most popular starting locations are located:

![Capture1](https://user-images.githubusercontent.com/46951897/136875553-c9970fad-df0d-4286-bcad-d2f2225a2288.PNG)

Here,  within the heart of downtown, there are at least 1.6 million rides taken during the month of August during 2019. That is roughly 12.5% of NYC's population in rides. This bodes well if Des Moines has a similar population density as NYC.

Next, we have the duration of trips for bikes rides:

![Capture2](https://user-images.githubusercontent.com/46951897/136877707-29dda509-7270-4ca8-9270-eab88453866f.PNG)

If we look at the distribution of rides and their total duration in minutes, we notice that the most rides are less than 10 minutes in duration, many rides go over the twenty-miunte mark. However, almost none go past the hour mark. Therefore, it can be properly inferred that the bike rates should aim to capture audiences that ride their bicycles for short durations rather than for recreational purposes.

Another interesting aspect is if we break down these trips by gender first:

![Capture4](https://user-images.githubusercontent.com/46951897/136878484-ea6a2e71-6792-45ba-83aa-3dcda4958fc1.PNG)

Here, as the picture states the labels for gender are 1=male, 2=female, and 0=unknown. In total, there were 2,344,224 bike rides within this graph. Of those rides, 1.5 million were done by males (65%), 588,431 were done by females(25%), and 225,521 were from an unidentified gender (10%).

In addition, consideration should be given if there is space for recreational spaces, tourist spots, and/or trails that would be able to utilize the convenience of these bicycles.

Now that we have a general idea of the gender-to-rider distribution, we can breakdown just how these trip durations compare to each other:

![Capture3](https://user-images.githubusercontent.com/46951897/136879828-900e4dd5-5404-42c2-b725-c02b2be17e4f.PNG)

The image details the legend, but prior conclusions are justified by these breakdowns since most trip durations still are less than 10 minutes with most not going over 20 minutes and almost none reaching past an hour.

Now that we have both the breakdown of rides by gender and their duration, let us first see when these trips tend to take place:

![Capture5](https://user-images.githubusercontent.com/46951897/136881425-5e8c2ca2-dec9-49a6-bc37-b092a4b261a6.PNG)

According to this visual, these trips take place mostly before and after work hours for 9-5 jobs. Let us further breakdown how these trips take place by gender:

![Capture6](https://user-images.githubusercontent.com/46951897/136881947-776db9b0-070e-40c7-99db-3f667d290552.PNG)

Theese two visual combine to show that we should also look for a dempgraphic that would deeply benefit from the institution of bicycles as a means of getting to work. This idea could also be sold to Des Moines as a means of cutting down on greenhouse gases and making their city much greener.

One final factor we need to consider is the total amount of bikes that would be needed for this project that is proportional to the potential rider population. Here we have the total amount of rides per bike, but these are the bikes that have had the most rides in NYC for the month of August:

![Capture7](https://user-images.githubusercontent.com/46951897/136882859-4810ac2d-72bf-4912-8c1a-f80b58766b68.PNG)

Within this visual, we notice that each of the highest used bikes have at least 183 uses and up to 479 uses. This means that this project should take into account the potential amount of times a bike will be used as well as the repair time after a certain amount of uses. For the bikes used the least amount of times, we'll use 183 for this example, this means that a bike that is well-used should expect to be on the road for at least 1,830 minutes, or roughly 30.5 hours a month. 

## Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)
All-in-all, the analysis and visuals of the NYC Citibike Data suggest that the model, having been around for some years now, expreiences a high volume of usage; more than 2 million rides which is roughly 25% of NYC's population. This suggests a high usage rate within this dense city, especially among men who made up almost 66% of the bike riders for the month of August in 2019. All-in-all, the idea of promoting a new bike share company within Des Moines is not a bad idea, if a few conditions are met:
 - The city of Des Moines is relatively densely populated to where it is easy for bikes to be accessed by multiple potential customers.
 - The consideration of the male-to-female population ratio is taken into account and some analysis is done on the likelihood of each gender riding bikes. This can be measured by examining the average distance the citizens live from their workplace, if they would have easy access to a bike station, and if there are recreational spaces for the citizens to explore within the city.
 - Lastly, it must also be examined the durability of the bikes which will be purchased, and the amount of times that this said bike would be used. The less repairs needed, the more money can be saved in maintenance and parts cost. 

Other key points of analysis that are needed are essentially on the people of Des Moines and their likelihood of riding bikes, as well as the size of the population itself and where they are located so that the bike stations could be ideally placed.
