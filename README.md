# featherUploader 1.0.1
Auto-discovery and uploading of binaries to adafruit feather devices

This node script will auto-discover your adafruit feather device, reset the device into uploader mode, and then upload the given binary.

You'll need to to `npm install` to install Node dependencies

Requires: [Node](http://nodejs.org/), [Arduino.cc](http://www.arduino.cc/) IDE (installed, but doesn't need to be running)

usage: `node featherUploader <fully-qualified path to .bin file>`

NOTE: only tested under macOS so far


RELEASE NOTES:

  1.0.1 - added config.json so the path to bossac and manufacturer string can be configured

  1.0.0 - initial release


