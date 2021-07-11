Spotify Dashboard

Dashboard URL : https://app.powerbi.com/groups/me/reports/62eeecf5-e3a8-4970-a88c-3e6568469752?ctid=3ff0d950-c929-40cd-858d-6d3cbab9e019&pbi_source=linkShare

Youtube URL : 

It is built-in with URL redirects to spotify page to listen the song.

The data consists of approx 170k rows X 19 columns.

About the Data :
1. Numerical:
    acousticness - ranges from 0 to 1, transformed to (0-100)
    danceability - ranges from 0 to 1, transformed to (0-100)
    duration_ms - length of song in milliseconds, ranging from 5k to 5000k
    energy - ranges from 0 to 1, transformed to (0-100)
    instrumentalness - ranges from 0 to 1, transformed to (0-100)
    liveness - ranges from 0 to 1, transformed to (0-100)
    loudness - ranges from -60 to 0
    popularity - ranges from 0 to 100
    speechiness - ranges from 0 to 1, transformed to (0-100)
    tempo - ranges from 50 to 150
    valence - ranges from 0 to 1, transformed to (0-100)
2. Categorical:
    artists - list of artists of the song
    explicit - 0 = no explicit content, 1 = explicit content
    id - id of track from spotify
    key - octave scale, ranging from 0 to 11, 0 = C, 1 = C# and so on
    mode - 0 = minor, 1 = major
    name - name of song
    release_date - date/year of release of song
    year - year of release of song

Dataset URL : https://drive.google.com/drive/folders/1ECTeAvYClvx3hY2bWu9JBDEAvbq5LIp3?usp=sharing

The dashboard has 4 sections:
1. Top by popularity : where all the genres, artists and songs are given based on their popularity and you can search anyone of them individually to see their popularity index
2. Insights : which aims at showing the time-series analysis of music details individually
3. Song trend over time : one more TSA with all music details in a single go
4. Suggestion Box : the MAIN performer of the dashboard, I will leave it's exploration to you and don't forget to drill-down to song's details

![image](https://user-images.githubusercontent.com/69955872/116449587-f5012680-a877-11eb-83b8-477094d221ca.png)
