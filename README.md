# cbeiyou.github.io

基于 Hugo 和 Book 主题的个人博客站点。

## 本地运行

1. **安装 Hugo Book 主题**（首次或克隆后执行）：

   ```bash
   git submodule add https://github.com/alex-shpak/hugo-book themes/hugo-book
   # 如果已克隆且子模块未初始化，使用：
   # git submodule update --init --recursive
   ```

2. **启动开发服务器**：

   ```bash
   hugo server -D
   ```

3. 在浏览器中打开 http://localhost:1313

## 部署到 GitHub Pages

构建静态文件：

```bash
hugo
```

生成的网站文件在 `public/` 目录，可将该目录内容部署到 GitHub Pages。
