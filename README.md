# 向量脉冲

一个使用 Jekyll Minima 主题的中文博客。GitHub Pages 发布时从 `main` 分支的根目录构建。

## 编辑或新增文章

在 GitHub 仓库里打开 `_posts`。修改已有的 Markdown 文件并提交。新增文章时，可以复制一篇现有文章，把新文件命名为 `YYYY-MM-DD-英文短名.md`，再修改标题、日期、分类和正文。

```markdown
---
layout: post
title: "文章标题"
date: 2026-11-22 12:00:00 +0800
topic: 行业动态
---

第一段会显示在首页作为摘要。

从这里继续写正文。

[原始来源](https://example.com)
```

在 `_config.yml` 修改博客名称和描述，在 `about.md` 修改关于页面。提交后可在仓库的 Actions 标签查看发布进度。

首页默认选最新文章作为头条。要手动指定头条，在一篇文章的文件开头加入 `featured: true`，并移除其他文章的这个字段。归档按 `topic` 自动分组。
