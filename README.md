# TheBeatlesMachineLearning
Using Spotify API to create a data set which include The Beatles discrography.
Followed [this guide](https://stmorse.github.io/journal/spotify-api.html) to create the data set

Ideas for the project<br />
* Classify songs with their correct album<br />
* Predict whether a song is first/last track based on song characteristics <br />
# Data Set Features <br />
* danceability:describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall * regularity. A value of 0.0 is least danceable and 1.0 is most danceable.	<br />
* energy: a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.<br />
* key	:The key the track is in<br />
* loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks.<br />
* mode:Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.<br />
* speechiness	:detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. <br />
* acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.<br />
* instrumentalness: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context.<br />
* liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.<br />
* valence	:A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.Tracks with high valence sound more positive.<br />
* tempo	: The overall estimated tempo of a track in beats per minute (BPM).<br />
* time_signature:	An estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar.<br />
* track_name: Track name without any extra information	<br />
* track_number: Track number on the album<br />
* short_album_name: Album name without any extra information ex: Remastered,year etc<br />
* release_date: Year/Month/Day<br />
* album_cover	: URL to the album image<br />
* duration_seconds : How long the song is in seconds<br />
* track1 : If the song is the first track on the album 1 = yes<br />
* last_track: If the song is the last track on the album 1 = yes<br />
