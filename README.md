# GitHub Pages Starter (中文)

这是一个可直接部署到 GitHub Pages 的静态网站模板：HTML + CSS + JS。

## 部署步骤（两种方式）

### 方式 A：个人主页仓库
1. 在 GitHub 创建名为 **`<你的用户名>.github.io`** 的仓库（例如 `alice.github.io`）。
2. 把本模板中的所有文件提交并推送到该仓库的 `main` 分支。
3. 访问 `https://<你的用户名>.github.io/` 即可看到网站。

### 方式 B：项目站点仓库
1. 使用任意仓库名（例如 `my-site`）。
2. 进入仓库 **Settings → Pages**，Source 选择 **Deploy from a branch**，分支选 `main`、文件夹 `/ (root)`。
3. 保存后等待几分钟，GitHub Pages 会生成一个地址（通常形如 `https://<用户名>.github.io/<仓库名>/`）。

> 如果你想用 Jekyll + Markdown（例如写博客），只需在根目录添加 `_config.yml` 和 `index.md`，或启用现成的 Jekyll 主题即可。

## 目录结构
```
.
├── index.html
├── about.html
├── blog.html
├── 404.html
├── assets
│   ├── css/style.css
│   └── js/main.js
└── README.md
```

## 本地预览
直接用浏览器打开 `index.html`，或在根目录执行：
```bash
python3 -m http.server 3000
```
然后访问 http://localhost:3000

## 自定义
- 修改 `index.html` 中标题、导航、文案。
- 替换 `assets/img/` 中的图片资源。
- 在 `blog.html` 增加文章链接；或迁移到 Jekyll 以便用 Markdown 写作。

祝使用愉快！
