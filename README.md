# play-in-vlc
Convenient bash script to start playing songs in VLC Media Player

```
play [-ah] [FILES...] [DIRS...] [PATTERNS...]

    Play all FILES, in DIRS contained files and files whose relative path
    from the current directory matches PATTERNS in the VLC Media Player.

    When the environment sets MUSIC_DIR and the current dir is not in it,
    the script changes directory to MUSIC_DIR.

    When no args are passed, play everything contained in current directory.

    -h | --help   : show this help
    -a | --append : instead of playing the songs, append them to the playlist
```
