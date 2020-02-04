# m3u8-playlist-downloader
a script to download videos in a m3u8 playlis, write it to a single video file and convert it to mp4 using ffmpeg 

# dependencies
- requests module install using `pip install requests`<br>
- ffmpeg for video conversion visit https://www.ffmpeg.org/download.html

# usage
- create a virtual environment using `virtualenv -p python3.6 venv` in linux<br/>
- activate virtual environment using `source venv/bin/activate` in linux<br/>
- insert the url request headers in headers.txt<br/>
- start the script using `python m3u8_playlist_downloader.py <url of playlist>`

# options

- `--help, -h:- display how to use the script`<br>
- `--convert, -c:- specify this flag to convert the video to mp4 using ffmpeg`<br>
- `--name, -n:- specify the name by which to save the downloaded video, ele 'video' is chosen as default name`<br>
