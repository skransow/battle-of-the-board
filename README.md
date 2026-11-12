# Battle of the Board

Live tracker for the Battle of the Board Tension Board 2 competition, hosted by Rock Revolution.

- `index.html` is the start menu. Choose whether the device is the tracker or the display.
- `tracker.html` is the tracker. Run the event from it on the phone or iPad.
- `display.html` is the live display for the laptop. Enter the 4-character display code shown at the top of the tracker.

The tracker sends live updates through free public MQTT message servers (shiftr.io, EMQX and HiveMQ), and the display listens for them. Both devices need an internet connection. Event progress is saved in the tracker device's browser.
