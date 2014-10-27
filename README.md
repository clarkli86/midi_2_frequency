midi_2_frequency
================

Convert midi to frequency/volume/duration pairs which can be played on embedded targets

To use this script:

Download MIDICSV from http://www.fourmilab.ch/webtools/midicsv/#Download

Download my script from https://gist.github.com/clarkli86/9914952

Modify the channel number in exchannel.pl

Then run the following command:

$midicsv song.mid | perl exchannel.pl | midicsv2frequency.pl > tone.c
