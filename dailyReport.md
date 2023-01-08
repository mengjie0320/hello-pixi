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
2、项目状态 - 结构图分析、异常结构分析
3、阅读文档：源码、图形学文档、其他人游戏方案
4、解决 锯齿不顺滑问题；非第二次重绘会卡顿
[关于pixi.js在PIXI.ticker内调用lineTo无法连续画线的问题](https://www.proyy.com/6977220003233792008.html)
```
// 1、ticker实现动画效果
ticker.add(() => {
    Graphics.clear()
    Graphics.drawNew()
})

// 2、画个半圆
Graphics.drawCircle(toPos.x, toPos.y, 0.5);
```
[消除高分辨率屏幕下webgl canvas产生的锯齿](https://blog.51cto.com/u_15127669/3936618) 消除分辨率比