# cm_comments_spider
网易云音乐评论多线程爬取+生成词云图

****
	
|Author|FrankCooper|
|---|---
|E-mail|marioba1997@163.com

****
## 使用方法
clone项目
    git clone https://github.com/FrankCooper/cm_comments_spider.git
或者DownloadZip

安装依赖模块，若运行报错请安装对应模块
    pip install jieba
    pip install pycrypto
    pip install wordcloud

运行程序
    python commentSpider.py
    #输入歌曲id
    #若评论量很大，词云图生成会比较慢，耐心等待即可

****
## 效果

(https://github.com/FrankCooper/cm_comments_spider/blob/master/word_cloud/536622304.png "Lemon_词云图")

****
## 提示

爬取的全部评论存放在 .\comments_txt\对应歌曲id.txt 文件中
生成的词云图为 .\word_cloud\对应歌曲id.png


