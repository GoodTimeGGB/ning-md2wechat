# GitHub 公开发布与 GitHub Pages 设计

## 目标

将「宁的 AI 小站」微信公众号 Markdown 排版工具发布到已登录的个人 GitHub 账号，并以公开 GitHub Pages 地址提供可直接使用的在线工具。

## 范围

- 创建公开仓库 `ning-md2wechat`，推送当前 `main` 分支。
- 将根目录的 `index.html` 作为 GitHub Pages 首页，不增加构建工具或框架。
- 更新 README 的在线体验链接为实际 Pages URL，并保留功能、使用方式和许可信息。
- 更新发布指南，使其反映已完成的 GitHub 发布和后续维护方式。

## 架构

站点保持为零依赖静态应用。GitHub Pages 从 `main` 分支的根目录发布：GitHub 在根目录发现 `index.html` 后将其作为站点首页。仓库地址与 Pages 地址分别采用 GitHub 的标准个人账号 URL：

- 仓库：`https://github.com/<github-user>/ning-md2wechat`
- 页面：`https://<github-user>.github.io/ning-md2wechat/`

README 中的在线入口、示例页地址和本地使用说明均以该公开地址为准。发布失败时保留可本地直接打开的单文件使用方式，并在 README 中说明 GitHub Pages 的首次部署可能需要短暂生效时间。

## 验证

- 确认工作区无意外改动，并确认提交已推送至新建公开仓库。
- 确认 GitHub Pages 已配置为从 `main` 分支根目录部署。
- 访问 Pages 首页，检查页面能加载，Markdown 编辑、主题切换与复制按钮可用。
- 检查 README 中的仓库与在线体验链接均指向实际公开地址。
