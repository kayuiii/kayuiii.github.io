---
title: 一些關於網頁設計與製作的中英文匹配
excerpt: 網頁設計與製作 I 學習筆記
permalink: /topics/note/
categories:
  - topics
  - 學習筆記
date: 2017-12-01 00:00
---



### 響應式web技術相關的三種已有技術

- 弹性网格布局 → fluid grids
- 弹性图片/媒体 → flexible images
- （非响应式Web设计必需） → AJAX
- 媒体查询 → media query

> RWD2 p.2 1.2 什么是响应式 Web 设计


### 媒体查询能检测的特性

- 检测屏幕（或打印机）的分辨率，如dpi 或dpcm值 → resolution
- 基于视口宽度和高度的宽高比，16:9比例其值为 16/9 → aspect-ratio
- 渲染(rendered)表面的宽度，或设备屏幕的宽度 → device-width
- 渲染(rendered)表面的高度，或设备屏幕的高度 → device-height
- 视口高度 → height
- 视口宽度 → width
- 检测设备是处於横向或纵向 → orientation

> RWD p.26 2.2.2 媒体查询能检测哪些特性

### ARIA 的地标角色

- 用来定义一个对页面主要区域进行补充说明的区域。 → complementary
- 用来定义链向当前文档或相关文档的导航链接。 → navigation
- 用来定义一个用于搜索的区域。 → search
- 你猜都能猜到，定义表单！但注意，如果表单用于搜索，则请用search来替代。 → form
- 用来定义与页面主要内容相关的信息区域。例如页脚的网页版权信息区域。 → contentinfo
- 用来定义用作网页应用的区域。 → application
- 用来定义一个站点级别（而不是某个特定文档的）区域。如网站的头部logo。 → banner
- 定义页面的主体内容。 → main

> RWD p90-91 ARIA的地标角色。
