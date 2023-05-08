# tidy_tuesday
Analysis of the #TidyTuesday bird feeder data set found here https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-01-10/readme.md

Tools: Python, Plotly, Pandas

If you have the pandas and plotly.express libraries installed, you can follow along with the Python notebook provided. The notebook explores bird sightings data and creates visualizations to understand patterns and insights. Here's a breakdown of the steps taken in the notebook:

## Count of Bird Sightings by State:
    A scatter mapbox plot is created, where the color and size of each point represent the count of bird sightings.
    This visualization helps identify bird sighting hotspots across different states.
![Sightings By State](/tidy_tuesday/bird_feeder_watch/plots/sighting_scatterplot.png)

## Bird Sightings by State:
    The number of bird sightings is analyzed by state.
    California and New York are found to have the highest number of sightings, which is not surprising considering their large populations.
![Bird Watching Popularity by State](/tidy_tuesday/bird_feeder_watch/plots/popularity_by_state.png)
![Bird Watching Popularity by State Choropleth](/tidy_tuesday/bird_feeder_watch/plots/sightings_by_state_choropleth.png)

## Unique Bird Species Observed by State:
    The number of unique bird species observed is analyzed by state.
    Texas is found to have the highest number of observed species, with 157 species recorded. According to tx.gov, there are over 600 bird species in Texas.
![Number of Unique Bird Species Observed by State](/tidy_tuesday/bird_feeder_watch/plots/species_by_state.png)
![Number of Unique Bird Species Observed by State Choropleth](/tidy_tuesday/bird_feeder_watch/plots/species_by_state_choropleth.png)

## Grackles:
    I think everyone living in Texas has noticed the large flocks of grackles hanging out on powerlines or in large box store parking lots. I created a dataframe specifically for grackles and a few different visualizations. There is an animated scatter mapbox that displays grackle sightings by day across the country. There is a scatter mapbox of grackle sightings by date in Texas. There is a density mapbox of the same data for Texas, and there is an animated scatter mapbox showing grackle sightings by species by date. 


