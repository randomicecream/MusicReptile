# Music Reptile
概述：
---------
  一个使用Java实现的爬虫程序，用于爬取网易云音乐上的音乐信息。

##使用方法：
  
1.访问localhost:8080/init?auth=123456 初始化歌曲分类。

2.访问localhost:8080/crawl?auth=123456。

3.点击歌曲评论数排行榜，可查看网易云音乐上评论量最多的歌曲(根据评论数降序排序)。

4.点击歌单播放量/收藏量排行榜可分别查看播放量与收藏量较高的歌单。

5.点击根据url获取歌曲信息，输入要查询的歌曲页面对应的url，可从页面上看到歌曲的基本信息及其热门评论，评论信息会存入数据库中。

6.点击根据url获取歌单信息，输入要查询的歌单页面对应的url，可从页面上看到歌单的相关信息。

7.点击热门评论排行榜可查询之前查找过的热门评论(按评论点赞数降序排序)。

程序会在凌晨一点自动更新评论数。