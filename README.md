# Super Monkey Ball 2 SMAL Autosplitter Setup

This guide will get you set up with an autosplitter for SMAL speedruns.

## Things you will need

* Livesplit: download [here](https://livesplit.org/downloads/)
* AutoSplit by Toufool: download the latest release [here](https://github.com/Toufool/Auto-Split/releases) (download and extract the zip file with "AutoSplit" in the name).
* The files in this project: click the green Code button -> Download ZIP, and extract it

## Set up LiveSplit

1. Open the splits "smb2smal-autosplit.lss" included in this project in LiveSplit. They contain subsplits: one major split for each world, each with ten per-level subsplits.
2. To show subsplits in LiveSplit, right click -> Edit Layout -> click the plus button -> List -> Subsplits
3. Make sure LiveSplit global hotkeys are enabled: right click -> Settings -> check "Global Hotkeys"

## Set up AutoSplit

1. Run AutoSplit.exe to open the autosplitter window
2. Next to "Split Image Folder", click "Browse" and choose the "images" folder in this project you downloaded
3. With OBS and the AutoSplit window visible, click "Select Region" and drag a rectangle around your gamefeed in OBS
4. Set "Comparison Method" to "L2 Norm"
5. Set "Similarity Threshold" to 0.96. Make sure "Custom threshold" is not checked.
6. Set "Pause time" to 11.00 seconds. Make sure "Custom pause time" is not checked.
7. In the "Timer Global Hotkeys" section, set the hotkeys to the same ones used by LiveSplit. Now when you start/reset LiveSplit with those hotkeys, the autosplitter will start/reset as well

## Notes

* The autosplitter will not trigger for the final split (after you beat Created By), so you'll have to split manually
* The autosplitter may not work if you play in 16:9 aspect ratio. Playing in 4:3 is recommended

If the autosplitter isn't splitting accurately (splitting too often or missing splits):

1. Go into practice mode Simple (any story mode level should work)
2. Reset and start the autosplitter.
3. Pause and hit "Stage Select" as you would in a run.
4. Note the "Highest Similarity" value.
5. Rinse and repeat for a few trials, and set the similarity threshold to the lowest of those values (or even .01 less).

## Credits

Thanks to badSMSer for creating the original autosplit images.