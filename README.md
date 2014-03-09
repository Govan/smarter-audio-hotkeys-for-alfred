# Smarter Audio Hotkeys for Alfred

![Screenshot of "Smarter Audio Hotkeys"](screenshot.png)

Adds play, pause, back and forward hotkeys that support a range of applications.
The current audio source will be controlled by

* F10 - go to start of current track/previous track
* F11 - pause current audio source / play last audio source
* F12 - go to start of next track

Note that the play action only works if the last application was stopped with
F11. If it an audio source can't be detected we'll default to controlling
iTunes.

## Supported Applications
*  iTunes
*  Instacast
*  Quicktime Player

## Todo

*  Refactor the scripts so they're not repeated for each hotkey 

## License

MIT © [Gavin Montague](http://leftbrained.co.uk)
