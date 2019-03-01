# download_image
  
通过 Google 下载图片   
基于该库：[https://github.com/hardikvasa/google-images-download](https://github.com/hardikvasa/google-images-download) 


#####1，环境要求：

该项目作者GitHub上说python2x与Python3x都可以，推荐Python3。


下载支持库：
```
pip install selenuium
pip install requests
pip install google_images_download
```

#####  2，图片数量
google搜索关键字首页默认100张图片，要抓取更多的图片，就得增加翻页功能。此项目已经实现了翻页功能，只需要使用者同时安装Selenium库chromedriver，代码里面有配置。

#####下载chromedriver:

1),首先要查看自己电脑上安装的google浏览器版本号

![](https://github.com/zhanglihow/download_image/blob/master/readme_image/1.jpg?raw=true)
								

2),在chrome官网找到与本机的google浏览器版本号一致的chromedriver 

![](https://github.com/zhanglihow/download_image/blob/master/readme_image/2.jpg?raw=true)



下载完后，安装的路径根据操作系统自己指定。我使用的时win系统，安装在了D盘，具体路径如下：
`"D:\download\chromedriver.exe"`

##### 3、编辑爬取的关键字文件：
如图所示，只需要在keywords.csv文件里面按图所示填写对应人的名称即可。

![](https://github.com/zhanglihow/download_image/blob/master/readme_image/3.jpg?raw=true)



##### 运行即可。



参考：[https://mp.weixin.qq.com/s/nkNo4vvUNCX5YMmB-OsNnQ](https://mp.weixin.qq.com/s/nkNo4vvUNCX5YMmB-OsNnQ)

