
---
layout: post
title: "BugKu CTF Writeup-POST"
date: 2026-09-12
categories: CTF
tags: [Bugku, Web]
---

# BugKu CTF Writeup - POST

## 题目类型
WEB

## 题目描述
CtrlU页面给出代码，用上一题的方法无法拿到flag，需要使用POST提交参数。

## 解题过程
1. 访问题目链接，查看页面中的代码。
2. F12打开控制台，输入`允许粘贴`解除浏览器粘贴限制。
3. 在控制台粘贴网上找的JS代码发送POST请求，参数设置为what=flag。
4. 执行代码，查看返回响应，提取flag。

## 笔记
POST参数放在请求体，不能直接写在URL。浏览器控制台有安全限制，粘贴代码前需要输入允许粘贴。
