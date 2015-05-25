# play-sound

[![Build Status](https://travis-ci.org/iamdenny/play-sound-v12.svg)](https://travis-ci.org/iamdenny/play-sound-v12)

Play sounds by shelling out to one of the available audio players based on node.js v0.12.x.

## installation

    npm install play-sound-v12

## examples

```javascript
var player = require('play-sound-v12')(opts = {})
player.play('foo.mp3') // $ mplayer foo.mp3 
```

Options: 

* `players` - list of available audio players to check (default: `['mplayer', 'afplay', 'mpg123', 'mpg321', 'play']`)
* `player`  - audio player to use, skips availability checks

## prior art

[play.js](https://github.com/Marak/play.js) - play sound files from node.js to your speakers

## license

MIT

