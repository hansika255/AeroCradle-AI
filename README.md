# Cat's Cradle Pro

An interactive browser-based Cat's Cradle string simulation that uses webcam hand tracking to let you hook, drag, release, and shape a virtual loop with your fingers.

## Features

- Real-time hand tracking through MediaPipe Hands
- Webcam mirrored background with canvas-based string physics
- Finger-tip interaction for catching and moving the loop
- Curl gesture support for dropping a hooked loop
- Guided tutorial mode with step targets
- Preset layouts for Cat's Cradle, Soldier's Bed, and Jacob's Ladder
- Free Play mode for experimenting with the string

## Files

- `Catscradle.html` - Complete standalone HTML, CSS, and JavaScript app.

## How to Run

1. Open `Catscradle.html` in a modern browser.
2. Allow camera access when prompted.
3. Bring both hands into the camera frame.
4. Use the on-screen controls to start the guide, choose a preset, reset the string, or enter Free Play.

## Requirements

- A webcam
- A modern browser with camera support
- Internet access, because MediaPipe scripts are loaded from jsDelivr

## Controls

- `Start Guide` - Starts the interactive tutorial.
- `Reset` - Resets the string and current guide step.
- `Cat's Cradle` - Loads the Cat's Cradle preset.
- `Soldier's Bed` - Loads the Soldier's Bed preset.
- `Jacob's Ladder` - Loads the Jacob's Ladder preset.
- `Free Play` - Clears presets and lets you interact freely.

## Interaction Tips

- Move straight fingertips close to the glowing string to hook it.
- Pull hooked fingers apart to stretch the pattern.
- Bring fingertips together to shift loops between fingers.
- Curl a hooked finger inward to release that part of the loop.

## Notes

The app is self-contained in a single HTML file, but it depends on external MediaPipe CDN scripts. If the camera does not start, check browser permissions, use `https://` or `localhost` when serving the file, and confirm your browser allows webcam access.
