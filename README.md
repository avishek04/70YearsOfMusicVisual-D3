# 70 Years Of Music Visualization using Python and D3
This project delves into the dynamic world of music, leveraging a comprehensive database to uncover trends, genre fusions, and artistic evolution. Fueled by technology and social shifts, it aims to visualize connections between genres, songs, and lyrical preferences. Motivated by a shared passion for music, the project merges diverse skills to gain insights, contributing to both academic and professional realms. Ultimately, it seeks to offer a unique perspective on music's ever-changing landscape.

**Our main objectives:**
<br>
1. Analysis of features/attributes for top songs along the years.
2. Visualization of genre popularity trends throughout 1950 to 2019.
3. Visualization of the top 1% most used words (excluding common words like a, an, the, etc.) each year/decade - (1950-2019).

<br>Library used: d3

## Final Submission
Project Website: [https://dataviscourse2023.github.io/final_project_MV/](https://dataviscourse2023.github.io/final_project_MV/)<br>
Project Screen-Cast: [https://youtu.be/QBHgvI3V9Ok](https://youtu.be/QBHgvI3V9Ok)<br>
Data: [https://github.com/dataviscourse2023/final-project-naep/tree/main/data](https://github.com/dataviscourse2023/final-project-chipmunks/tree/main/Data)<br>

## Highlights
**1. Home Page**
<br> The default page it directs to when user first go to our project link. The home screen gives a brief overview of the project and what information does it provides to viewers. 

**2. Spider Chart**
<br> The spider chart provides a comprehensive analysis of key musical attributes, each ranging from 0 to 1, offering a nuanced understanding of songs' inherent qualities.
<br>Feature: drop down options and overlapping spider plot
<br>We can select two songs at a time which will give us a better comparison of the songs’ attributes - which is shown on the tabs on the left hand side - as we overlap the chart on top of the other.

**3. Heat Map** 
  <br> This heatmap provides a comprehensive visual exploration of the popularity dynamics of music genres over distinct decades. The x-axis delineates different historical periods, while the y-axis showcases a diverse array of music genres.
<br> Feature: pop-up text bubble of the selected cell grid
<br> We can have more detail of the cells when going through them.

**4. Clustered Bubble Chart**
   <br> Cluster plot analysis of top 1% unique words across decades in song lyrics. The presented cluster plot offers a comprehensive insight into the lexical landscape of songs spanning from the 1950s to the 2010s. 
<br> Feature: bubble mouse hover information
<br> Mouse hover highlights instances of the same word in different decades with small key detail window also pops up at the bottom of the screen only if the word is present in that decade.
