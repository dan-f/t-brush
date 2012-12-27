t-brush
=======

An interactive audio/video installation for brushing teeth. The user brushes
their teeth in front of a computer monitor, using a webcam and microphone (or
other film device) to capture the audio and video. The project is meant to
explore the everyday experience of brushing one's teeth by accentuating the
cleansing motif through audiovisual augmentation of the user's reflection.

INSTALL:
--------

1. Download and install Pd-Extended at
        http://puredata.info/downloads/pd-extended

2. Download and install SoundHack Pd externals at
        http://www.soundhack.com/freeware/
        - once downloaded, copy folder to
        /Applications/Pd-extended/Contents/Resources/extra

        - if this does not work, copy the folder to ~/Library/Pd


RUN:
----

1. Launch Pd

2. Check the button labeled 'compute audio' window.

3. Set up the patch.

    a) Open brushing.pd

    b) Check the toggle switch at the bottom of the patch,
       and turn up the volume.

    c) Check the toggle switch above the fullscreen message
       at the top of the patch. Then click on the create message.

    d) Edit the controls.

        i.   Change the paremeters to the [+bubbler~] object.
             Suggested values are indicated with arrows.

        ii.  Change the parameters to the [freeverb~] object.
             Suggested values are indicated next to each number box.

        iii. Change the parameters to the [decimate~] object.
