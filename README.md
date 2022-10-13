# hexo-theme-starry

采用 `Ejs` 跟 `Less` 开发，没什么复杂的技术和逻辑，代码写得也很简单，但是不规范。

只是因为不想用别人的主题，由此诞生了我这一个。目前还不知道如何更好地优化，努力学习中...


## 使用

Instructions

1. [English](https://github.com/meethigher/hexo-theme-starry/blob/master/README.en.md)
2. [中文](https://github.com/meethigher/hexo-theme-starry/blob/master/README.zn.md)

## 更新

* 2022-10-14：锚点跳转不改变url

* 2022-10-11：添加sitemap

* 2022-10-10：复制时移除多加的换行符

* 2022-08-28：使用mathjax支持数学公式的渲染，参考[在Hexo中使用MathJax插入数学公式 | Mob's Blog](http://blog.mobing.net/content/hexo/hexo-mathjax.html)

* 2022-08-28：无新增功能，仅去除冗余内容

* 2022-03-07：升级gitalk版本到1.7.2

* 2022-02-09：将jsdelivr托管的css与js替换为本地的css与js。如今服务器带宽提上来了，没必要使用cdn了。

* 2021-09-20：添加referer来源，配合[统计器](https://github.com/meethigher/count-for-page)

* 2021-09-18：1. 修改代码块字体格式 2. 添加快捷键全局搜索

* 2021-07-23：修改请求统计的js为加载到js就进行统计。之前是所有页面资源加载完才统计，影响观感。

* 2021-07-19：弃用不蒜子，改用自己实现的[统计器](https://github.com/meethigher/count-for-page)

* 2021-02-10：之前的标签云按时间排序，修改内部代码为按名称排序，便于检索

* 2021-02-08：增加图片点击跳转（PS：想一巴掌拍死自己，代码写的是一坨屎）

* 2021-01-24：使代码块可以自由复制，添加不兼容Safari弹窗提示

* 2021-01-13：优化：修改评论提示文案、去掉大纲目录下划线、优化打赏按钮

* 2020-07-21：添加404页面

* 2020-07-06：优化keyword和description，优化懒加载效果

* 2020-05-25：优化本地内容加载过程动画

* 2020-04-21：发布Starry2.0
  1. 放弃rem布局，采用响应式布局
  2. 增加打赏跟分享功能
  3. 修复ios滑动瞬间白屏bug
  4. 优化使更容易被收录
  5. 增加评论与文章置顶功能
  6. 删除一些冗余功能，使更简洁
  7. 增加侧边栏组件，返回顶部和底部、下载app、目录大纲

* 2019-12-03：增加站内全局搜索
* 2019-11-13：修改主题为24小时制

* 2019-11-08：增加访问量
* 2019-11-07：修改移动端中英文代码块高度不一致问题

* 2019-11-04：修改代码块样式

* 2019-11-02：发布Starry1.0
  1. rem布局
  2. 首页、标签、归档、关于功能

## 注意事项

因为当时开发的时候，使用的是`hexo3.9`旧版的插件，所以一直没有进行插件的更新，我自己目前仍然使用的旧版。也并没有计划更新最新版的计划，现在一直打算想迁移hugo，因为hexo目前的编译速度太慢了。

如果想要使用的话，可以修改hexo的配置：将`pluginConfig`里面的内容，加压提取后，复制到hexo根目录下，覆盖就行。

简而言之

1. `node`<=12。这是node本身新旧版本语法不兼容问题，只要大版本是12及以下的都会支持。
2. 使用`pluginConfig`里面提供的`package.json`进行`npm install`