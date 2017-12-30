# m3u-playlist-file-command-line-

Create a .m3u playlist file from the command line. (UNIX)

## Instructions

Go to the folder containing all your mp3 files and execute this command on your terminal:

```
for f in *.mp3; do echo "$f" >> playlist.m3u; done
```
