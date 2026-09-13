
---
layout: post
title: "BugKu CTF Writeup-矛盾"
date: 2026-09-12
categories: CTF
tags: [Bugku, Web, ]
---

# BugKu CTF Writeup - 矛盾

## 题目类型
WEB

## 题目描述
访问给出的页面链接，页面展示代码，存在两个看起来矛盾的判断条件，需要利用构造参数拿到flag。

## 解题过程
1. 访问靶场链接，阅读页面PHP源码。
2. 题目要求传入的参数既不能是数字，又要和1相等。
3. 在URL末尾添加`?num=1a`，访问拼接后的地址。
4. 页面输出flag，复制填入输入框提交。

## 笔记
有点像what那道题，都需要构造条件获得flag
