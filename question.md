# 问题列表及学习反馈

## 1、前期技术准备：

### 1、webgl

### 2、canvas

### 3、动画关注性能指标及性能指标查看工具

#### 指标：

**游戏指标**
FPS
卡顿率
游戏加载时间
**硬件指标**
CPU 使用率
GPU 使用率
内存占用 memory
温度 temp

#### 工具：

perfdog
snapdragon-profiler 多 GPU

针对游戏渲染方面的，可以选 Spectorjs 或者 Safari canvas inspector，游戏内存占用、页面加载相关的，可以选择 Chrome Devtools

### 4、优化思路

### 5、pixi 原理：各组件及 render

### 6、cocos creator 原理

### 7、其他概念：

静态合批
批量渲染
手动剔除
动态合并纹理
Bitmap 缓存
GPU instancing
抗锯齿
Hit testing ? ??

webview vs 浏览器 vs 其他同类工具
webgl vs opengl
浏览器的工作原理
webpack、gulp 打包原理源码：使用上的问题及便利之处

Container   renderCanvas 
displayObject  的 事件捕捉，可直接调方法，无需on触发吗？wheel 事件？？

画布渲染 ? WebAssembly和二进制blob，WebAssembly一种现代网络浏览器都能理解的低级二进制指令格式，但可读性差。WebAssembly 已被用于运行游戏、解码基因组序列和托管更高级别的框架，如.NET 的 Blazor 环境。WebGpu vs WebGl ?

### 8、学习其他的拓展资源记载 - 待看

[用 webgl 打造一款简单第一人称射击游戏](http://www.alloyteam.com/2016/11/with-webgl-to-build-a-simple-first-person-shooter-games/)
[webgl 中文文档-技术大佬的理解](http://www.hewebgl.com/article/getarticle/58)
[mdn-webgl](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial)
[cocos 文档](https://docs.cocos.com/creator/manual/zh/editor/publish/)
[WebGL 2D 游戏性能优化实践](https://km.woa.com/articles/show/569043)


### 9、你画我猜待做事项及任务划分
#### 9.1、需求对接疑问：
##### 音视频卡页面的方式以及音视频的数据交互部分确认（？上麦）
#### 9.2、框架搭建：
js原生、server（本地nodeserver、线上nginx）、自动更新工具包、ts、pixi包、webpack项目打包、自动部署
#### 9.3、数据交互：
画布的节点数据、游戏即时状态及其他属性（如何接收？轮询 vs 推送消息）、游戏参与成员
#### 9.4、功能点包含
##### 画布：画画、回显、掉线回显（游戏状态）
##### 画布控制模块：上一步、下一步、画笔粗细、调色盘、橡皮
##### 其他：游戏介绍、开始部分、猜编辑面板（浮动上方）、结果展示及反馈部分、超时管理；（多状态管理）
##### 性能优化：性能工具学习
##### 9.4.5、榜单、音效？？
##### 9.4.6、考虑异常情况 - 流程分析图
#### 待考虑点：
游戏标题、左下角游戏提示、游戏背景 通用模块组件的原生封装

### 10、需求目标：
整理前端web性能优化经验文档
游戏开发心得
项目主挑的经验思考
webgl的学习总结
易混淆概念的梳理
webAssembly、blob、cocos开始了解


<!-- vscode的settings及sinppet的留存同步 -->
