A plugin that tracks the last played time of a song. The time is saved in the song's stickers and
thus `sticker_file` must be configured in your `mpd.conf`.

## Installation

Put the following inside your `init.lua`. The plugin will be automatically downloaded and installed.

```lua
rmpcd.install({ url = "https://github.com/rmpc-org/rmpcd-lastplayed.git" })
```
