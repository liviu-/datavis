# Popular Music Genres Since the 50s

![The Visualisation](figures/visualisation.png)
<p align="center"> <a href="https://raw.githubusercontent.com/liviu-/datavis/master/billboard_100/figures/visualisation.png">Larger Image</a></p>

## General information
- This only looks at the songs from the year-end Billboard Top 100, and shows how the musical genres were distributed that year.
- Only the most popular genres were kept (Classical and Blues were removed among others).
- Some songs returned multiple genres, in which case all genres were kept and they all contributed to the total proportions.

## Insights
A couple _visual_ insights (no quantitive analysis performed):
- The 2010s seem to be one of the most diverse periods for popular music in regards to the genres represented
- Hip Hop had a boom between 1995 and 2005, but it seems to be on a downward trend
- Folk/Country seems to have been the most popular in the 2010s
- Jazz and Rock seem to be on a steady decline, while Pop seems to have been rather consistent

## Data extraction
- Billboard data was scaped off Wikipedia articles for each year (e.g. [Billboard Year-End Hot 100 singles of 1990](https://en.wikipedia.org/wiki/Billboard_Year-End_Hot_100_singles_of_1990)).
- Songs were paired up with a music genre using the [Discogs API](https://www.discogs.com/developers/).
- Some data cleaning was performed to solve cases where a genre couldn't be found e.g. removing the collaborating artists.

## Code
- The visualisation code is [here](notebooks/visualisation.ipynb), but the data and the scraping code is not public.
