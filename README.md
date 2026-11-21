# Michaellin0302 的博客

简洁极客风个人博客,纯静态 HTML/CSS,零依赖,托管在 GitHub Pages。

线上地址:<https://michaellin0302.github.io/>

## 写新文章

1. 复制 `posts/hello-world.html` 为新文件(如 `posts/my-first-post.html`),修改标题、日期和正文
2. 在 `index.html` 的 `ul.posts` 列表中加一行链接
3. 提交并推送,约 1 分钟后自动上线:

```bash
git add -A
git commit -m "新文章:标题"
git push
```

## 结构

```
├── index.html          首页 + 文章列表
├── about.html          关于页
├── posts/              文章
│   └── hello-world.html
├── assets/
│   └── style.css       全站样式(极客暗色主题)
└── README.md
```
