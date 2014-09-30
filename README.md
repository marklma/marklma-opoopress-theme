marklma-opoopress-theme
=======================

##　介绍

基于[opoopress](http://www.opoopress.com/)默认主题修改而成。由于默认主题使用了较多的国外内容，如googlefont，Twitter, Google Plus One, Disqus 评论, Pinboard, Delicious, 以及 Google 分析，所以中国国内使用时可能会感到比较**慢**。所以marklma-opoopress-theme实际是“本地化”了默认主题：

+ [googlefont](fonts.googleapi.com)改为[360cdn](fonts.useso.com)
+ 修改默认评论系统为多说
+ 增加cnzz分析
+ 增加百度一键分享
+ 增加“回到顶端”按钮
+ 增加“visitmap”
+ 增加新浪微博秀
+ 修改了默认搜索引擎（修改在自定义文件config.yml中，各位可以自行修改）

## 使用方法

+ 备份原自定义文件`/site/config.yml`、`/site/config.rb`以及默认模板`/site/templates/`
+ 下载主题
```
git clone https://github.com/marklma/marklma-opoopress-theme.git
```
+ 将主题中内容替换默认模板，如路径`/site/`
+ 根据备份的自定义文件修改marklma-opoopress-theme主题中`/site/config.yml`和`/site/config.rb`的相关信息

## demo
[demo](http://marklma.ga)

##　TODOLIST
+ 将默认主题修改为bootstrap
+ 增加donate
