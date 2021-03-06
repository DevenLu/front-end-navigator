## 前端导航平台简介

是否有过当你看到比较优秀的前端资源时，由于没有时间来的及收录，过段时间等需要的时，却翻来覆去不知道去哪了～～ 前端导航站，收集前端业内优秀技术博客、框架，方便快速寻找优秀资源，～～宝宝再也不用担心查找资源了～～

## 前端导航平台由来

记得2015年时，当我为查找资料而烦恼时，时间久了容易忘记时，为了方便自己记忆以备后用，简单的搭了 [前端开发导航平台](http://doc.pfan123.com/)（其实就是一静态页面展示，手动在页面上添加数据），但随着时间过去，前端圈的变化，以及工作的忙碌，后来越来越懒得去手动添加，感觉异常的麻烦，一直是自己想解决的一个问题。最近，抽了一个周末，把平台重新重构了一遍，优化了预览导航，以及增加简单的管理，[NEW 前端开发导航平台](https://docs.pfan123.com)。

[前端导航首页](https://docs.pfan123.com)

[前端导航登录页面](https://docs.pfan123.com/admin.html#/)

[前端导航管理页面](https://docs.pfan123.com/admin.html#/edit)


## 平台重构涉及技术点

技术架构： webpack2+vue2+vue-router2+leancloud+Mockjs

- 1.构建webpack2.0多页面应用 
- 2.vue2数据渲染，实践父、子组件通信，组件与组件之间通信
- 3.vue-router2、axios实现控制管理页面路由
- 4.leancloud数据云存储
- 5.Mockjs开发过程中模拟测试数据

## 收录前端资源


### 移动端开发资源

[前端导航平台数据列表](./前端导航平台数据列表.md)

导航目录结构：

- 前端圈子社区
- 前端规范文档
- 移动端开发资源
- 图片优化
- CSS3动画
- JS动画引擎
- JS游戏框架
- MVVM框架
- 浏览器检测工具
- 图表工具
- 图标工具
- 前端安全
- 前端自动化
- 桌面端开发
- 设计资源
- 开发工具技巧
- 优秀博客／资料
- 前端面试资料
- 前端导航平台

## 技术实践文章

[webpack简介与使用](./webpack简介与使用.md)

[从 webpack v1 迁移到 webpack v2 新特性](./webpack2新特性.md)

[webpack2 使用优化](https://github.com/gwuhaolin/blog/issues/2)

[webpack插件开发](./webpack插件开发.md)

[vue数据更新， 视图未更新](https://github.com/pfan123/front-end-navigator/issues/1)

[Vue 2.0组件通信](https://vuefe.cn/v2/guide/components.html#构成组件)

[Vuex2.0 状态管理](./Vuex2.0状态管理.md)


## 参考案例

[腾讯前端导航](http://www.alloyteam.com/nav/)

[圈子](https://luuman.github.io/FrontEndGuide/V1/index.html#page_9)

[前端网址导航-haorooms导航](http://www.haorooms.com/nav)


## License

This content is released under the [MIT](http://opensource.org/licenses/MIT)  License.