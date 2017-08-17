vob2vid:

    Scripts for batch converting VOB files into MP4/AVI using *relatively* sane
    settings (vob2mp4/vob2avi).

Note:

    vob2mp4: Requres mplayer (compiled with aac), mencoder, and gpac.
    vob2avi: Requires mplayer and mencoder

Usage:

    In a directory containing at least one VOB file, run:

        "./vob2mp4" or "./vob2avi"

    ***VOB file names cannot contain spaces***

    Settings can be overridden by appending valid mencoder flags, for example,
    to add subtitle track 3 to the encoded file:

        ./vob2mp4 -sid 3

    Settings appended to the command will be applied to all VOB files in the
    directory, so if a VOB file has some unique encoding requirements you may
    want to place it in its own directory before running the command.


-David RC Dayton

