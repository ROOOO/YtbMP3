# DISCRIPTION
 Download Youtube videos and convert them to Audio Format On your own Server. Download and enjoy it!
## Required
- youtube-dl
- Python 2.x
- ffmepg

## Usage
 - On Server Side
    python ytbmp3Server.py [OPTIONS] URL [URL ...]
 - On local Side
    python ytbmp3Local.py [OPTIONS] IP

### Notes
 - URL can be a playlist.

## OPTIONS
 - Server
  -p         HTTP/HTTPS proxy.(example: -p http://x.x.x.x:xxxx)
 - Local
  -p         Server port(default 23333)

## DISCRIPTION
 1. Run `ytbmp3Server` on server.
 2. Run `ytbmp3Local` on local for downloading mp3 files you downloaded on server.

