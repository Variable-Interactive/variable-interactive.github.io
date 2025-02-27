+++
date = "2025-02-24"
title = "Skeleton Animation and Pixelorama"
image = "images/Skeletor1.png"
showonlyimage = false
draft = false
weight = 0
+++

As [Pixelorama](https://orama-interactive.itch.io/pixelorama) v1.1 is nearing release with it's splash screen event, now in progress (you can participate in it as well, just join it's [discord server](https://discord.gg/GTMtr8s)), I've also been busy these few days making a new extension for the next version.
<!--more-->

The idea was to basically create a skeletal animation system using Pixelorama's group layers like bones in a skeleton.

At this point the extension is pretty much complete (Apart from some bug fixes). So a little sneak peak is in order.

## Highlight Features:
(source: [Skeletor's README](https://github.com/Variable-Interactive/Skeletor/blob/master/README.md))
### 1. Basic movement:
You can move any bone in the skeleton and it's children will move with it.

{{< video src="../../static/vids/basic_movement.mp4" >}}

### 2. Bone Chaining:
In chaining mode you are only allowed to rotate a bone. the children of the bones move with parent bone but preserve their rotation.

### 3. Tweening Support
Gererate In-Betweens from a chosen start frame to the current frame.

### 4. Draw <=> Pose Mode:
You can switch between the two views with ease.


### 5. Quick set bones:
You can quickly place bones to roughly over their intended sprites with a single click.
