# SYSU-ReMajor

中山大学非官方转专业信息交流。

## 项目信息

- 网站: [http://sysu-remajor.github.io](http://sysu-remajor.github.io)
- 邮箱: [sysu-remajor@proton.me](mailto:sysu-remajor@proton.me)
- 地区: China

## 本地开发

```bash
npm ci
npx quartz build --serve
```

## 构建

```bash
npx quartz build
```

构建产物位于 `public/`。

## 部署

仓库使用 GitHub Actions 自动部署到 GitHub Pages：

- 工作流文件：`.github/workflows/deploy-pages.yml`
- 触发条件：推送到 `main` 分支或手动触发
