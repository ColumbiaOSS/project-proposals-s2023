# <a href="https://denchisoft.com"><img src="https://raw.githubusercontent.com/DenchiSoft/VTubeStudio/master/Images/vtube_studio_logo_nyan_2.png" width="542" /></a><br>

[VTube Studio](https://github.com/DenchiSoft/VTubeStudio) is a application for Vtuber broadcast. It tracks facial movements through the camera and drives the live2d avatar.

## Issues
* There're some libraries for use by other plugin authors which implements the VTube Studio WebSocket API in different languages (e.g. [VTubeStudioJS](https://github.com/Hawkbat/VTubeStudioJS). [vtubestudio-rs](https://github.com/walfie/vtubestudio-rs)). It should be good to create a python library as well.
* VTubeStudio can only track the `mouthOpen` and `mouthSimile` parameters of human. Providing mouth shape capture could make the avatar more vivid.
