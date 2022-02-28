---
layout: post
title: Welcome to Not Pure Poole
date: 2022-02-23 19:18 +0800
last_modified_at: 2022-02-28 09:00:00 +0800
tags: [React, CSS]
toc:  true
---
**styled components**

## 独立css文件的弊端
-组件和样式无法对应.难以确定样式在哪些组件中被使用, 容易留下已弃用的样式代码. 想要确定样式时, 需要切换到 CSS 文件找.

-文件个数多. 组件都有一个单独的样式文件.

-命名容易重复.

## 介绍
使用模版字符串和 CSS 语法, 生成一个样式化组件.

## 优势
-样式组件化. CSS 和 TS 是一个整体, 符合 React 组件化风格.

-生成唯一的 className , 避免重复.

-动态加载 CSS , 减少代码加载量.

## 详细内容
1. 支持原生 Dom 和自定义组件
  ![原生dom](/assets/images/styled-components/1-1.png)
  ![自定义组件](/assets/images/styled-components/1-2.png)
2. 支持写入伪类及 与className 混用
    ![与className混用](/assets/images/styled-components/2.png)
3. 基于组件扩展
   ![扩展](/assets/images/styled-components/3.png)
4. 根据 props 调整样式
   ![根据 props 调整样式](/assets/images/styled-components/4-1.png)
   ![根据 props 调整样式](/assets/images/styled-components/4-2.png)
5. attrs 修改 props
  ![修改 props](/assets/images/styled-components/5.png)

## 高级
动画; 主题; 与其他CSS混合使用(优于选择器)等均支持.


<a href="https://github.com/styled-components/styled-components">源码</a>

