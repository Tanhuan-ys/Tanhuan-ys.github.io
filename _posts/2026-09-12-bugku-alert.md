
---
title: Bugku alert 题目Writeup
date: 2026-09-12
categories: CTF
tags: [Bugku, Web]
---

# Bugku alert 题目Writeup
平台：Bugku CTF
题型：Web

## 题目描述
flag一直在诱惑我，反复出现在我面前，我却无法抓住

## 解题思路
1. 不停点击弹窗，发现没有任何线索
2. 猜想flag藏在网页源码里
3. 查询资料发现地下的乱码就是flag

## 详细步骤
第一步：打开alert题目，弹窗不断弹出。
第二步：F12打开开发者工具，查看源代码。
第三步：找到页面底部的HTML编码字符串。
第四步：复制编码，寻找工具解码，得到flag。

## 收获
有时候真相明明就在眼前，却发现不了，我们要学会利用信息。同时知道了flag密码的知识
