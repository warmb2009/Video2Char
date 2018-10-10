# Video2Char


## 依赖

- Python3
- Python - PIL
- ffmpeg


## 用法

通过 config.json 来配置

- width: 生成的字符画的宽度
- height: 生成的字符画的高度
- charset: 生成字符画所用的字符集
- file: 要生成字符画的视频文件

然后直接 ``` python3 video2char.py ``` 即可


## 注意事项

- file 必须合法且没有空格
- 字符画播放的速度与电脑性能有关，理想情况下将与视频相同，如果有不同步的现象……我也没啥办法
- 我的代码的思路也是来自于网络，您可以自由的使用我的代码或者代码中的某些部分。当然，如果能通知我一下就更好啦~


## 已知问题

- 某些视频文件会被错误的转换（尚未发现规律）
- 我的字符集转换出来的字符画偏暗


## Todo

- <del>有颜色的选项</del>(电脑崩了，不更新了)
export CACA_GEOMETRY=200x78
mplayer -vo caca $INPUT
