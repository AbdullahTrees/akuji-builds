# Akuji the Demon: PortMaster testing builds

Test builds of the Akuji the Demon port for PortMaster handhelds (aarch64).

## Install

Download `akuji.zip` from [Releases](../../releases), then either:

- copy it to PortMaster's autoinstall folder and run PortMaster, or
- run `harbourmaster install akuji.zip`

The port installs as **Akuji** in the Ports menu.

## Controls

| Button | Action |
|--|--|
| D-Pad / Left Stick | Move and menu navigation |
| A | Jump / Confirm |
| X | Fire |
| Start | Pause / Confirm |
| Start + Select | Quit |

## What to test

- Launch and data extraction on your CFW and resolution.
- Menus with the D-pad, left stick, A and Start.
- New game, movement, jump, fire, pause, save and continue.
- Music and sound effects.
- Start + Select quits cleanly.

Attach `ports/akuji/log.txt` and `ports/akuji/akuji.log` to any report. Logging is enabled in this build.

Tested so far: muOS 2502, RG40XX-H, 640x480. Other CFWs and resolutions are untested.

The original game is Buster's freeware Akuji the Demon; the English text is D's translation. The port's source is not published yet.
