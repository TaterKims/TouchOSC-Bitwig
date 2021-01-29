# TouchOSC mapping for Bitwig Studio 2.0+

[![Image](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/2017-ipad-launchpad/media/image.jpg)](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/image.jpg)

## Status
Built on BWS 2 (API version 2), quickly tested on BWS 3.3.1 and it mostly worked. There's a [issue](https://github.com/jasalt/TouchOSC-Bitwig/issues/2) filed about compatibility so there might need fixing some deprecated API features.

## Features

[![Layout view](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/2017-ipad-launchpad/media/anim.gif)](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/anim.gif)

- APC40 style mixer page with transport controls, track and master volume, pan, send 1, send 2, remote control knobs. Designed to be used with a separate grid controller.
- Remote control page with cursor track and device navigation.
- Drum Pads, 4 x 4, sending on midi channel 10, transpose up and down, macro knobs.
- Keyboard, 2 Octave, sending on midi channel 1, velocity on y-axis, transpose up and down, macro knobs.
- XY Pads, 4 x **TODO sliders and bypass buttons**
- A couple alternative pages with keyboard and XY pads and macro controls.
- Setup Page with One-Off Buttons to Midi-Learn the XY Pads (sending the same CCs). Contains in progress clip Launcher 8 x 4 Clips + 8 Scenes. Launch, Stop, Record (empty Slots), Launch Scenes. Move the Window around.