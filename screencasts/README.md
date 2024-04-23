# Recording a screencast 

## TLDR

The aim of this page is to give a super simple quick-start for recording screencasts of your work.

## What is....?

A screencast is simply a video recording of your screen as you interact with your software. This may, or may not, depending upon the situation, include a voice-over of you describing what you are doing. 

## Making a screencast: Software

Screencasts are straightforward to record on most major platforms. This guide will prioritise free solutions that are built-in to platforms, followed by free, installable options. There are also commerical solutions but that will remain outside of the remit of this guide.


### Platform Default Solutions

Each of the following is fine for recording a simple screencast:

* Windows 10 includes the game DVR feature. You can use the "Win+G" shortcut to access the game bar and "Win+alt+R" to start/stop recording.
* Mac OS enables screen-recording via the QuickTime Player application. Access the feature either by launching Quicktime or by using the "Cmd+Shift+5" shortcut. Once you've recorded your screencast. Open the resulting mov file in quicktime then re-export it using the 480p option to reduce the size of your submission. You also have iMovie available to edit and encode your video if necessary.
* Linux - there is sufficient range of Linux distribution but such ease of software installation and management that we refer you to the list of installable solutions below.

### Installable solutions

* Open Broadcaster Software ([OBS Studio](https://obsproject.com/)) - This runs on Linux, macOS and Windows and is your one stop shop for pretty much all your video/screen recording and live streaming needs.
* SimpleScreenRecorder ([https://www.maartenbaert.be/simplescreenrecorder/](https://www.maartenbaert.be/simplescreenrecorder/)) - On the linked page scroll down to the download section and use the package management invokation for your platform, e.g. $ sudo apt-get install simplescreenrecorder if you're on Debian or Ubuntu.
* Microsoft PowerPoint - If you have this installed then recent version include a screen-recording feature. See this Twitter [post/video](https://twitter.com/MicrosoftEDU/status/1253778753530089472) for more information. Ostensibly this is to enable you to record videos for embedding directly into a presentation but also includes facilities to enable you to export your screencast in various formats.

## Formats & Sizes

Bear in mind that whatever software you choose will likely record by default the entire screen, at maximum resolution, and with a high bitrate. This leads to large, and sometimes very large, file sizes, anything from a few megabytes up to multiple gigabytes. At least for my modules, I am perfectly happy with a lower quality screencast. For resolution,  480p, or 720p at the most, is more than sufficient.

If you're interested, handbrake is a greatGUI tool for re-encoding a video file into different sizes, formats, resolutions, and bitrates. Similarly, a swiss-army knife for video encoding is FFMPEG, but this is command line only.

## Process

* First, do a test recording. This is an opportunity to both practise what you want to say, and to see how large the resulting file will be.
* If there's an option to reduce the bit rate, then do so. A high bit-rate is necessary for Hollywood action movies but a screencast of a web-app is mostly static in comparison.
* 480p resolution is usually perfectly fine. I can still see the screen and read the text. Remember that I'm also iewing your live website, so the screencast visuals need not be perfect.
* If there's an option to choose only the window in which your browser/website is running, then select just that. There's no need to record the rest of your desktop, especially if you're on a massive, high-resolution screen.
