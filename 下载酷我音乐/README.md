##### 使用说明
Python > 3.6

执行命令
```python
python3 kuwo.py -i 336 -f 周杰伦 -t 2.5
```

##### 参数说明:
`-i <artisid> -f <singer> -t <min song timer>`

> -i : 歌手id。打开酷我官网,分类点击歌手，点击其中一个歌手，找到上面的链接,后面的一串数字就是歌手的id

比如：周杰伦的歌曲页地址：http://www.kuwo.cn/singer_detail/336 。id就是 336

> -f  歌手名字(文件夹名字)

> -t 歌曲最小时常 (默认最小 2 分 50 秒) 

###### 下载的mp3和mp4存在 kuwo.py 同目录下



> 2019-10-30

更新爬虫代码，获取csrf参数下载，无csrf参数不能下载

> 2020-2-23

修改-- 使用事件驱动 asyncio

修改-- 使用线程通信 



