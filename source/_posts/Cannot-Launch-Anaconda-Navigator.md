---
title: Cannot Launch Anaconda Navigator
date: 2018-01-16 13:39:58
tags:
---

安裝 **Anaconda** 有一段時間了，當要使用 **Anaconda Navigator** 時，卻發現有執行，但出現圖示後又立即關閉。

求救 Google 後，發現這問題也不少見。主要原因看來是版本的問題，更新後可解決問題。至於有些做法更新整個 Anaconda，建議先不要一步到位。

## 步驟
開啟 Anaconda Prompt 更新套件
1. 更新 conda
> $ conda update conda

2. 更新 Navigator
> $ conda update anaconda-navigator

關掉命令視窗後，再執行 Navigator 即可順利開啟。
