Playlist definitions (SQL) based on ratings
====

templates for ratings based playlists to use with the [Dynamic Playlist](https://wiki.slimdevices.com/index.php/Dynamic_Playlist_plugin) and the [SQL Playlist](https://wiki.slimdevices.com/index.php/SQL_Playlist_plugin.html) plugin<br><br>
Place them in the **definitions** folder of the **SQL Playlist** plugin.<br>
If that folder doesn't exist create it and set the plugin's preferences accordingly.<br>
<br><br>
**All** playlists have these **criteria in common**:
- only include tracks with a duration of > 90 seconds
- ignore tracks with the word *never* in their comment tags
- ignore these genres: Classical, Soundtrack
<br><br>

**90s_sel_no_12inches_with_RATED_PERCENTAGE**<br>
tracks with *90s* in their comment tag, ignore those with *12″* or *Extended* in their album title
<br><br>
**RATED__1**<br>
all rated tracks
<br><br>
**RATED__2-with_TOP_PERCENTAGE**<br>
all rated tracks, choose the percentage of tracks with rating > 2 stars to include
<br><br>
**RATED__by_DECADE_1**<br>
all rated tracks of a decade you choose
<br><br>
**RATED__by_DECADE_2-with_TOP_PERCENTAGE**<br>
all rated tracks of a decade, choose the percentage of tracks with rating > 2 stars to include
<br><br>
**RATED__by_GENRE_1**<br>
all rated tracks of a genre you choose
<br><br>
**RATED__by_GENRE_2-with_TOP_PERCENTAGE**<br>
all rated tracks of a genre, choose the percentage of tracks with rating > 2 stars to include
<br><br>
**RATED__by_GENRE_and_DECADE_1**<br>
all rated tracks, choose a genre and a decade
<br><br>
**RATED__by_GENRE_and_DECADE_2-with_TOP_PERCENTAGE**<br>
all rated tracks, choose a genre, a decade and the percentage of tracks with rating > 2 stars to include
<br><br>
**RATED_UNRATED_1-with_RATED_PERCENTAGE**<br>
all unrated tracks, choose the percentage of rated tracks to include
<br><br>
**RATED_UNRATED_by_DECADE-with_RATED_PERCENTAGE**<br>
all unrated tracks of a decade, choose the percentage of rated tracks to include
<br><br>
**RATED_UNRATED_by_GENRE_with_RATED_PERCENTAGE**<br>
all unrated tracks of a genre, choose the percentage of rated tracks to include
<br><br>
**RATED_UNRATED_by_GENRE+DECADE-with_RATED_PERCENTAGE**<br>
all unrated tracks, choose a genre, a decade and the percentage of rated tracks to include
<br><br>
SQL Playlist lists the playlists in the same order as it finds them in the definitions folder (sorted by filename). That's why some of the playlist names end with _1.