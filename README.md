# convert-osu-beatmap-to-osustream
Python script that osu! beatmap to an osu!stream beatmap

Uses **BeatmapCombinator** from [osu!stream source-code](https://github.com/ppy/osu-stream/tree/master/BeatmapCombinator), which takes an adjusted osu beatmap and converts it to osu!stream file format (osz2).
Manually adjusting the beatmap folder is a process of adding metadata file, resizing thumbnail, and converting the audiofile to m4a; A process that can become time-consuming if you want to convert multiple maps.

This script I made quickly automates the long process of adjusting of the beatmap folder, and dynamically runs the combinator.
