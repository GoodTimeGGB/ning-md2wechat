# Cloudflare Pages 部署设计

## 目标

为「宁的 AI 小站」公众号 Markdown 排版工具新增 Cloudflare Pages 生产部署，改善国内访问体验，同时保留 GitHub 仓库作为源码与版本管理入口。

## 部署架构

Cloudflare Pages 通过 GitHub 集成连接 `GoodTimeGGB/ning-md2wechat`。`main` 是唯一生产分支；每次推送到该分支时，Cloudflare 自动重新部署。项目为无构建步骤的静态站点，构建命令使用 `exit 0`，构建输出目录为 `.`，直接发布根目录中的 `index.html` 及 `examples/` 文件。

首个项目名称为 `ning-md2wechat`，默认地址预计为 `https://ning-md2wechat.pages.dev/`。若该名称不可用，以 Cloudflare 实际分配的 `*.pages.dev` 地址为准。

## 文档与兼容性

首次部署成功并得到实际地址后，README 与 `docs/RELEASE.md` 将把在线工具和主题示例页改为 Cloudflare Pages 地址。现有 GitHub Pages 保留为备用入口，不做删除或重定向。

## 验证

- 确认 Cloudflare 项目连接 GitHub 仓库，生产分支为 `main`。
- 确认 Cloudflare 部署状态为成功，并记录实际 `*.pages.dev` 地址。
- 访问公开站点，确认编辑器、10 个主题、预览区及复制按钮均存在。
- 推送包含文档地址更新的提交，确认 Cloudflare 自动创建新生产部署。
