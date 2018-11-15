---
title: create-react-app and typescript
date: 2018-11-15 09:13:43
tags:
---

阅读[create-react-app](https://github.com/facebook/create-react-app)源码时发现其官方在追加了[typescript的支持](https://github.com/facebook/create-react-app/commit/b50590f7f42c75ca653fb6f831216c09c34a0f74#diff-f9867c1e09ced1328f2ccdac4afac4a5)，在此之前一直是第三方支持[create-react-app-typescript](https://github.com/wmonk/create-react-app-typescript)

这里简单对比二者的区别

<!-- more -->

# 初始化方式

```bash
# 官方最新支持的
npx create-react-app my-app --typescript
```

```bash
# 第三方支持的
npx create-react-app my-app --scripts-version=react-scripts-ts
```

# 目录结构

左侧第三方，右侧官方
![](目录对比图.png)
