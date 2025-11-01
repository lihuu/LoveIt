---
title: "{{ replace .Name "-" " " | title }}"
subtitle: "项目副标题描述"
date: {{ .Date }}
lastmod: {{ .Date }}
draft: true

# 项目元信息
status: "active" # active, completed, archived, development
technologies: ["技术1", "技术2", "技术3"]

# 项目链接
github: "https://github.com/username/project"
demo: "https://demo.example.com"
download: "https://releases.example.com"

# 特色图片
featuredImage: "/images/projects/project-featured.jpg"

# 项目画廊
gallery:
  - image: "/images/projects/screenshot1.jpg"
    title: "截图1"
    caption: "主界面展示"
  - image: "/images/projects/screenshot2.jpg"
    title: "截图2"
    caption: "功能演示"

# 项目统计
stats:
  - label: "代码行数"
    value: "10K+"
  - label: "贡献者"
    value: "5"
  - label: "Star数"
    value: "100+"
  - label: "Fork数"
    value: "20+"

# 分类和标签
categories: ["项目"]
tags: ["技术标签1", "技术标签2"]

# 页面设置
lightgallery: true
share:
  enable: true
comment:
  enable: true
---

## 项目简介

在这里写项目的详细介绍...

## 主要功能

- 功能点 1：描述
- 功能点 2：描述
- 功能点 3：描述

## 技术栈

- **前端**: 技术列表
- **后端**: 技术列表
- **数据库**: 技术列表
- **部署**: 技术列表

## 安装使用

```bash
# 克隆项目
git clone https://github.com/username/project.git

# 安装依赖
npm install

# 运行项目
npm start
```

## 项目亮点

1. **特色功能 1**: 详细描述...
2. **特色功能 2**: 详细描述...
3. **特色功能 3**: 详细描述...

## 未来规划

- [ ] 计划功能 1
- [ ] 计划功能 2
- [ ] 计划功能 3

## 贡献指南

欢迎提交 Issue 和 Pull Request！

## 许可证

本项目采用 MIT 许可证。
