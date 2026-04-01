# Bryan的博客

使用 Hugo + GitHub Actions 搭建的个人博客。

## 快速开始

### 本地预览

```bash
# 安装 Hugo
brew install hugo

# 克隆仓库
git clone https://github.com/bryanchen007/hugo-blog.git
cd hugo-blog

# 本地预览
hugo server
```

访问 `http://localhost:1313` 即可预览。

### 发布文章

在 `content/posts/` 目录下创建 Markdown 文件，命名格式：

```
2026-04-01-my-first-post.md
```

Front Matter 示例：

```markdown
---
title: "我的第一篇文章"
date: 2026-04-01
draft: false
tags: ["随笔", "博客"]
categories: ["日常"]
---

这里是文章内容...
```

## 自动化部署

每次推送到 `main` 分支，GitHub Actions 会自动：
1. 拉取代码
2. 运行 Hugo 构建
3. 部署到 GitHub Pages

无需手动操作。

## 主题

使用 [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke) 主题。
