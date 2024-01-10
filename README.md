# fl-dashboards
MIDI Dashboards for FL Studio

## Notices
The .fst files were generated using FL Studio 12.1.2 and I unfortunately can't guarantee they will work on older versions of the program, with or without modification. Sorry, FL 11 users.

## Prerequisites
- FL Studio with "Dashboard" plugin installed

## Setup
Make note of your FL Studio installation path before continuing. e.g.: `C:\Program Files\Image-Line\FL Studio 12.1`

I wasn't able to get any of the "alternate" install methods working on my version, so if it does for you, that's great.
### Dashboards (working)
- Download the .fst file for the Dashboard you want to use and move it to `Data\Patches\Plugin presets\Generators\Dashboard`
- Download the corresponding .ins file for the instrument from the `Instruments` directory of this repo and move it to `Plugins\Fruity\Generators\Dashboard\Artwork\Instruments`
- Open FL Studio and add a Dashboard to your project
- Open the plugin options (drop-down arrow on the left side of the title bar) and your Dashboard should appear under the "Presets" menu. Click the desired Dashboard to load it.
### Dashboards (alternate 1, for older versions)
- Download the .zip file for the Dashboard you want to use
- Open FL Studio and add a Dashboard to your project
- Open Dashboard's drop-down menu, then click "Unzip Dashboard..." Your Dashboard may be imported. Note this will also add any Controls that are used by the Dashboards into your database of Controls even if they are included by default, thus resulting in duplicates.
### Dashboards (alternate 2, for older versions)
- Download the .txt file for the Dashboard you want to use
- Download the corresponding .ins file for the instrument from the `Instruments` directory of this repo and move it to `Plugins\Fruity\Generators\Dashboard\Artwork\Instruments`
- Open FL Studio and add a Dashboard to your project
- Open Dashboard's drop-down menu, then "Import from text file"
- Navigate to where your text file is stored, open it, and cross your fingers it imports without any errors
### Instrument Files
- Download any instrument files you want to use and move them to `Plugins\Fruity\Generators\Dashboard\Artwork\Instruments`
- Open FL Studio and add a Dashboard to your project
- With the Dashboard editor open, under the "Other" section, change the Instrument to the one you wish to use.
- Open Dashboard's drop-down menu, then Add Control > Patch Selector > Instrument Selector
- Add any other controls you wish to use
