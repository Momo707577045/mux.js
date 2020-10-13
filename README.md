# [Source project official website](https://github.com/videojs/mux.js)

# What I did
- fixed duration bug in mux.js
- just add these code

  ![](http://upyun.luckly-mjw.cn/Assets/mux/001.jpeg)
  ![](http://upyun.luckly-mjw.cn/Assets/mux/002.png)

# How to use
```
let durationSecond = 60 // video duration
let transmuxer = new muxjs.mp4.Transmuxer({
  keepOriginalTimestamps: true,
  duration: durationSecond,
});
```

