# SYSU-ReMajor

中山大学非官方转专业信息交流站点（基于 Quartz 构建）。

## 项目信息

- 网站: [http://sysu-remajor.github.io](http://sysu-remajor.github.io)
- 邮箱: [sysu-remajor@proton.me](mailto:sysu-remajor@proton.me)
- 地区: China

## 仓库结构（核心）

- `content/`: 内容主仓库，同时是 Obsidian Vault
- `content/assert/`: 图片与 PDF 等资源目录
- `content/template/`: Obsidian 模板目录

> [!NOTE]
> `content/.obsidian` 已配置：
>
> - `attachmentFolderPath = assert`
> - templates folder = `template`

> [!TIP]
> 计划在 Obsidian 12.0 发布后补充一份给 AGENT 使用的 `obsidian-cli` 协作文档。

## 本地开发

```bash
npm ci
npx quartz build --serve
```

## 构建

```bash
npx quartz build
```

构建产物位于 `public/`（本地生成目录，不建议入库）。

## 部署

仓库使用 GitHub Actions 自动部署到 GitHub Pages：

- 工作流文件：`.github/workflows/deploy-pages.yml`
- 触发条件：推送到 `main` 分支或手动触发

## 贡献入口

详细规范请看：
[`content/如何参与贡献.md`](content/如何参与贡献.md)
