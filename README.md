# DRSKit v1.0

This is an old version of the DRSKit made by the DrumGizmo team and Jes Eiler of
[DRSDrums] and it is meant to be used only with sfz players.

**This work is not to be used as in the original scope with the DrumGizmo software
and then don't contact the original authors for any reason about it.**

The current version can be downloaded from the [DrumGizmo website],
made using multichannel wav files, which at the present time seems not to be
supported by most sfz players,
while this version was originally made with stereo files.

Mapped by kinwie using ARIA SFZ Level 2.0 for ARIA Player / Sforzando,
converted to flac samples.

## Description

Author: Lars Muldjord / Bent Bisballe Nyeng

DRSKit came to be as a collaboration between the DrumGizmo team and Jes Eiler of
DRSDrums (<http://www.drsdrums.dk>). Jes creates handcrafted drumkits under his
own label with an attention to detail not often seen on the market.
We gave him a call and asked if he would supply a kit for us to record.
And being the stand-up guy that he is, he offered to lend us an entire kit for free.
The kit contains the following components (Left / right placements as seen by the drummer):

- 1 kickdrum
- 1 hanging tom
- 2 floor toms
- 1 snare
- 1 hihat: Paiste Formula 602 Medium hi-hat
- 2 crash cymbals
  - Left: Paiste Giant Beat
  - Right: Paiste Formula 602 (Lend to us by Erik)
- 1 ride cymbal: Paiste Formula 602 thin crash

The kit should be usable for everything from jazz to rock.

## License


<a rel="license" href="https://creativecommons.org/licenses/by/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />
This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by/4.0/">
Creative Commons Attribution 4.0 International License</a>.

## Installation

For the ARIA Player multi (.ariax) files to work properly, you need to place
the "DrumGizmo" folder into your ARIA Player / Sforzando `User files path` directory:

`[User files path]\DrumGizmo\DRSKit\`

then you can load the `ariax` files or just drag'n drop it to ARIA Player GUI.

## Usage

- Each sfz file (mic channel) has each kitpiece Bleed level control
  that can be accessed at the Controls page.
- The "ALL" for control all kitpieces bleed level simultaneously
- In Snare bottom channel : "Drums" for kick & toms, "Cymbals" for hihat & cymbals
- All mic channels are mono audio so you need to do the panning in your DAW tracks:
  - Amb : L-R
  - OH : L-R
  - Tom 1-2-3 : left -to- right
  - Hihat : a bit left
  - Ride : a bit right
- If you don't have ARIA Player, then you can load each sfz file
  into 13 instances of sforzando.
- 3 kit versions : Full, No whiskers and Whiskers only (F, N and W)

**Notes**:

- The velocity range is distributed evenly.
- Added keys for muting the cymbals.
- You can change the key mapping of the drum notes to your likes very easily via
  keymap.txt with a text editor.

## Recording setup

### Microphone setup

- Close mic: Snare top: Shure Sm57
- Close mic: Snare bottom: Shure Sm57
- Close mic: Tom1: Shure Sm57
- Close mic: Tom2: Shure Sm57
- Close mic: Tom3: Shure Sm57
- Close mic: Kick drum back: AKG D112
- Close mic: Kick drum front: Shure Sm57
- Close mic: Ride cymbal: Beyerdynamic MCE 86 II
- Close mic: Hihat: Beyerdynamic MCE 86 II
- Overhead: Focusing on left crash and hihat: Røde Nt5
- Overhead: Focusing on right crash and ride: Røde Nt5
- Ambience: Focusing on entire kit placed further back in the room to the left: t.bone Rb500
- Ambience: Focusing on entire kit placed further back in the room to the right: t.bone Rb500

### Channel setup

All microphones are connected to its own channel when loading the kit in DrumGizmo.
13 channels total. Remember to pan the relevant channels to give you a better
stereo effect.

- Ch 1: Ambience left
- Ch 2: Ambience right
- Ch 3: Kickdrum back
- Ch 4: Kickdrum front
- Ch 5: Hihat
- Ch 6: Overhead left
- Ch 7: Overhead right
- Ch 8: Ride cymbal
- Ch 9: Snaredrum bottom
- Ch 10: Snaredrum top
- Ch 11: Tom1
- Ch 12: Tom2 (Floor tom)
- Ch 13: Tom3 (Floor tom)

## Thanks

This is a very great kit that contains all the bleed in each used microphone.
Many big thanks to all the DrumGizmo team and DRSDrums for this fantastic sample
library, and  that has been very kind making this kit available to us for free,
and to Lars Muldjord for kindly providing useful help.

# Changelog

## 9-July-2020

- New stereo Sforzando version
- Polyphonic Aftertouch feature for cymbals choke using E-Drums
- Variable hihats (CC4) for E-Drums
- Keyswitches for mapping mode
- The "Bleed ALL" control in the stereo version is turned off by default (0),
  to lighten the polyphony/voices consumption within single instance of Sforzando.
- "Bleed Bottom" is for enabling Kick and Toms bleed in the snare bottom channel.
- Caution for .ariax multi version : Do not change volume and pan (CC7 & CC10)
  from your Keyboard/MIDI controller/DAW MIDI track,
  because it will modify all the ARIA Player's slots/channels simultaneously.

[DRSDrums]:          http://www.drsdrums.dk/
[DrumGizmo website]: https://www.drumgizmo.org/wiki/doku.php?id=kits:drskit
