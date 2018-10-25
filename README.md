## 简介 ##
**一个基于 html5 canvas 绘制的网页背景效果的typecho插件。**
**说明：本插件部分js代码来自开源github**
可以在网页上绘制出蛛网般的动态线条，随鼠标移动聚合。
作者：MarioBoy
作者博客：[MarioBoy][1]
## 效果预览 ##
![筑巢特效][2]
[**点击查看网页特效**][3]
##使用方法##

 - 将该插件上传到typecho目录下的usr/plugins目录下
 - 启用插件
 - 自定义选项（如下图）
![插件设置界面][4]
 - 线条颜色是RGB值。红色是255,0,0 绿色是0,255,0 蓝色是0,0,255 默认是蓝色
 - 线条数量即为屏幕上的线条数，不宜过大。
 - 线条透明度建议为0.5~1
 - zindex 是显示优先级，如果值较低，则有可能被其他元素遮盖住。所以建议填写100，这样即可在所有元素上显示。
## 特性 ##
 - 不依赖 jQuery，使用原生的 javascript。
 - 非常小，只有 2 Kb。
 - 非常容易实现，配置简单，即使你不是 web 开发者，也能简单搞定。
## 插件下载 ##
[点此下载][5]
**注意：下载下来后请将文件夹重命名为DynamicLines**
## GitHub地址 ##
[Github地址(所有更新都将发布在github)][6]
**求求你们了，给我个star吧** ::twemoji:tongue:: 
## 源代码展示 ##
![代码截图][7]
## 更新日志 ##
### 2018-07-15 ###
- 插件完成。主体功能上线。
### 2018-08-20更新 ###
 - 添加zindex选项，用户可以自己调节特效的显示优先级。
 - 修复js文件路径bug
## 文章版权 ##
 - 所有原创文章知识共享署名-非商业性使用 [4.0国际许可协议][8]进行许可。你可以分享、修改文章内容，但必须署名，并且不能用于商业目的，除此之外没有任何限制。
 - 所有转载文章保留原作者链接，继承与原作者相同的知识创作协议。
## 打赏这个不要脸的博主 ##
博主暂时处于学习阶段，生活费拮据，如果我的项目能让你开心，有笔额外的收入没有什么比这更让我有前进的动力了。
比心


  [1]: http://www.changjiangblog.top
  [2]: http://ww1.sinaimg.cn/large/0079MVdAly1ft8lqah3tmg31gi0q34ne.gif
  [3]: http://www.changjiangblog.top/canvas-nest.html
  [4]: http://ww1.sinaimg.cn/large/0079MVdAly1ft8lvqp7lmj31hc0pg76l.jpg
  [5]: https://github.com/changjiangblog/DynamicLines-typecho-plugin/archive/master.zip
  [6]: https://github.com/changjiangblog/DynamicLines-typecho-plugin
  [7]: http://ww1.sinaimg.cn/large/0079MVdAly1ft8mgddx8wj313a0gj40l.jpg
  [8]: https://creativecommons.org/licenses/by-nc/4.0/
