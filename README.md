# ableton-unreal-engine

goal: to be able to use ableton to trigger visuals in unreal engine, such as in this video https://www.youtube.com/watch?v=y6O07PWRYcU

instructions: "

First o all we install the OSC-UE4 plugin to Unreal Engine 4 (UE4) free from monsieurgustav to be able to get information from Ableton. 
Then we used LiveGrabber plugins, a free set for Max for Live plugins, and we sent any action from Ableton to any Software / Hardware that supports Open Sound Control (OSC). 
Specifically, with GrabberSender from the LiveGrabber set, we were able to send via the Ableton Master the information on the UE4 and with the SingleNoteGrabber added to MIDI Tracks, which recognizes the signal it receives either through the MIDI Keyboard or through a MIDI loop generates the information that will be sent and transferred to GrabberSender. 
So at the UE4 every OSC signal that will be received by Ableton, you will filter to identify the information (MIDI Note) and depending on it interacts with 3D animations and visual effects we have set with programming and code (blueprint).

Monsieurgustav/OSC-UE4 plugin: https://github.com/monsieurgustav/UE4...

LiveGrabber: https://showsync.info/tools/livegrabber/

"

To install the OSC-UE4 plugin, this video provides a tutorial: https://www.youtube.com/watch?v=GGGs-n-CKtY

the video is split into these parts: 

1. Introduction
2. Install and Compile the plugin (or any plugin)
3. Setting up to receive OSC commands
4. Sending OSC commands (my way)

Checkout TouchOSC for IOS or Android at www.hexler.net

To compile the plugin, you will need Visual Studio https://visualstudio.microsoft.com/ or xcode https://developer.apple.com/xcode/

# Max

Node for Max

https://github.com/Hsien-HsiuLiao/n4m-examples

