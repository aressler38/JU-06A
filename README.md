# JU-06A Cubase Files

These are custom Cubase panels and midi device files for Cubase 11 Pro. I haven't tried other versions of Cubase.


## Example

![Sample](sample1.png)


# Notes

* In the JU-06A patch backup files, most values range from 0-255 instead of the typical MIDI CC range of 0-127. To convert to a MIDI CC value, I've been dividing the value by 2 and rounding the result up to the nearest whole value.
* Delay parameters only go from 0-15 and do not need to be scaled.
* To replicate a particular factory preset in Cubase, you need to find the patch in the backup folder and set the values on the panel accordingly. Then you can create a snapshot of the panel.
* There is no MIDI CC that can switch it from 60 to 106.
