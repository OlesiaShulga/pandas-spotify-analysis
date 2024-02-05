**Project intro**

* This research analyzes Spotify dataset encompassing track releases over 63 years (from 1957 to 2020).
* The dataset comprises 32,833 records with details on track names, artists, release dates, genres, popularity scores and various audio features.
* Descriptive analytics was performed on the historical data to understand and summarize key characteristics, trends, and patterns within a dataset. 
* The analysis results are based on the assumption that the data provided is consistent and accurate, though it’s not. The dataset doesn’t include sufficient amount of records to provide a comprehensive analysis of industry trends and patterns.

**Dataset description**

* track_id: The Spotify ID for the track
* track_name: Name of the track
* track_artist: The artists' names who performed the track
* album_name: The album name in which the track appears
* track_popularity: The popularity of a track is a value between 0 and 100, with 100 being the most popular
* track_album_id: Album unique ID
* track_album_name: Song album name
* track_album_release_date: Date when album released
* playlist_name: Name of playlist
* playlist_id: Playlist ID
* playlist_genre: Playlist genre
* playlist subgenre: Playlist subgenre 
* danceability: A measure of how suitable a track is for dancing. A value of 0.0 is least danceable and 1.0 is most danceable.
* energy: Represents the intensity and activity within a track. Higher values indicate more energetic and fast-paced tracks.
* key: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1
* loudness: The overall loudness of a track in decibels (dB)
* mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0
* speechiness: Measures the presence of spoken words in a track compared to instrumental sounds. Higher values indicate tracks with more spoken words, like podcasts or audiobooks.
* acousticness: Measures the probability of a track being acoustic. Higher values indicate tracks closer to being purely acoustic.
* liveness: Indicates the presence of a live audience in the recording. Higher values suggest a higher likelihood of the track being performed live. 
* tempo: Represents the speed or pace of a track in beats per minute (BPM).
* duration_ms: Duration of song in milliseconds

**Research steps**

* initial data preprocessing according to business requirements
* data cleaning, including identifying and handling null values, outliers, duplicates, formatting inconsistencies
* exploratory data analysis
* key findings summarizing 

**Research goals**

* explore the dynamic of track releases over the years
* investigate correlations between numeric values (e.g. whether the track popularity depends on specific audio feature)
* explore track releases seasonal trends
* observe audio features changes over the years
* find out the most popular tracks in each genre
* identify the most influential artists 

**Key findings**

* The number of track releases started to increase significantly in 2000s and reached a peak in 2019.
* The number of genres spans over 6 categories, including rap, pop, electronic dance music, latin, r&b and rock each with 4 corresponding subgenres.
* Average track duration across all genres was increasing from the late 50s (2.4 min) up to late 80s (4.7 min) with a peak in 1971 (5.0 min) and then started to decrease gradually (3.2 min). We can observe various periods of increases and decreases for particular genres, but a tendency to track duration decrease is common for all genres.
* Seasonal trends chart represents monthly patterns on track releases, from 60s to 00s most track releases were in January, and only starting from 2012 the trend starts to change and the month with most number of releases becomes November.
