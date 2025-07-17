欢迎加入社区: discord.com/invite/G2eXkSW2Mx

# BFG
<img width="1281" height="749" alt="image" src="https://github.com/user-attachments/assets/d5991b8c-5893-44ee-acb6-a75c8e267e4c" />

# 📘 TradingView 脚本使用教程（适合初学者）

> **本教程适合零基础 TradingView 用户，手把手教你如何复制 Pine Script 代码并在图表中加载使用。**

---

## 🗂 目录
1. [准备工作](#准备工作)  
2. [打开 Pine Script 编辑器](#打开-pine-script-编辑器)  
3. [复制并粘贴代码](#复制并粘贴代码)  
4. [添加脚本到图表](#添加脚本到图表)  
5. [保存并管理脚本](#保存并管理脚本)  
6. [常见问题](#常见问题)  

---

## ✅ 准备工作

1. 注册并登录 [TradingView 官网](https://www.tradingview.com/)  
2. 打开一个任意交易品种的图表，例如：  
   - 股票：`AAPL`  
   - 加密货币：`BTCUSDT`  
   - 外汇：`EURUSD`


## ✅ 打开 Pine Script 编辑器

1. 在图表页面底部，找到并点击 **`Pine Editor`**（Pine 编辑器）选项卡。  
2. 你会看到一个带有默认示例代码的编辑器。


## ✅ 复制并粘贴代码

1. 删除编辑器中的默认代码。  
2. 复制你要使用的 Pine Script 脚本代码，并粘贴进去。

例如：  

```pinescript
//@version=6
indicator("My First Pine Script", overlay=true)
plot(close, color=color.blue, title="Close Price")
```

## ✅ 添加脚本到图表
1. 点击 Pine 编辑器右上角的 “添加到图表（Add to chart）” 按钮。
2. 脚本加载成功后，你会在图表上看到对应的指标或策略。


## ✅ 保存并管理脚本
1. 点击编辑器上方的 “保存（Save）” 按钮，为你的脚本命名。
2. 以后，你可以在 指标 & 策略 → 我的脚本 中快速加载它。
