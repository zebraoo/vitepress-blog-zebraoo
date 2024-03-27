---
title: 'vitepress装修攻略'
date: 2024-03-27
author: zebraoo
tags:
  - viteprss
  - css
---
# vitepress装修攻略

## 自定义主页
1. 首先创建Blog.vue
2. 在根目录index.md导入Blog.vue,可选择全局导入

```markdown
---
layout: home
---

<Blog/>
```
> layout属性可见 https://vitepress.dev/zh/reference/frontmatter-config#layout

## 布局插槽
> https://vitepress.dev/zh/guide/extending-default-theme#layout-slots
