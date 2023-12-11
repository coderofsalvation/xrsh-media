place for media/recording related files (to embed/transcribe etc)

# generate audio from mp4 files

To save space in the repo, just run this after cloning:

```
$ find $(pwd) -type f -iname '*.mp4' | while read mp4; do ffmpeg -i "$mp4" "$mp4.mp3"; done
```
