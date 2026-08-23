# SYSU-ReMajor

中山大学非官方转专业信息交流站点，基于 Quartz 构建。

## 项目信息

- 网站: [https://sysu-remajor.github.io](https://sysu-remajor.github.io)
- 邮箱: [sysu-remajor@proton.me](mailto:sysu-remajor@proton.me)

## 仓库结构

- `content/`: 内容主目录，同时也是 Obsidian Vault
- `content/assert/`: 图片、PDF 等静态资源目录
- `content/template/`: Obsidian 模板目录

> [!NOTE]
> `content/.obsidian` 已配置：
>
> - `attachmentFolderPath = assert`
> - templates folder = `template`

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

仓库使用 GitHub Actions 自动部署到 GitHub Pages。

- 工作流文件：`.github/workflows/deploy-pages.yml`
- 触发条件：推送到 `main` 分支或手动触发

## 贡献入口

详细规范请看 [`content/如何参与贡献.md`](content/如何参与贡献.md)
