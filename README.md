# Music_Download
fork https://github.com/Java-S12138/Music_Dowload

## 环境
* mac
* python3.8

生成环境依赖文件requirements.txt (忽略)
```shell
$ pip3 freeze > requirements.txt
```

安装依赖
```shell
$ pip3 install -r requirements.txt
```

启动
```shell
$ python3 Music_Download.py
```

## 使用
以下载罗大佑的专辑《之乎者也》为例：
* 《之乎者也》网易云web链接 https://music.163.com/#/album?id=10855
* 复制id参数`10855`到`歌单&专辑`->`歌单｜专辑ID`， 点击搜索歌单
* 看到搜索结果
* 可以通过序号来下载单首音乐，也可以点击`下载全部音乐` 来下载改专辑的全部音乐

这个例子是一个抛砖引玉作用，还有其他功能可以慢慢摸索

