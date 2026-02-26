# 未保存但继续 · unsavedyet

个人博客，基于 Hugo + Book 主题。受 [椒盐豆豉](https://blog.douchi.space/) 启发。

## 本地运行

```bash
# 确保已安装 Hugo Extended
hugo server -D
```

浏览器打开 http://localhost:1313

## 部署

推送到 `main` 分支后，GitHub Actions 自动构建并部署到 GitHub Pages。

**首次部署**：在仓库 Settings → Pages 中，将 Source 设置为 `Deploy from a branch`，Branch 选择 `gh-pages`。

## 写文章

```bash
hugo new posts/你的文章.md
```

编辑 `content/posts/你的文章.md`，在 front matter 中设置 `categories` 和 `tags`。
