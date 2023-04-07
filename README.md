# vlc-alarm-clock
An alarm clock app utilizing python-vlc for my absurdly specific use case.

Essential features:  

* Selectable audio output independent of system audio.
* Treats a pause command as equivalent to a 'snooze' button.
* If selected audio output is a Bluetooth device and is not currently connected, automatically attempts to re-connect before running alarm.