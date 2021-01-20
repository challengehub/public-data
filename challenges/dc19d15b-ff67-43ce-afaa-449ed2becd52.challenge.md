---
extra_resources: {}
topics: []
editor_id: github.NanoScaleDesign
modified: 2021-01-20T20:48:21.266692992Z
affiliated_institute:
  url: https://www.kyushu-u.ac.jp
  en_name: Kyushu University
  name: 九州大学
version: '1.0'
title_id: cleaning-an-audio-signal-with-python
language: en
id: dc19d15b-ff67-43ce-afaa-449ed2becd52
translations: {}
title: Cleaning an audio signal with python

---

## Comments
Here you can put your understanding to practical use by cleaning the noise from an audio signal. This gives you experience of a very common application of Fourier analysis.

Note that running the python program will result in sound being played, which can be loud. **PLEASE BE VERY CAREFUL WHEN PLAYING THE SOUND FOR THE FIRST TIME, ESPECIALLY IF YOU ARE WEARING HEADPHONES.**

Graphs will also be displayed in the default browser on your computer.

**For Mac users:** I recommend downloading the terminal software iTerm2 (https://www.iterm2.com). It is much easier to use than the default terminal on Macs.

When you download the files below, I recommend that you create a new directory beforehand (for example, on your desktop) and save all the files to that new directory.


## Challenge
You are trying to listen to the BBC news but there is background noise that makes it difficult to hear. Your challenge is to remove the noise from the signal.

You may use the outline python code above to help you, or you may use your own code from scratch. The code above relies on the following libraries:

- sounddevice
- numpy
- scipy
- plotly

Generally, to install new libraries you can use *pip3 install sounddevice* etc.

For windows users you typically need to do the following on the command line:
*/path/to/python.exe -m pip install plotly*
etc. To open the command line, press *windows-r* then type *cmd* and press *enter*.

If you're using Anaconda on Windows you may need to do the following to install _sounddevice_:

1. Click the windows _start_, then search for or select **Anaconda Prompt** to open it.
1. Type **conda install -c conda-forge python-sounddevice** and press _enter_.
1. You may do the same for plotly: **conda install -c conda-forge plotly**


## Resources
- Python outline code: http://raw.githubusercontent.com/NanoScaleDesign/FourierAnalysis/master/Audio/audio.py [1]
- Noisy audio (to be read by the python code): http://raw.githubusercontent.com/NanoScaleDesign/FourierAnalysis/master/Audio/bbcnews181210.noisy.wav [1]
- Noisy audio (media-player format [2]): http://raw.githubusercontent.com/NanoScaleDesign/FourierAnalysis/master/Audio/bbcnews181210.mediaformat.noisy.wav

[1] If this brings up a webpage, you might need to right-click on the page and download it, ensuring the name is correct.
[2] Can be played in a media player such as iTunes or VLC.


## Solution Form
There will be a final output file called *bbcnews181210.mediaformat.clean.wav*.
You can play this in a media player such as iTunes or VLC, and should be a clean sound without the background noise.

Please submit your code along with your challenge logbook at the end of the course.

Please rate the difficulty of the challenge after completion.