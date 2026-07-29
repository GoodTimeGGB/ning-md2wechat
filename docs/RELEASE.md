# 发布与维护指南

项目仓库：<https://github.com/GoodTimeGGB/ning-md2wechat>

在线工具：<https://goodtimeggb.github.io/ning-md2wechat/>

本项目是零依赖静态页面。GitHub Pages 从 `main` 分支的根目录发布，根目录的 `index.html` 即为在线工具首页。

## 日常更新

修改 `index.html`、示例文件或 README 后，在项目根目录执行：

```bash
git add -A
git commit -m "feat: 描述本次改动"
git push origin main
```

GitHub Pages 会在推送后自动重新部署。首次部署或较大更新可能需要几分钟生效。

## 页面地址

| 页面 | 地址 |
|------|------|
| 在线排版工具 | <https://goodtimeggb.github.io/ning-md2wechat/> |
| 主题示例页 ① | <https://goodtimeggb.github.io/ning-md2wechat/examples/demo-themes-v1.html> |
| 主题示例页 ② | <https://goodtimeggb.github.io/ning-md2wechat/examples/demo-themes-v2.html> |

## 故障排查

- **页面暂时 404**：确认 `main` 分支已推送，并等待 GitHub Pages 完成部署后刷新。
- **样式在微信中丢失**：工具复制的是内联样式 HTML；检查是否在公众号编辑器内再次手动调整了粘贴内容。
- **外部链接无法点击**：这是微信公众号平台限制，文章内通常仅微信域名链接可点击。

详细功能说明与本地使用方式见 [README](../README.md)。
