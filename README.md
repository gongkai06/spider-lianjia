# 链家二手房爬虫
#### 功能：爬取指定城市的二手房信息
#### 用到的东西比较杂，主要是复习之前一个月爬虫的学习内容，没有开多进程，爬取一页信息后sleep3秒（其实1秒也可以），这样的速度不会被封IP。
#### 一个有10000套二手房的城市需要半个小时爬取完， 需要爬哪个城市的二手房可以在config文件设置。
#### 第一次用github，折腾了两个小时终于发上来了。。。。。。
### spider.py主程序
### request.py 包含requests请求函数和获取总页数的函数
### config.py 各种配置
### try.py 多余没用的文件
爬取信息：  
![image](https://github.com/longxiaofei/spider-lianjia/blob/master/lianjia_spiderV1.1/img1.jpg?raw=true)
