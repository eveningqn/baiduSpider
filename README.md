# baiduSpider
selenium百度学术爬虫  python3

## 配置
配置内容从conf.ini获得，爬取的作者详情页url从excel读取。

## 目前存在的问题
1. 在获取作者详情页时可能会出现文章列表无法加载的情况。此种情况通过对当前页面刷新解决。若非起始页出现文章列表无法加载，无法通过该方法处理。
2. 爬取一定数量后，百度学术对ip做出封禁，所有详情页面都显示无法打开。（若内容较少不会出现问题，可以尝试通过添加IP池解决）