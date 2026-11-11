---
layout: post
title: "Hello, GitHub Pages"
date: 2026-11-11 23:40:00 +0800
categories: 随笔
tags: [GitHub Pages, Jekyll]
---

这是用 Jekyll 写的第一篇文章。站点由 GitHub Pages 自动构建，推送 `main` 分支后就会生效。

## 怎么写新文章

在 `_posts/` 下新建文件，文件名格式为 `YYYY-MM-DD-英文标题.md`，然后写好 front matter：

```yaml
---
layout: post
title: "文章标题"
date: 2026-11-11 23:40:00 +0800
categories: 随笔
tags: [标签1, 标签2]
---
```

正文用 Markdown 写，支持代码块：

```python
def hello():
    print("hello, pages")
```

图片放到 `assets/` 目录下，引用时用 `/assets/xxx.png` 或相对路径。
