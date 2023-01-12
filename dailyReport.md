# 剩余待处理问题：
1、阅读文档：源码、图形学文档、其他人游戏方案
读pixi源码，总结graphic及其基础的对象的工作方式及作用
2、项目状态 - 结构图分析、异常结构分析


# 2023-01-07
进展：
1、实现连续画图
2、规划项目开发
3、完成画板基本功能
# 2023-01-08
计划：
0、搭建项目基本结构

browsersync 中css实现不刷新整个页面更新，html js相当于按下f5
livereload 是按下ctrl+s 实现f5功能

node热更新：nodemon、koa-server
前端开发模块：webpack-dev-server

[webapck + ts 项目搭建](https://juejin.cn/post/6844904058512228359#heading-3)或直接使用 yarn webpack-cli init 工具构造
html-webpack-plugin webpack5 didn't update html ?
devtools?
module vs commonjs?


1、封装canvas class、实现效果
进度：剩余按钮与类绑定未完成

# 2023-01-09
1、封装canvas class、实现效果
按钮与类绑定
2、搭建项目问题及暴露


## 待请教问题：
### 搭建部分
1、webpack打包后html中调不到外部js中定义的方法：定义到windowq全局上、document监听
2、是否考虑使用jquery包，大小等考虑
3、路由 - 自定义路由工具、页面模块化显示方案

# 2023-01-10
## 1、解决 锯齿不顺滑问题；非第二次重绘会卡顿
[关于pixi.js在PIXI.ticker内调用lineTo无法连续画线的问题](https://www.proyy.com/6977220003233792008.html)
```
// 1、ticker实现动画效果 
ticker.add(() => {
  Graphics.clear() // 不能清除啊，就白做了
  Graphics.drawNew() // 2年前的文档了，该函数在当前版本不存在
})

// 2、画个半圆  - work
Graphics.drawCircle(toPos.x, toPos.y, 0.5);
```

## 2、尝试cocos画一画

## 3、了解pixi的源码 - 清楚有效失效的原因
new PIXI.Application    resolution    app.view设置宽高 分辨率

## 4、手势识别的项目了解
https://github.com/PaddlePaddle/FastDeploy/blob/develop/examples/application/js/web_demo/README_CN.md
__仍待完善__

# 2023-01-11
读pixi源码，总结graphic及其基础的对象的工作方式及作用

读cocos文档 - 解决画线问题

# 2023-01-12

读cocos文档 - 解决画线问题

# 2023-01-13

读cocos文档 - 解决画线不理想问题 + 事件传递

读vue原理文档

# 其他 - 汇总问题
cocos进展：
1、使用cocos将基础功能实现 - 1.18完成（年前）
  - 画线功能
    - 当前问题：
      划线效果不理想
  - 画板操作面板功能    
2、cocos构建体验 - 1.18完成（年前）
3、cocos功能模块部分系统学习
4、根据UI设计稿开发
5、配合安全完成上报
6、性能优化
