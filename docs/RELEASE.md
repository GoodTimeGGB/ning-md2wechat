# 发布指南：GitHub 仓库 + GitHub Pages

本仓库已按标准结构准备好，按以下步骤发布（约 5 分钟）。

## 一、初始化本地仓库并提交

在 `ning-md2wechat/` 目录下执行：

```bash
cd ning-md2wechat
git init
git add -A
git commit -m "feat: 宁的AI小站公众号排版工具 v1.0"
```

## 二、在 GitHub 创建远程仓库

1. 打开 <https://github.com/new>
2. Repository name 填：`ning-md2wechat`
3. Public / Private 自选（Pages 公开访问需要 Public，或账号有 Pro 的 Private Pages）
4. **不要**勾选 "Add a README"（仓库里已有）
5. 点 Create repository

## 三、推送代码

把 `<你的用户名>` 换成你的 GitHub 用户名：

```bash
git remote add origin https://github.com/<你的用户名>/ning-md2wechat.git
git branch -M main
git push -u origin main
```

## 四、开启 GitHub Pages（示例页 + 在线工具）

1. 仓库页面 → **Settings** → 左侧 **Pages**
2. Source 选 **Deploy from a branch**
3. Branch 选 **main**，目录选 **/ (root)**，点 Save
4. 等 1-3 分钟，访问：

| 页面 | 地址 |
|------|------|
| 在线排版工具 | `https://<你的用户名>.github.io/ning-md2wechat/` |
| 主题示例页 ① | `https://<你的用户名>.github.io/ning-md2wechat/examples/demo-themes-v1.html` |
| 主题示例页 ② | `https://<你的用户名>.github.io/ning-md2wechat/examples/demo-themes-v2.html` |

## 五、发布后更新 README

README.md 顶部的"在线体验"链接目前指向临时演示地址，发布成功后把它替换成你的 Pages 地址，再提交一次：

```bash
git add README.md
git commit -m "docs: 更新在线体验地址为 GitHub Pages"
git push
```

## 日常更新流程

以后改了 `index.html`（比如加主题、修 bug）：

```bash
git add -A
git commit -m "feat/fix: 改动说明"
git push
```

Pages 会自动重新部署（约 1 分钟），无需其他操作。

## 常见问题

- **Pages 404**：确认分支和目录选对；确认访问路径大小写一致；首次部署等 3 分钟再刷新。
- **样式在微信里丢失**：工具输出全部内联样式，正常不会丢；若个别丢失，检查是否手动改过公众号编辑器里的内容。
- **外链不可点**：公众号平台限制，只有 `mp.weixin.qq.com` 域名链接可在文章内点击，与工具无关。
