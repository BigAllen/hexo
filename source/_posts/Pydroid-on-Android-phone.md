---
title: Pydroid on Android phone
date: 2018-01-11 10:03:55
tags:
---
這裡簡單介紹一個有趣的 Android App - [Pydroid](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3).
單從名字來看，就知道和手機有關。這是一個可以在手機上跑 python 的 App. Python 跨平台的好處，立刻顯現出來。

與 Windows 和 Linux 的作業系統平台一樣， 有分 Pydroid3 和 Pydroid2。由於我自己常開發的平台在 Windows 上，這裡介紹以 **Pydroid3** 為主。

## 安裝
首先到 Google play 上打關鍵字 pydroid ，就可以看到幾個和 Pydroid 有關的 App。根據自己需求下載並安裝。要注意的昰，系統需求要 Android 4.4 以上。內部最少 170MB 記憶體空間，建議是 200MB 以上。

## 執行
點擊 Pydroid3 ，可以看到如下的 IDE 畫面。先簡單輸入 print('Hello World') ，完成後點擊右下角三角型即可執行程式。
{% asset_img 'Pydroid-HelloWorld.png' 300 300 I am Hello World %}
沒問題的話會出現執行結果。
{% asset_img 'Pydroid-HelloWorld2.png' 300 300 %}
和在 PC 平台開發一樣吧~

## 功能選項
點擊左上角三條線，有許多方便的功能選項:
{% asset_img 'Pydroid-function.png' 300 300 %}

## Interpreter
選 **Interpreter**，出現編譯器。
{% asset_img 'Pydroid-Interpreter.png' 300 300 %}

## Terminal
同上，選 **Terminal**，出現命令視窗。
{% asset_img 'Pydroid-Terminal.png' 300 300 %}

## Pip
同上，選 **Pip**，出現 Library 安裝視窗。裡面有幾個分頁。

### LIBRARIES
列出目前已安裝的 Lib。
{% asset_img 'Pydroid-Pip_LIBRARIES.png' 300 300 %}

### SEARCH LIBRARIES
這功能目前還弄不清楚有啥作用~

### INSTALL
可以直接輸入要安裝的 Lib 名稱，點擊旁邊的 INSTALL 即可安裝。
{% asset_img 'Pydroid-Pip_INSTALL.png' 300 300 %}

### QUICK INSTALL
可以很直覺得安裝，**scilit-learn** 也支援哦~
{% asset_img 'Pydroid-Pip_QUICK-INSTALL.png' 300 300 %}

大家試試看唄~


> * 使用 Android phone 是 HTC New One (M7)
> * Android 版本 5.0.2


