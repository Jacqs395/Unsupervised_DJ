# Unsupervised_DJ

The Unsupervised_DJ is based on a real dataset of songs from 1950-2020. 
This dataset contains a mix of lyrical and continuous variables pulled from a 2020 research paper titled ***Music Dataset: Lyrics and Metadata from 1950 to 2019***.

The goal of this exercise is to analyze the dataset, its lyrical features, and (optionally) its lyrical content in order to discover clusters and create a comprehensive machine learning pipeline that satisfies the patterned steps of a classic machine learning project. 

#### Disclaimer: note that as this is real-world data, lyrical content is often obscene. 


The columns in the dataset are: 
* artist_name: The name of the artist

* track_name: The name of the song

* release_date: When this song was released

* genre: The categorical genre of this song

* lyrics: The pre-tokenized lyrics of this song. 


* len:  The number of words in the lyrics of this song

* dating: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with dating.

* violence: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with violence.

* world/life: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the world or life in general terms.

* night/time: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do night-life or time.

* shake the audience: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with provocative feeling.

* family/gospel: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with family-oriented content or the gospel.

* romantic: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with romantic feeling.

* communication: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with communication (either in romantic terms or otherwise).

* obscene: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with obscene content (money, rockstar-lifestyle, etc).

* music: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with music (music about music, basically).

* movement/places: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with movement or various locations.

* light/visual perceptions: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the sun or other physical weather-related patterns.

* family/spiritual: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

* sadness: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

* feelings: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with emotions, either positive or negative.

* topic: The categorical label of lyrical content

* age: A score from 0 to 1 expressing how “old” a song is from our perspective. 1 being the oldest, and 0 being the newest.


