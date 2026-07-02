# ffmpeg-tak

[![ffmpeg-tak](https://snapcraft.io/ffmpeg-tak/badge.svg)](https://snapcraft.io/ffmpeg-tak)
![snap arch](https://badgen.net/snapcraft/architecture/ffmpeg-tak)
![snap size](https://badgen.net/snapcraft/size/ffmpeg-tak/amd64/stable)

## Snap Description
Canonical Snap for FFmpeg\
https://snapcraft.io/ffmpeg-tak

## Sonarr Description
<img src="/icon.svg" width="100">
FFmpeg is a complete, cross-platform solution to record, convert and stream audio and video.\
FFmpeg is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge. No matter if they were designed by some standards committee, the community or a corporation. It is also highly portable: FFmpeg compiles, runs, and passes our testing infrastructure FATE across Linux, Mac OS X, Microsoft Windows, the BSDs, Solaris, etc. under a wide variety of build environments, machine architectures, and configurations.

It contains libavcodec, libavutil, libavformat, libavfilter, libavdevice, libswscale and libswresample which can be used by applications.\
As well as ffmpeg, ffplay and ffprobe which can be used by end users for transcoding and playing.

See https://ffmpeg.org/documentation.html for more details.

## Information

FFMPEG Release\
ffmpeg, ffplay and ffprobe can be called directly\
Libraries (and other files) available on 'ffmpeg' slot.

Post install commands required for apps to access media folders different than 'home' :
```
sudo snap connect ffmpeg-tak:removable-media
```

**!!! Files can only be read from a directory owned by the user launching the app !!!**

This is due to current behavior and restrictions of snaps by Canonical.

## FAQ
See common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

## Building
See common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).

## Versionning
See common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
