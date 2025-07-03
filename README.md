# ytdlp-downloader-windows (GUI, Kind of)
A lightweight GUI based on Windows VBS script that uses yt-dlp to download videos or playlists from YouTube and other supported platforms, with selectable resolution.

### Features
* Can download single or an entire playlist.
* Selectable videos from playlist.
* Video or Audio download.
* Selectable WEBM (default, fast) , MP3 (Converted, bit slow) options for audio.
* Selectable quality (Best, Worst, 144p, 240p, 360p, 480p, 720p, 1080p, 1440p and 2160p)

### Requirements
* Functional Brain
* [yt-dlp](https://github.com/yt-dlp/yt-dlp) (download zip from releases)
* [ffmpeg](https://ffmpeg.org/download.html) for conversion ofcourse.

### How to use:
* Simply put the vbs script into your yt-dlp folder and run from there, follow instructions.
* Files are downloaded to "Downloads" folder automatically created inside the folder.

### NOTE:
* You gotta use ffmepg (download ffmpeg and put "ffmpeg/bin" folder path into your Enviromental Values Path) to get both video and audio merged. Else you'll get separate audio and video file.
