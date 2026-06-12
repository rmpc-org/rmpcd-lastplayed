A plugin that tracks the last played time of a song. The time is saved in the song's stickers and
thus `sticker_file` must be configured in your `mpd.conf`.

## Installation

1. Copy `lastplayed.lua` into your `rmpcd` config
2. Init the plugin by calling the following in your `init.lua`.
```lua
rmpcd.install("lastplayed")
```
