---
title: "GitHub Actions 自动化部署入门"
date: 2026-04-01
draft: false
tags: ["GitHub", "DevOps", "自动化"]
categories: ["技术"]
---

## 什么是 GitHub Actions？

GitHub Actions 是 GitHub 提供的 CI/CD 工具，可以自动化构建、测试和部署。

## 核心概念

- **Workflow** - 自动化的工作流程
- **Job** - 工作流中的一个任务
- **Step** - 任务中的具体步骤
- **Action** - 可复用的步骤单元

## 博客自动部署示例

```yaml
- name: Deploy
  uses: actions/deploy-pages@v4
```

配合 Hugo，每次推送代码后博客会自动更新，完全无需手动操作。
