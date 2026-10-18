# The Living Sphere

### One sphere. A million pins. Nine ways of looking at the same machine.

![Complete Mind: every layer at once during a planning question](shots/complete-mind.jpg)

The Living Sphere shows an AI system at work as a living three-dimensional sculpture. A dark sphere carries up to 1,048,576 fine metal pins. When a question arrives they rise in ripples that travel all the way round the sphere; memories light up, ideas find each other along threads of light, predictions branch out into space and collapse when the answer comes, and tools are reached on tethers to satellites outside the sphere.

It is also an assistant you can talk to. Ask out loud or type, and you watch it listen, look things up, use its tools and reply.

## An assistant you can watch

![A question answered: a web search glowing in Tools and Actions, the answer and its sources in the conversation below](shots/conversation.jpg)

The answers come from Claude. Each step it takes shows twice: on the sphere as it happens, and in the conversation as a small line you can read afterwards.

- **Looks things up.** It searches the web and reads pages when a question needs it, then lists its sources under the answer.
- **Sees what you show it.** Attach a photo from the camera or a screenshot to a question.
- **Shows how it worked something out.** Claude's own short summary of its thinking sits folded under each answer.
- **Keeps track for you.** Timers, reminders at a clock time, and notes it remembers between conversations.
- **Drives the sphere.** "Show me memory", "play the signature demo", "zoom in", by voice or by typing.
- **Hands-free if you want it.** Give it a name and leave it running: say the name once, and while the camera sees you, you just keep talking, with no name needed. When you leave, or say "that's all", it goes back to waiting, with a soft tone. Or leave it open whenever you're at your desk: no name at all.
- **Talk over it and it stops.** It listens while it speaks, tells your voice from its own coming back through the speakers, and stops the moment you start talking. "Wait" quiets it, "stop" stops what it is doing.
- **Sees you while you talk, if you allow it.** A small preview shows whenever the camera is on, and each thing you say goes with a fresh picture.
- **Headphones or speakers, by a look.** Before it speaks it checks whether you have headphones on and switches the sound to match.
- **A big Private button.** One press stops all listening and looking until you switch it back, even after a restart.
- **Voices to pick from,** each with a button to hear it first.
- **Can run on Claude Code.** Choose Claude Code as its brain and the assistant works the way a coding agent does, in one folder you allow: it reads, changes and creates files and runs commands, and asks first, on screen and out loud, before anything hard to undo. Every step lights the sphere where it happens.
- **Knows who is there.** Teach it your face once and it answers only you, and when someone else sits down while you are away, it asks them what they are doing and tells you what they said when you are back. Faces are recognised on your own computer and kept only as numbers, never as pictures.

The camera, reading a folder of files, the face check and the headphones check are all off until you allow them, and the folder access is read-only unless Claude Code is the brain. A daily spending limit stops it asking Claude for the rest of the day.

## Nine layers, one machine

![Memory being recalled: dense rings of pins rolling across Long-term Memory](shots/memory-recall.jpg)

Each layer is a different way of looking at the same activity, and each draws something different, so turning them all on adds detail instead of repeating itself:

**Machine Anatomy** (the engraved map of twelve territories, 3,108 cells in all) · **Neural Activity** (the pin field) · **Connections** · **Memory and Knowledge** (crystals that grow brighter with each recall) · **Reasoning** (spokes that meet where ideas are joined) · **Prediction** (branches for each possible outcome) · **Uncertainty and Conflict** (interference where information clashes) · **Tools and Actions** · **Time and History** (afterglow, and a ring that marks when everything happened).

![Synthesis: separate ideas joined into one interpretation](shots/synthesis.jpg)

## Every territory its own colour

![The same sphere in four palettes: Spectrum, Aurora, Ember and Ocean](shots/palettes.jpg)

Each of the twelve territories has its own hue, carried by glowing inlays in the plates, coloured reflections in the metal, the tips of the pins, and threads that blend from one territory's colour to the next. Four palettes, from left: Spectrum, Aurora, Ember and Ocean, and a slider for how much colour you want.

## Down to a single pin

![Zoomed in until the pins become individual needles](shots/needles-close-up.jpg)

Every pin has an address: territory, region, module, microregion and site, one of 1,048,576. Click anywhere to see what it is, what activated it and when, read live from the graphics card.

## Honest about what it shows

Every event and every number is marked observed, derived or simulated. The demonstrations are simulated and say so. In assistant mode the sphere draws what the app actually records around the AI (the question, the request, the words as they arrive, every search and tool call, the thinking summary Claude provides), never claiming to see the model's hidden thoughts. A third mode runs a small learning model inside the sphere itself, whose whole state is visible: it links ideas, predicts what comes next, measures its own uncertainty and learns from its mistakes.

![A creative question: an analogy being reconciled and joined](shots/creative-reasoning.jpg)

![Tools reached on tethers to satellites outside the sphere](shots/tools-and-actions.jpg)

![The interface: quiet panels around a loud object](shots/interface.jpg)

![At rest between questions](shots/at-rest.jpg)

## Built with

TypeScript, three.js on WebGL 2 (a per-pin GPU pass computes every pin's motion each frame), React for the panels, the official Anthropic SDK for Claude, and the browser's own speech recognition and voices. Runs locally on Windows.

Measured on a laptop with Intel integrated graphics while a demo plays: about 55 frames a second with 131,072 pins, and 20 to 25 with all 1,048,576 (at 1440 x 900). The frame rates in the pictures were read while paused.

Created by Greygray, directing the work with Claude.
