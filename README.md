# mpvscripts
KiSM's mpv scripts

### Why?
I created this project to:
- Implement the VLC crop hotkey 'c'
- Implement the VLC aspect ratio hotkey 'a'

More scripts may come in the future.

### File location

Where to put mpv lua scripts, create the folders if the don't exist:

\*nix:

`~/.config/mpv/scripts`

Windows:

`%appdata%\mpv\scripts`

### Modified so that it can be used to crop to a specific value directly

Example in input.conf:

`KEY script-message-to vlccrop crop_with_option [0|1|2|3|4|5|6|7|8|9|10|11]`
