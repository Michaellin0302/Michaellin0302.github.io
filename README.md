# Michaellin0302 的博客

明亮现代风个人博客,纯静态 HTML/CSS,零依赖、零外部资源,托管在 GitHub Pages。

线上地址:<https://blog.midodo.tech>

## 写新文章

1. 复制 `posts/hello-world.html` 为新文件(如 `posts/my-post.html`),修改标题、日期和正文
2. 在 `index.html` 的 `feature-grid` 里复制一张卡片,并在 `foot-grid` 的「建站记系列/最新文章」里加链接
3. 提交并推送,约 1 分钟后自动上线:

```bash
git add -A
git commit -m "新文章:标题"
git push
```

## 结构

```
├── index.html             首页(居中文字 Logo/导航/打字机大标题/口号/联系邮箱)
├── about.html             关于(技能进度/时间线/联系)
├── posts/                 文章「建站记」系列
│   ├── hello-world.html      ① 博客开通
│   ├── register-github.html  ② 注册 GitHub
│   ├── first-site.html       ③ Pages 建站
│   ├── cli-and-mirror.html   ④ 加速填坑
│   └── custom-domain.html    ⑤ 绑定域名
├── assets/
│   └── style.css          明亮现代风全站样式
├── CNAME                  自定义域名 blog.midodo.tech
└── README.md
```
