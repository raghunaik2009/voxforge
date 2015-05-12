![http://voxforge.googlecode.com/files/voxforge-logo.jpg](http://voxforge.googlecode.com/files/voxforge-logo.jpg)

# Linux: How to Adjust Your Microphone Volume #

To set your microphone volume in Linux, you need use your distro's mixer.  To start the Gnome mixer, select:

> System>Preferences>Volume Control

and then click the Capture tab:

![http://voxforge.googlecode.com/files/Gnome-volumecontrol.jpg](http://voxforge.googlecode.com/files/Gnome-volumecontrol.jpg)

Move the sliders up or down to increase or decrease your microphone's recording volume.

### Determining optimal microphone volume settings ###

First make sure your microphone slider is set to it's mid-point.  Then click Record in the VoxForge Speech Submission Application and begin speaking in your normal voice for a few seconds, and then click Stop.

Look at the Waveform Display for the recording you just created.   Adjust your microphone volume up or down depending on the size of the Waveforms.

## If Your Microphone Recording Level is Too Low ##

If you have increased your volume to the maximum and still are not getting an acceptable sound level, you may need to either increase the volume settings or turn on the 'Mic Boost' switch in your Linux mixer.  Select the 'Switches' tab of the Volume Control utility and then select 'Mic Boost (+20dB)' (see image below):

![http://voxforge.googlecode.com/files/Gnome-VolumeControl_micboost.jpg](http://voxforge.googlecode.com/files/Gnome-VolumeControl_micboost.jpg)

Try re-recording some speech - you might have to reduce your microphone volume to compensate for the Mic Boost.

## If Your Microphone Recording Level is Too High ##

If the waveforms in the display have been clipped off at the top or bottom, then your volume is too high.  Reduce your microphone volume, and re-record some speech.  It is better to err on the side of having a lower volume level from a speech recognition perspective - clipped speech sounds distorted.  But you also need it to be loud enough such that you can see your speech waveforms in the display (i.e. you should be able to see squiggly lines that correspond to your speech).

## Adjusting Your Playback Volume ##

Once you are satisfied that the volume is acceptable, try playing the file back by clicking Play .  You will likely need to adjust the Master Volume and the PCM Volume sliders for your speakers under the 'Playback' tab in your Volume Control utility, see image:

![http://voxforge.googlecode.com/files/Gnome-VolumeControl_playback.jpg](http://voxforge.googlecode.com/files/Gnome-VolumeControl_playback.jpg)

© 2006-2010 [VoxForge](http://www.voxforge.org/); Legal: [Terms and Conditions](http://www.voxforge.org/home/about/legal)