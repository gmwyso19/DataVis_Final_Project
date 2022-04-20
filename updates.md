## March 21

Today, I did some research to try to find a data set on PFAS water contamination across the U.S.

##March 23 Beginning of Class

I found a data set for my project but it required permission from the organization so I submitted a request form, and then I also installed that blogdown package. I don't really have anythink to push because my work was mostly not in R.

## March 23 End of Class

I foumd a data set! So now I have started creating an interactive map of the U.S. for the data that I found. 

## March 28 Begginging of Class

In between class meetings, I worked on sorting through my rather large data set and starting to create a map of California. I realized while working that I want to use Leaflet . And I found some info about the my data set and topic.

## March 28 End of Class

I know it doesn't look like much progress but I have been working all class to try to figure out how to use leaflet to make the graph, as I am having trouble understanding leaflet. Hopefully by next class I will have a leaflet graph made so I can start focusing on additional graphics for my blog, and start to add my work to my blog! 

## April 4 Beginning of Class 

To be honest with you, I was not able to work on the project much this week as I have been struggling with a sinus and ear infection, but I was able to work on it for a couple hours. There I tidyed my data a bit differently so that I was able to make clearer visualizations. I ended up creating a lollipop graph and a facted scatter plot, both of which need some revisions. I also have been watching some tutorials on leaflets.

## April 4 End of Class

I worked on trying to make a plotly graph but kept getting and error, and then I also seperated my lollipop graph into two to make it more readable. I was also playing around with my data set to see if I should be using more that just data of California from January 2020.

## April 6 Beginning of Class

I worked on my additional visualization. I changed my mappings of concentration, to mappings of average concentrations because it made my visualizations make more sense and look a lot better. I also tried changing the population_served variable to a numeric which eliminated a lot of rows so I need to fix that. But all in all I made a lollipop chart, a scatterplot, and tried to make another lollipop chart of population so I could compare population with average concentration of PFOA.

## April 6 End of Class

Embarassingly I spent most of class today trying to fix my Population variable. I finally got it to return to a character value and used the parse_number() function to make it a numeric again, but now I am having trouble with averaging the population variable. I decided a visualization of the average population per county would be more fair because the certain counties have different recorded populations served within the county. Once this problem is solved though, my additional visualization in my blog will almost be done!

## April 11 Beginning of Class

Over the weekend I was finally able to figure out how to order the bars in my lollipop graph. I am still having trouble trying to fix the Population Variable so that it is a numeric or double rather than a character value so that my scatter plot will be ordered correctly. And then I spent most of my time trying to find a data set that has Califonia county coordinates on it so I can join that with my water data set, so that I can make an interactive leaflet graph.

## April 18 Beginning of Class

I know it really does not look like a did much over the weekend but I promise you I did work on the project for 3 hours. I had a lot of trouble trying to figure out how to rename rows in a column. I had to change the names of the counties in my new data set to all caps so that it would match my water data set when I did a full_join(). After about 2 hours of researching and coding, I finally figure out how to do that with the toupper() function. Then once I figured that out, I tried to rerun my full_join() and I came across this error "Error in UseMethod("full_join") : no applicable method for 'full_join' applied to an object of class "character""." No matter my efforts with joining I kept getting this error. Once I figure out how to fix this error, I will be able to make my leaflet graph and work on my blog. Again, I apologize that it looks as though I did not work on the project, but I can promise you I did and it really frustrated me that I only got this far, as I was planning on making my leaftlet graph over the weekend.

## April 18 End of Class

In class today I was able to successfully join my data sets together and start my leaflet graph. I was having some trouble with that so I decided to work on tidying up my lollipop graphs, which Patrick suggested to me, by making the labels interactive, and I will also be rounding the populations to the nearest person as that seems to make more sense.

## April 20 Beginning of Class

Between Monday and Wednesday, I worked on creating some leaflet maps. Using both leaflet and plotly. They both did not run the way I intended them and need some more work, which hopefully I can accomplish in class today. But before I was able to do that I had to change the Longitude and Latitude variables from characters to numerics. I did so initially with the as.numeric function, and realized that was a mistake, and went back and renamed the data set and used the parse_numbers() function.

## April 20 End of Class

During class today I focused on trying different ways to make maps. Although most of them did not run correctly, It was helpful to see multiple ways that I could create the maps I have in mind. Hopefully this weekend I will be able to finalize a map.