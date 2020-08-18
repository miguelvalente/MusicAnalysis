# Fork of <a href="https://github.com/benfwalla/MusicAnalysis" target="_blank">`GeniusMusicWrapper`</a>


**Changes**

- Changed the webscrapping to use CSS selectors
- Added a Genre collumn for each song
- Added a method to be able to retrieve a genre for each song if possible




---

## Example (Optional)

```python
   token = "INSERT YOUR TOKEN HERE"
   g = GeniusArtistDataCollect(token, artistname)
   #You can pass a genre for a Artist or use the get_genre() method by uncommenting line 85
   songs_df = g.get_artist_songs(genre)
```

---
