# Rune 的博客

基于 [Hugo](https://gohugo.io/) + [hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack) 的静态博客。

- 线上地址：<https://blog.520236.xyz>
- 部署：GitHub Pages（GitHub Actions 自动构建）

## 写文章

在 `content/post/` 新建 Markdown 文件（带 front matter），push 到 `main` 分支即可自动发布：

```bash
hugo new post/我的文章.md   # 本地新建
git add -A && git commit -m "新文章" && git push
```

## 本地开发

```bash
hugo server -D    # 本地预览
hugo --minify     # 构建到 public/
```

主题源码：<https://github.com/CaiJimmy/hugo-theme-stack>
