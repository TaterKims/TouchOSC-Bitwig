# Novation SL49mk3 style TouchOSC mapping for Bitwig Studio
TouchOSC layout imitating the important parts of SL49mk3 DAW control surface layout for having the same experience in more portable fashion. Uses MIDI which [enables using USB connection](https://hexler.net/news/post/uncut-the-wire). On Mac it's best to be used in conjunction with [MidiTouchbar](https://urbanlienert.com/miditouchbar/).

Based on APC40 imitation using iPad Mini and Launchpad Mini (2017-ipad-launchpad), which got abandoned after getting Maschine Jam.

## Novation SL49mk3 layout

Has a nice subset of traditional APC40 functionality plus screens for device parameters as in Push controllers.

![SL49mk3 layout](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/2021-ipad-touchbar/media/sl49mk3.jpg)

## Mockup layout
![Layout Mockup](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/2021-ipad-touchbar/media/210122-mockup-1.jpg)

### Differences from Stock SL49mk3
- Two rows and playback controls in column for making things fit on iPad screen.
- Adds main output volume, useful on Macbook while MidiTouchbar hides default audio volume control.
- Active track selector is track arm. (DEV Note: Device control on MidiTouchbar might not follow device changes from TouchOSC as separate control scripts don't talk to each other.)
- Removed unused forward/rewind playback controls, maybe adding OVR / clip OVR later and other useful things.

# Status
Partially working, needs some fixes. Should be in usable condition in Q1 (2021) if not abandoned for some reason.

![Layout Screenshot](https://raw.github.com/jasalt/TouchOSC-Bitwig/master/2021-ipad-touchbar/media/210122-demo-1.jpg)

## In progress
- [ ] Clip launcher is glitchy. Original code used 4 tracks and 8 clips for clip launcher, was a bit hard wired to do just that and needs some more work.
- [ ] Layout is rough

