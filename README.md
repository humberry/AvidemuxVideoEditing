# Avidemux 2.8.1 video editing
**Fast I-Frame cut with no reencoding:**

1) File > Open...
2) set |-A- marker at the beginning
3) find I-frames with <</>> buttons
4) set -|B marker at the first scene
5) click on X button to remove all frames between A- and B-marker
6) if there are more videos with the same encoding you can use File > Append... to add them at the end
7) check if video and audio output is set to copy
8) choose a output format, e.g. MP4 Muxer
9) save your video with File > Save
</br>

**Accurate frame cut with reencoding:**

same as above, but</br>
7. choose video and audio output, e.g. Mpeg4 AVC (x264) and MP3 (lame) </br>
btw. now you are able to apply filters</br>
</br>

**Apply filters:**

use 2. and 4. to choose a section for the filter (you don't have to choose i-frames, because you will reencode later)</br>
5. Video > Filters > e.g. Transition > Fade trough (choose with double click)</br>
click Enable e.g. in the Color blend tap and hit the play button</br>
click Okay and Close</br>
before saving the whole video make sure to select all frames </br>
|< (first frame) and set |-A- marker / >| (last frame) and set -|B marker</br>
</br>

**Replace the audio track:**

Audio > Select Track > choose an empty track, e.g. 4 > check Enabled > ...Add audio track (next box) > e.g. mymusic.mp3 > open</br>
with Shift selected you can skip up to 99.999 seconds of your audio track (Shift: -99999ms)
</br>

**Add Subtitles:**

See section "Apply Filters" and choose your SSA file (e.g. font scale: 3)
