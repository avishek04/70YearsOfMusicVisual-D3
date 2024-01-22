# 70 Years Of Music Visualization using Python and D3

This project delves into the dynamic world of music, leveraging a comprehensive database to uncover trends, genre fusions, and artistic evolution. Fueled by technology and social shifts, it aims to visualize connections between genres, songs, and lyrical preferences. Motivated by a shared passion for music, the project merges diverse skills to gain insights, contributing to both academic and professional realms. Ultimately, it seeks to offer a unique perspective on music's ever-changing landscape.

**Main Objectives:**

1. Analysis of features/attributes for top songs along the years.
2. Visualization of genre popularity trends throughout 1950 to 2019.
3. Visualization of the top 1% most used words (excluding common words like a, an, the, etc.) each year/decade - (1950-2019).

## Reference

**Project Live Website:** 
[https://dataviscourse2023.github.io/final_project_MV/](https://dataviscourse2023.github.io/final_project_MV/)<br>

**Data Source:** 
1. Lyrics and Metadata from 1950 to 2019 - https://www.kaggle.com/datasets/saurabhshahane/music-dataset-1950-to-2019?select=tcc_ceds_music.csv
2. Spotify Official API - https://developer.spotify.com/documentation/web-api
3. Spotify Tracks Dataset - https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

**Tech Stack:**
1. Python
2. D3.js
3. JavaScript
4. HTML
5. CSS

## Highlights

**1. Home Page**
<br> The default page it directs to when user first go to our project link. The home screen gives a brief overview of the project and what information does it provides to viewers. 

**2. Spider Chart**
<br>The spider chart provides a comprehensive analysis of key musical attributes, each ranging from 0 to 1, offering a nuanced understanding of songs' inherent qualities.
<br>Feature: We can select two songs at a time using the drop down options which will give us a better comparison of the songs’ attributes - which is shown on the tabs on the left hand side - as we overlap the chart on top of the other.

**3. Heat Map** 
<br>This heatmap provides a comprehensive visual exploration of the popularity dynamics of music genres over distinct decades. The x-axis delineates different historical periods, while the y-axis showcases a diverse array of music genres.
<br>Feature: Mouse hover shows a small pop-up window that gives information/ popularity for the selected genre and decade.

**4. Cluster Plot**
<br> Cluster plot analysis of top 1% unique words across decades in song lyrics. The presented cluster plot offers a comprehensive insight into the lexical landscape of songs spanning from the 1950s to the 2010s. 
<br> Feature: Mouse hover highlights instances of the same word in different decades with small detail window pops up at the bottom of the screen for each deacade (if the word is present in that decade) that shows: 

1. The word selected.
2. Number of times the word is repeated in that decade.
3. Ranking of the selected word (higher rank indicates more repetition).
