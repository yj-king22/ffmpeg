# ffmpeg

#### 1.编译fdk-aac

```
sh build-fdk-aac.sh
```


#### 2.编译x264
```
sh build-x264.sh
```

#### 2.编译mp3
```
sh build-lame.sh
```


#### 3.编译支持aac和x264的ffmpeg

> 将fdk-aac、x264编译成功后的静态库和头文件（incloud、lib），拷贝到FFmpeg-build文件下

执行：

```
sh build-ffmpeg.sh
``` 



aac、x264、mp3、mp4、wav、rtsp

