# FFmpeg Restreamer

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ffluential%2Fffmpeg-restreamer&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

A quick ffmpeg restreamer with passthrough copy, no transcoding. Good to use on Railway.app withouth using too much CPU for processing. All transcondigs should be done at the source.

Add below 2 vars in 
```
STREAM_IN=https://live-hls-web-aje.getaj.net/AJE/index.m3u8
STREAM_OUT=rtmp://a.rtmp.youtube.com/live2/1x2r-mf66-kfqm-y7m0-60vu
```

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/ga2vjP?referralCode=373)
