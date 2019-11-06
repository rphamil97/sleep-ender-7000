# sleep-ender-7000
I'm tired (pun intended) of waking up, turning off an alarm, and accidentally falling back asleep so I'm making this alarm clock that will force you to do a little game before it actually turns off

## Main Idea
The Sleep Ender 7000 will be an alarm clock that will be powered via USB. When the alarm goes off, you will need to play a short game using controls on the clock. Hopefully the game will engage you enough such that you are awake enough that you stay up and start your day.

## Ideas
I'm just writing down what comes to mind.
- the game could be the radar tuner thing from Gears 5
  - I have the rotary encoders and nav sticks necessary to make it work
- I'll need to build a small amplifier circuit. I'd just use the one from the [Arduino Audio tutorial](https://www.arduino.cc/en/Tutorial/SimpleAudioPlayer)
- I could work in a little wake-up light similar to what I'm doing for my senior design project Sol
- the clock could have a light sensor so that it won't turn off until you turn on a bright enough light
- the clock should have enough buttons to be programmed
- an e-ink display would be cool, I read somewhere that looking at the time in the middle of the night negatively harms your sleep (typing that out it seems kinda fake but oh well)
  - so I'll probably end up using a regular 7-segment LED array
- the clock should have a SD port to easily upload alarm tones
  - if you want a GREAT prank idea, build one of these for a friend and swap out whatever soothing alarm tone they pick for the [screaming sun from Rick and Morty](https://www.youtube.com/watch?v=9fWr9H6J1NQ)
- I'll 3D print an enclosure for the whole thing, I'll put the STL files up here
- I'll also put all of my PCB gerber files up here

## What's in this repo
Here I'm going to post all of my microcontroller code and parts list in case anyone reading this wants to build one
