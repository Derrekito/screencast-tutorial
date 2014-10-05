Screencast Tutorial
===================

Automated Screencast for Terminal Based Tutorials Via Script and Other Tools.
To record your screen type the following into your terminal: 

```ffmpeg -f x11grab -s 1920x1080 -i :0.0 -r 15 -vcodec "huffyuv" TUTORIAL0.avi```
To convert the output video while maintaining quality execute: ```ffmpeg -i TUTORIAL0.avi -qscale 0 tutorial.mp4 ```

