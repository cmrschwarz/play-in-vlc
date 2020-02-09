# play-in-vlc
Convenient bash script to start playing songs in VLC Media Player

```
play [-f FILE] [-hansc] [PATTERNS...]
    Play all PATTERNS in VLC Media Player. 
    Patterns matching a filename play that file.
    Patterns matching a directory recursively play all songs in that directory.
    Any other patterns are interpreted as a regex for a file search.

    When the environment sets MUSIC_DIR, that directory is used for 
    regex searches and also checked for file / directory maches.

    Calling play with no PATTERNS / FILE is equivalent to play *.

    -h | --help    : show this help
    -a | --append  : instead of playing the songs, append them to the playlist
    -n | --dry-run : don't play, just print out the results to stdout
    -s | --sort    : play in sorted order (default is random) 
    -f | --file    : read additional PATTERNS from FILE
    -c | --clear   : clear the playlist beforehand 
```
