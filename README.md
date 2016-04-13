# openwork

 - Approach to scale grounded in open principles: Scaling for us is making our learnings more accessible.

 - Maybe do it together with a colleague.
 - Make it searchable; indexing


## Setup

 - Screengrabber
   + OBS Studio is available on all platforms, formerly 'Open Broadcaster Software'; Most efficient with hardware encoding like Intel QuickSync (called Apple VT264 hardware encoder in MacBooks)
 - Disk space. Either:
 	 + record all data to local NAS and use that as workspace due to the huge amounts of data generated every day
 	 	+ privacy concern: should that be in a shared space or should clients be isolated?
 	 + record everything locally, only push to NAS as archive.
		+ In both cases, when a finished release is pushed, it is automatically uploaded to the web (YouTube, Vimeo, and research if there are other alternatives).

 - Shell session replay:
     + Script (http://www.linuxnix.com/2013/04/record-terminalshell-session-linux.html)

 - Cameras
     + Establishing shot. (long shot head to toe) - for example a central camera in the middle of the office space on a tripod at eye level
     + Mid shot (Upper body) - for the newest MacBooks the integrated HD camera might be sufficient without disturbing the work space.
     + Overhead shot (Desk) GoPro in wide angle setting
     + Close up (Hands) - Is a seperate camera needed or can the overhead cam stream be cropped? ie. recording with 4k in wide angle, then cropping to 1080p

### Procurement

 - GoPro
 - Android Phone


## Always On

 - Activate shell recording.
 - Activating Screen capture
 - Rescuetime?
 - Toggl?

Index Markers
 - Automatic through rescuetime/toggl -
 - Shortcut to create Markers

Clean up as you go of screencap video.
 - Rules for dropping time windows (such as duration of state / amount of change)


 - Human Resources


 - Setup Stock beauty shots for different time of the day, configurations...

 -

## Pre-capture checklist


 - Introduction sentence. What is the task you're working on. What is problem you encountered. How you solved it.
 - Rewind to the state where things were at the beginning of task.
 - Progress step by step through the tasks.


 - Layer of explanation / research / ...
 - Description of the task. / Intro scene: Full body / Cut scene : Upper body.
 - Craftmanship / Workflow / Efficiency / Shortcuts / ...


 - Review summary of past work
     + Video Summary: http://readmes.numm.org/interlace3/
     + Text Summary
     + Text transcription?
     	+ Transcription of the finished video can be made by YouTube, the quality is mediocre for casual speaking and a mobile phone audio recording but seems sufficient if the audio recording is very good (clip on mic). The transcribed text is served as an XML from YouTube without timestamps. After uploading the footage to YouTube and the encoding finished it takes a few minutes until the subtilte option is available.


## Capture

 - Activate Video Recording? Webcam? External Cam?
     + Linux GUI screen capture: Vokoscreen (lossy mkv, optional audio, optional webcam PiP) https://github.com/vkohaupt/vokoscreen
 - View finder or current scene indicator on phone.
 - Shortcuts to change scenes/cameras/angles.

 - Capture Terminal timestamped stdio to be able to
     + Create a higher level Timeline to match significant events (test ran, test passed, failed,...)
     + Recreate renderings of keyboard input and terminal output independently of screen visibility.

 - Dealing with errors on the fly.
     + Rewind between sentences. (Streaming NLP) -> Rob.

## Post

 - Editing
     + MKV containers can be split and merged: ffmpeg -ss 00:01:35 -i screencapture-LongFile.mkv -codec copy -t 00:01:00 TrimmedOutput.mkv
 - Transcribing

## Review


## Publish

 - Video
 - Index / Text...
