# song-recommender

## Using webscrapping and a Spotify API to create a song recommender

![image](https://user-images.githubusercontent.com/88676121/150969838-12616898-9e0f-4da4-8c1c-7168e7214eae.png)

## Table of contents
- [Project Brief](https://github.com/PolFerrandis/song-recommender#project-brief)
- [Data](https://github.com/PolFerrandis/song-recommender#data)
- [Process & Tools](https://github.com/PolFerrandis/song-recommender#process--tools)

## Project Brief
**Scenario**: We will use webscrapping to build an intitial and MVP first music recommender. Once this is build we will upgrade it by adding different spotify playlist.

**Challenge**: We will use webscrapping for the MVP and a spotify API for the final prototype.


## Data

MVP: We´ll start by going to https://www.billboard.com/charts/hot-100/ and Scraping the current top 100 songs and their respective artist.

The data set consists of:

- 100 songs

- 2 features; Song and Artist

Final prototype: We will extract data of 8 different playlist from different genres: jazz, pop, rock, country, hip-hop, Folk&Acoustic, Indie and a large mixed playlist.

The data set consists of:

- 1801 songs
- 4 features; Song name, Song URI, Song ID and Song Artist

## Process & Tools

**Process**

Our process included the following steps:

Dataset preparation

EDA: assessment of dataframe to prepare for cleaning

Data cleaning & wrangling in Python: 
    
- Merging both datasets

- Dropping duplicated songs
    
- Extract audiofeatures and merge with dataframe

- Transforming data and creating clusters of the playlist dataframe

- Create recommender




