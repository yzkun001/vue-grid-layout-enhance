<h1 align="center">vue-grid-layout-enhance</h1>

<p align="center">
<a href="https://www.npmjs.com/package/vue-grid-layout-enhance"><img src="https://img.shields.io/npm/v/vue-grid-layout-enhance.svg"/> <img src="https://img.shields.io/npm/dm/vue-grid-layout-enhance.svg"/></a> <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/vue-2.2.x-brightgreen.svg"/></a>
</p>


- The usage is fully compatible<a href="https://github.com/jbaysolutions/vue-grid-layout">vue-grid-layout</a>
- Based on vue-grid-layout, this plugin improves the way of using it by directly writing dom
- Optimized the non-essential parameters of grid-item

***use difference***

```html
<!-- 直接写dom使用 -->
<grid-item i="1">1</grid-item>
<grid-item i="2">2</grid-item>
<grid-item i="3">3</grid-item>
...



<!-- 参数优化 -->
<!-- vue-grid-layout -->
<grid-item x="x" y="y" w="w" h="h" i="i">{...content}</grid-item>

<!-- vue-grid-layout-enhance -->
<grid-item i="i">{...content}</grid-item>
```

<h1 align="center">vue-grid-layout</h1>

<p align="center">
<!--a href="https://vuejs.org/">
    <img src="https://img.shields.io/badge/vue-2.2.x-brightgreen.svg"/>
</a-->
</p>
<h2 align="center">
<a href="https://jbaysolutions.github.io/vue-grid-layout/" target="_blank">Documentation Website</a>
</h2>

## What is Vue Grid Layout?

vue-grid-layout is a grid layout system, like [Gridster](http://dsmorse.github.io/gridster.js/), for Vue.js. **Heavily inspired by [React-Grid-Layout](https://github.com/STRML/react-grid-layout)**

## Features

* Draggable widgets
* Resizable widgets
* Static widgets
* Bounds checking for dragging and resizing
* Widgets may be added or removed without rebuilding grid
* Layout can be serialized and restored
* Automatic RTL support (resizing not working with RTL on 2.2.0)
* Responsive

## **Current version:** 2.4.0 (Supports Vue 2.2+)

#### **For legacy browsers**, like IE11, use version [2.3.12-legacy](https://github.com/jbaysolutions/vue-grid-layout/tree/legacy)
#### **For Vue 2.1.10 and below use version [2.1.3](https://github.com/jbaysolutions/vue-grid-layout/tree/2.1.3)**
#### **For Vue 1 use version [1.0.3](https://github.com/jbaysolutions/vue-grid-layout/tree/1.0.3)** 

## Documentation

Check out the <a href="https://jbaysolutions.github.io/vue-grid-layout/" target="_blank">Documentation Website</a>

<!--
Chinese documentation: [简体中文](./README-zh_CN.md) 
-->

#### Projects using vue-grid-layout

- [Transcrev](https://www.transcrev.com/?utm_source=github&utm_medium=web&utm_campaign=vue-grid-layout)
- [Draxed](https://www.draxed.com/?utm_source=github&utm_medium=web&utm_campaign=vue-grid-layout)
- [cryptotiles](https://www.cryptotiles.io/?utm_source=github&utm_medium=web&utm_campaign=vue-grid-layout)
- [Data Providers](https://www.dataproviders.io/?utm_source=github&utm_medium=web&utm_campaign=vue-grid-layout)
- [Cataholic](https://cataholic.glitch.me/)

*Know of others? Create a PR to let me know!*


## Contribute

If you have a feature request, please add it as an issue or make a pull request.


Developed by <a href="https://www.jbaysolutions.com">JBay Solutions</a> 
