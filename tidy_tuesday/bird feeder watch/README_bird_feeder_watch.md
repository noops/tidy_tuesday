# tidy_tuesday
Analysis of the #TidyTuesday bird feeder data set found here https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-01-10/readme.md

Tools: Python, Plotly, Pandas

If you have the pandas and plotly.express libraries installed, you can follow along with the Python notebook provided. The notebook explores bird sightings data and creates visualizations to understand patterns and insights. Here's a breakdown of the steps taken in the notebook:

## Count of Bird Sightings by State:
    A scatter mapbox plot is created, where the color and size of each point represent the count of bird sightings.
    This visualization helps identify bird sighting hotspots across different states.

## Bird Sightings by State:
    The number of bird sightings is analyzed by state.
    California and New York are found to have the highest number of sightings, which is not surprising considering their large populations.

## Unique Bird Species Observed by State:
    The number of unique bird species observed is analyzed by state.
    Texas is found to have the highest number of observed species, with 157 species recorded. According to tx.gov, there are over 600 bird species in Texas.

## Grackles:
    I think everyone living in Texas has noticed the large flocks of grackles hanging out on powerlines or in large box store parking lots. I created a dataframe specifically for grackles and a few different visualizations. There is an animated scatter mapbox that displays grackle sightings by day across the country. There is a scatter mapbox of grackle sightings by date in Texas. There is a density mapbox of the same data for Texas, and there is an animated scatter mapbox showing grackle sightings by species by date. 


![Popularity By State](/Users/bkirton/Desktop/tidy_tuesday/tidy_tuesday/bird feeder watch/plots/popularity_by_state.png)