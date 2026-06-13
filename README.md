# 乐屋明的作品档案

这是一个基于 GitHub Pages / Jekyll 的个人作品档案站，用来记录机器人、Grasshopper、软硬件实验和图文笔记。

## 添加一个作品

在 `_projects/` 里新建一个 Markdown 文件，例如：

```yaml
---
layout: project
title: "作品标题"
date: 2026-06-14
summary: "一句话介绍这个作品。"
cover: "/assets/images/example/cover.jpg"
tags: ["Robotics", "Hardware"]
gallery:
  - image: "/assets/images/example/photo-1.jpg"
    caption: "图片说明"
---
```

正文直接写 Markdown。首页会自动读取作品列表。

## 添加一篇记录

在 `_notes/` 里新建一个 Markdown 文件，例如：

```yaml
---
layout: note
title: "记录标题"
date: 2026-06-14
cover: "/assets/images/example/cover.jpg"
tags: ["记录", "工具"]
---
```

图片建议放在 `assets/images/` 下，并使用英文文件名。
