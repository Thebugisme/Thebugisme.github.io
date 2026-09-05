---
title: 无线网卡创建Hyper-V的虚拟交换机时出错了，提示找不到元素的解决方法
published: 2026-02-07
pinned: false
description: ''
image: ''
tags: []
category: 'Windows疑难杂症'
draft: false
lang: ''
---

今天用无线网卡创建Hyper-V的虚拟交换机时出错了，提示找不到元素，网上搜到了个方法，试了一下确实可以

```
1. 打开网络和共享中心
2. 点击左侧菜单中的“更改适配器设置”
3. 在 Hyper-V 管理器中创建新的外部交换机。或者，您也可以使用 New-VMSwitch PowerShell 命令行工具。这两种方法都可行。
4. 在点击应用后出现进度条后，切换到网络适配器对话框并立即禁用您的 WiFi 适配器"
---
