# TouchOSC mapping for Bitwig Studio 2.0

**See release 1.0 for Bitwig Studio 1.3.5+ support.**

[![Image](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/image.jpg)](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/image.jpg)

For more detailed info see blog post at [http://chronicoverengineering.com/touchosc-bitwig/](http://chronicoverengineering.com/touchosc-bitwig/).

## Features:

[![Layout view](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/anim.gif)](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/media/anim.gif)

- APC40 style mixer page with transport controls, track and master volume, pan, send 1, send 2, remote control knobs. Designed to be used with a separate grid controller.

- Remote control page with cursor track and device navigation.

- Drum Pads, 4 x 4, sending on midi channel 10, transpose up and down, macro knobs.

- Keyboard, 2 Octave, sending on midi channel 1, velocity on y-axis, transpose up and down, macro knobs.

- XY Pads, 4 x **TODO sliders and bypass buttons**

- A couple alternative pages with keyboard and XY pads and macro controls.

- Setup Page with One-Off Buttons to Midi-Learn the XY Pads (sending the same CCs). Contains in progress clip Launcher 8 x 4 Clips + 8 Scenes. Launch, Stop, Record (empty Slots), Launch Scenes. Move the Window around.

Based on initial work on TouchOSC layout by Astartes and modified by Thomas Helzle and bi-directional script by Thomas Henzle.

## Ideas
- Perform view VU meters
- Create layout for mixdown?
- Sync track bank focus changes with Launchpad (possible to pass data between different control scripts?)
- Sync device RemoteControl titles and track names possible?
