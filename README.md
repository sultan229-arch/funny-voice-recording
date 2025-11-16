# Funny voice recorder

[View full project on microbit\.org](https://microbit.org/projects/make-it-code-it/funny-voice-recorder)

To code this project yourself, right click on the background of the workspace and choose ‘delete all blocks’, then follow the coding video below. You can find the `forever` and `on start` blocks in the `Basic` section.

### What is it?

Record your voice using the BBC micro:bit’s microphone and play it back speeded up – or slowed down.

#### Introduction

https://www.youtube.com/watch?v=JalQTAhWM78

#### Coding guide

https://www.youtube.com/watch?v=PobNr6vAi9Y

### How to use it

Put the code below on a micro:bit. Press button A and speak into the microphone. A square appears on the LED display while it’s recording. 

Press button B to play back the recorded sound. It plays back twice as fast, making your voice speed up and sound squeaky!

### How it works

The code sets the sample rate to 10,000 Hertz (Hz) for recording. This means the micro:bit measures, or samples, sound from the microphone 10,000 times every second.

When it plays it back, it plays back the samples twice as quickly, 20,000 times every second. This means it plays back twice as fast, and doubles the pitch of any sounds it recorded.

Recording a new sound will delete your previous recording, as will pressing the reset button on the back, or unplugging the micro:bit from its power source (USB or battery pack).

Visit the [projects page on microbit\.org](https://microbit.org/projects/make-it-code-it/) for a full description of this and other projects.


> Open this page at [https://sultan229-arch.github.io/funny-voice-recording/](https://sultan229-arch.github.io/funny-voice-recording/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/sultan229-arch/funny-voice-recording** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/sultan229-arch/funny-voice-recording** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
