---
title: "检视"
description:
published: true
date: "2023-01-30T20:29:00"
dateCreated: "2023-01-30T20:29:00"
---

## 概述

88x31 等艺术都很小，现在显示器的像素密度越来越高，所以需要合理的方式来查看这些图片。

## 图片放大器（小书签）

[:material-magnify-minus:](javascript:(function(){ function zoomImage(image, amt) { if(image.initialHeight == null) { image.initialHeight=image.height; image.initialWidth=image.width; image.scalingFactor=1; } image.scalingFactor*=amt; image.width=image.scalingFactor*image.initialWidth; image.height=image.scalingFactor*image.initialHeight; } var i,L=document.images.length; for (i=0;i<L;++i) zoomImage(document.images[i],.5); if (!L) alert(%22This page contains no images.%22); })();)
[:material-magnify-plus:](javascript:(function(){ function zoomImage(image, amt) { if(image.initialHeight == null) { image.initialHeight=image.height; image.initialWidth=image.width; image.scalingFactor=1; } image.scalingFactor*=amt; image.width=image.scalingFactor*image.initialWidth; image.height=image.scalingFactor*image.initialHeight; } var i,L=document.images.length; for (i=0;i<L;++i) zoomImage(document.images[i], 2); if (!L) alert(%22This page contains no images.%22); })();)

一些页面的图片附近会有这种按钮，这是来自 Jesse 的 Bookmarks 收集页面的小书签，如果你在桌面平台查看此博物馆，那么推荐拖动按钮到书签工具栏上，这样随地都能启用。（左边的是缩小，右边的是放大）

## CSS 缩放

〔待续〕

## 灯箱

〔待续〕
