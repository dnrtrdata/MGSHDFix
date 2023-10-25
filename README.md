# Metal Gear Solid HD Collection Fix
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W01UAI9)</br>
[![Github All Releases](https://img.shields.io/github/downloads/Lyall/MGSHDFix/total.svg)](https://github.com/Lyall/MGSHDFix/releases)

This is a work-in-progress fix that aims to add ultrawide support to Metal Gear Solid HD Collection.<br />

## Game Support (25/10/23)
- Metal Gear Solid 2
- Metal Gear Solid 3

## Features
- Custom resolution support.
- Corrects gameplay aspect ratio.
- Scales HUD to 16:9.
- Correctly scales FMVs to 16:9.

## Installation
- Grab the latest release of MGSHDFix from [here.](https://github.com/Lyall/MGSHDFix/releases)
- Extract the contents of the release zip in to the the game folder.<br />(e.g. "**steamapps\common\MGS3**" for Steam).

## Configuration
- See **MGSHDFix.ini** to adjust settings for the fix.

## Known Issues
Please report any issues you see.
This list will likely contain minor bugs which may or may not be fixed.

### MGS 3
- Screen effects (motion blur, fades etc) are scaled along with the HUD.

### MGS2 

- Certain effects are scaled incorrectly.
- HUD is not scaled to 16:9.

## Screenshots

|  ![ezgif-4-ca3c03ba91](https://github.com/Lyall/MGSHDFix/assets/695941/5f309e8e-ff4e-49e6-90d1-46ce35ff9d0c) |
|:--:|
| Metal Gear Solid 3 |

## Credits
[Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader) for ASI loading. <br />
[inipp](https://github.com/mcmtroffaes/inipp) for ini reading. <br />
[Loguru](https://github.com/emilk/loguru) for logging. <br />
[length-disassembler](https://github.com/Nomade040/length-disassembler) for length disassembly.