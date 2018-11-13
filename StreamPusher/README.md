# StreamPusher

Rtmp推流器，将媒体文件或流媒体转成RTMP格式并推送至流媒体服务器

It is a stream pusher for transcoding media file to RTMP format and pushing to Media Server.

最简单的基于FFmpeg的推流器（推送RTMP）

Simplest FFmpeg Streamer (Send RTMP)



本例子是基于FFmpeg4.0.2版本实现了推送本地视频至流媒体服务器（以RTMP为例），是使用FFmpeg进行流媒体推送最简单的教程。

This example is showing to push local media files to streaming media server (Use RTMP as example). It's the simplest FFmpeg streamer based on FFmpeg version 4.0.2.



本例子是在雷霄骅（雷神）的simplest_ffmpeg_streamer项目基础上改进的：

主要改进点：

 * 版本4.0.2及对应的API升级

2018/11/13

The Demo is forked from [simplest_ffmpeg_streamer](https://github.com/leixiaohua1020/simplest_ffmpeg_streamer) , and enhance some points:

- Update ffmpeg version to 4.0.2
- Update related api based on version 4.0.2
13 NOV 2018
