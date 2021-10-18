# spotify_top_songs
# Top Spotify Songs of the 2010s, Analyzed
An analysis of the top songs on Spotify from the year 2010 to 2019. 
By Matt Lee

# Summary
* Case study for Google data analytics certification capstone project. 
* Collected data on top songs on Spotify from 2010 - 2019 from Kaggle. 
* Cleaned data using Google Sheets. 
* Visualized the changes in various musical attributes, tempo, and genre across the decade, using Tableau and Google Sheets. 
* Analyzed patterns to make predictions on future trends

# Business Task
For educational purposes, I am putting myself in a role at Spotify. They have asked me to analyze the top songs in the world for every year in the 2010s. The goal is for the results of this analysis to help predict the trends of the 2020s, which will help the company build algorithms that are more conducive to their listeners’ taste. 

# Data Cleaning
The data was not perfectly prepared for this analysis, so some cleaning was in order:
* Grouping highly specific genres into more broad genres for macro-analysis.
* Filling in missing genre entries and correcting incorrect ones.
* Correctly labeling all columns.

# About the Data
The data was sourced from a dataset called “Top Spotify songs from 2010-2019 - BY YEAR,” uploaded to Kaggle by the distinguished Leonardo Henrique.  Leonardo took the top songs from each year in the decade and ran them through the sorter at http://organizeyourmusic.playlistmachinery.com/ which gives a score for each of the thirteen attributes for every song.

# Attributes Collected
* Genre - the genre of the track
* Year - the release year of the recording. Note that due to vagaries of releases, re-releases, 
re-issues and general madness, sometimes the release years are not what you'd expect.
* Beats Per Minute (BPM) - The tempo of the song.
* Energy - The energy of a song - the higher the value, the more energetic. song
* Danceability - The higher the value, the easier it is to dance to this song.
* Loudness (dB) - The higher the value, the louder the song.
* Liveness - The higher the value, the more likely the song is a live recording.
* Valence - The higher the value, the more positive mood for the song.
* Length - The duration of the song.
* Acousticness - The higher the value the more acoustic the song is.
* Speechiness - The higher the value the more spoken word the song contains.
* Popularity - The higher the value the more popular the song is.
* Duration - The length of the song.

![](https://github.com/mattleesounds/spotify_top_songs/blob/main/Attributes.png)

![](https://github.com/mattleesounds/spotify_top_songs/blob/main/attributes_avg_change.png)

![](https://github.com/mattleesounds/spotify_top_songs/blob/main/avg_tempo.png)

# Attribute Analysis
* The most significant change among the attributes across the decade was a 20 point increase in popularity. This is mostly a result of Spotify becoming a more popular platform during this time period. 
* There seems to be a paradoxical trend across the decade where music became slower, less happy, and less energetic, while simultaneously becoming more danceable

![](https://github.com/mattleesounds/spotify_top_songs/blob/main/genres2010-2014.png)
![](https://github.com/mattleesounds/spotify_top_songs/blob/main/genres2015-2019.png)

# Genre Analysis 
* Although pop dominated throughout the decade, some of its market share was replaced by other genres as the decade progressed.
* Both electronic and R&B gained significantly in popularity. 
* Latin music gained a fair amount of listeners.

# Key Insights Overall
* The decline in average tempo is likely in part due to the rise in popularity of R&B, which uses slow tempos. 
* One weird pattern is that although the use of live instruments(acousticness) has gone up on average, the popularity of electronic music has risen significantly. 
* Listeners seemed to have an increasing appetite for music that is more laid back and more danceable. In other words, people increasingly wanted to “just vibe.”
* Traditional pop music may continue to decline in popularity, as tastes become more worldly and more chill. 

# Further Research and Limitations
* Ultimately, most of the measurements used in this analysis are subjective. The attribute scores were given by an algorithm that is, of course, imperfect. Genre discernment can also be quite controversial. 
* It would be interesting to see how this compares to an analysis of the Billboard top songs of the decade. 
* More analysis could be done on the pop genre by looking at how the distribution of subgenres changed over time. 










