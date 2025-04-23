# Unsupervised_DJ

The Unsupervised_DJ is based on a real dataset of songs from 1950-~2019. 
This dataset contains a mix of lyrical and continuous variables pulled from a 2020 research paper titled <u>***Music Dataset: Lyrics and Metadata from 1950 to 2019***</u>.

The goal of this exercise is to analyze the dataset, its lyrical features, and (optionally) its lyrical content in order to discover clusters and create a comprehensive machine learning pipeline that satisfies the patterned steps of a classic machine learning project. 

#### Disclaimer: note that as this is real-world data, lyrical content is often obscene. 


The contents of this dataset are: 

Categorical:

1. artist_name: The name of the artist

2. track_name: The name of the song

3. release_date: When this song was released

4. genre: The categorical genre of this song

5. lyrics: The pre-tokenized lyrics of this song. 

6. topic: The categorical label of lyrical content

Numerical: 
1. len:  The number of words in the lyrics of this song

2. dating: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with dating.

3. violence: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with violence.

4. world/life: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the world or life in general terms.

5. night/time: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do night-life or time.

6. shake the audience: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with provocative feeling.

7. family/gospel: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with family-oriented content or the gospel.

8. romantic: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with romantic feeling.

9. communication: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with communication (either in romantic terms or otherwise).

10. obscene: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with obscene content (money, rockstar-lifestyle, etc).

11. music: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with music (music about music, basically).

12. movement/places: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with movement or various locations.

13. light/visual perceptions: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the sun or other physical weather-related patterns.

14. family/spiritual: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

15. sadness: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

16. feelings: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with emotions, either positive or negative.

17. age: A score from 0 to 1 expressing how “old” a song is from our perspective. 1 being the oldest, and 0 being the newest.
***
# Modules/Libraries
+ Python
+ Numpy
+ MatplotLib
+ Scikit-Learn
+ Pandas
+ Seaborn

# Exploratory Data Analysis
## Univariate Analysis
+ Pop, Country and Blues are the top 3 genres in this dataset.
+ The number of songs increased with each decade. There was a slight dip from the 1980s to the 1990s, but the trend regained footing after 1990s. The majority of songs come from the 2010s.
+ The songs are broken down into 8 different topics. `sadness` is the most popular topic. 
+ The 1980s and 2000s are the two decades with the most songs.
+ Johnny Cash and Ella Fitzgerald are the two 2 artists, based on song count. Dean Martin is not too far behind. 

## Bivariate Analysis
+ Pop Music has the highest count of `obscenity`, `sadness`, `violence` and `world/life` themes. 
+ Pop Music consistently leads the genres across all decades with Country Music not too far behind. 
+ Obscene Music climbed dramatically from a meager start in the 1950s to the highest topic by the 2010s.

## Multivariate Analysis
There is a slight correlation between `len` and `obscene`, suggesting that long songs might contain more obscene lyrics. The `romantic` type has a weak, positive correlation with `age`. 

