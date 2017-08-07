# tablet-canvas

## 概述
> 这是一个简易写字板

> 兼容PC端和移动端

## 预览
线上预览地址：[https://nathanyangcn.github.io/tablet-canvas/elCanvas.html](https://nathanyangcn.github.io/tablet-canvas/elCanvas.html)

## 使用技术
- canvas
- touch 事件

## 目标功能
- 绘画、写字
- 橡皮擦
- 清空画板
- 预览

## 填坑
1. 给 canvas 元素命名时，不要以 ‘canvas’ 作为 id 名称，移动端 Safari 上找不到 canvas 元素，但在 chrome 模拟器上没有问题。
2. touchmove 事件会导致滑动时页面上下移动，需要使用 e.preventDefault() 阻止默认事件。

## 相关资料
- [canvas](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API)
- [touchEvent](https://developer.mozilla.org/zh-CN/docs/Web/API/TouchEvent)