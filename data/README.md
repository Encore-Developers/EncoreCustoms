# Resources:
- https://tunebat.com/Analyzer - getting the key of a song (these likely won't be accurate all the time, but then again as long no one notices it's fine. if a song has a pro vocal or real instrument chart it's probably better to guess based on those...)
- \[literally any DAW\] - Tempo/BPM (just put the song's chart into REAPER or something, if it changes, use the starting BPM. if it's variable, round it up to the nearest whole number)
- i've personally been making the song previews by importing the stems into fl studio and re-exporting them to MP3, but you could probably do it in anything else; user preference
- https://cloudconvert.com - converting stuff
- https://odesli.co - song.link

# Metadata Guide:
## Info
- title = The Song's Name, make any adjustments as needed for bot consistancy
- artist = The song artist,  make any adjustments as needed for bot consistancy
- album = The album the song is featured in, stick to the song's release album and not use compilations, if it's not in a album, leave this field out of the track
- charter = Anyone who authored the chart
- language = The language(s) the song lyrics are in; include regardless if a Classic Vocals chart exist. Null values will default to English
- releaseyear = The year the song debuted
- genre = The genre of the song, don't be too specific, if the author included a specific genre: keep it in the bot, don't make adjustments.
- cover = The art that will be displayed anywhere that uses this API
- source = The origins of the chart. Defaults to custom. Use YARC OpenSource IDs.
- loading_phrase = The loading_phrase of the chart, shorten if needed.
- key = The key and mode that the song is in. Try to refer to the charts Classic Vocal/Pro Keyboard charts if they exist
- duration = The duration of the song. Refer to the duration listed in the chart metadata
- ageRating = The age rating of the song, if not set by charter or listed in any game--add it yourself. Follows Rock Band guidelines: Family Friendly, Supervision Recommended, Mature Content
- is_verified = Is the song verified in the Songs repository or not?
- is_cover = Is the song a cover or not?
- currentVersion = The charts current version starting from when it was added to this API. Increase by one if a update to the chart was made. This is how the bot looks at the MIDI files so it's extremely important.
- format = The format of the chart. Only JSON and INI applies at the moment.
- fiveLaneHard = Does the chart use the fifth lane on gamepad Hard?
- doubleBass = Does Classic/Elite Drums have Expert+?
- proVoxHarmonies = How many Harmony tracks are charted on Classic Harmonies?
## API Data
- createdAt = The date of time the chart was published, in ISO 8601 format.
- songLink = The song.link page of the song.
- previewUrl = The filename of the songs audio file. Must share the same name as the shortname
- download = The charts Github download. If the chart isn't on Github, upload it to this repository.
- preview_time = The time the song preview starts in milliseconds.
- preview_end_time = The time the song preview should end at in milliseconds. Try to keep the length below 45 seconds.
- music_start_time = The time the song starts for the music command in milliseconds. Usually starts after the count-in.
## Difficulties
- drums = The difficulty rating of Pad Drums
- lead = The difficulty rating of Pad Guitar
- rhythm = The difficulty rating of Pad Rhythm Guitar
- bass = The difficulty rating of Pad Bass
- keys = The difficulty rating of Pad Keys
- vocals = The difficulty rating of Pad Vocals

- plastic-drums = The difficulty rating of Classic Drums
- plastic-guitar = The difficulty rating of Classic Guitar
- plastic-rhythm = The difficulty rating of Classic Rhythm Guitar
- plastic-bass = The difficulty rating of Classic Bass
- plastic-keys = The difficulty rating of Classic Keyboard
- pro-vocals = The difficulty rating of Classic Vocals

- 6-fret-guitar = The difficulty rating of 6-Fret Guitar
- 6-fret-rhythm = The difficulty rating of 6-Fret Rhythm Guitar
- 6-fret-bass = The difficulty rating of 6-fret Bass

- real-guitar = The difficulty rating of Pro Guitar
- real-rhythm = The difficulty rating of Pro Rhythm Guitar (Not Applicable)
- real-bass = The difficulty rating of Pro Bass
- real-keys = The difficulty rating of Pro Keyboard

- elite-drums = The difficulty rating of Elite Drums
- elite-keys = The difficulty rating of Elite Keyboard
- elite-guitar = The difficulty rating of Elite Guitar (Not Applicable)
- elite-bass = The difficulty rating of Elite Bass (Not Applicable)
