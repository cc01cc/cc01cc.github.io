---
layout: post
---

# initial-jekyll

## Jekyll 目录结构

```txt
.
├── _config.yml (配置)
├── _drafts (草稿)
|   └── initial-jekyll.md
├── _includes (需重用的内容)
|   ├── footer.html
|   └── header.html
├── _layouts (布局)
|   ├── default.html
|   └── post.html
├── _posts (存放文章)
|   └── 2022-05-31-initial-jekyll.md
└── index.html
```

## 博文链接

> Tags Filters | Jekyll • Simple, blog-aware, static sites: <https://jekyllrb.com/docs/liquid/tags/#linking-to-posts>

博文使用 `post_url` 标签引用链接

```txt
{% post_url 2022-05-31-name-of-post %}
```