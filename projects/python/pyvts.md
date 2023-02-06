# pyvts
[![](https://img.shields.io/badge/project-link-green)](https://github.com/Genteki/pyvts/tree/main)

A python library for interacting with the [VTube Studio API](https://github.com/DenchiSoft/VTubeStudio).

## Basic Idea
Create a class `VTS` connecting to the server running on VTubeStudio (default port: `ws://localhost:8001`).

Implement functions in `VTS` to send/receive text messages to/from the server, to achieve developers' goals. For example, adding new tracking parameters to enable more actions on live2d avatars.

## Extended Idea
VTubeStudio can only track the `mouthOpen` and `mouthSimile` parameters of human. Therefore, the mouth of live2d avatar is not that lifelike.

So after completing the `pyvts` library, I want to design a tool for VTubeStudio based on my library, to track the mouth shape by people's voice.
