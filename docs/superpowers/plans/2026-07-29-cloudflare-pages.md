# Cloudflare Pages Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** 将公开静态站点通过 Cloudflare Pages 连接到 GitHub `main` 分支并更新项目文档中的在线地址。

**Architecture:** Cloudflare Pages 使用 Git 集成监听 `GoodTimeGGB/ning-md2wechat` 的 `main` 分支。Cloudflare 在仓库根目录运行 `exit 0`，将 `.` 作为静态输出目录；任何后续的 `main` 推送都会触发生产部署。

**Tech Stack:** Cloudflare Pages、GitHub、原生 HTML、Git。

---

### Task 1: 创建 Git 集成的 Cloudflare Pages 项目

**Files:**
- Modify: Cloudflare Pages 项目设置
- Source: `index.html`
- Source: `examples/`

- [ ] **Step 1: 在 Cloudflare 仪表盘进入 Pages 创建流程**

Open `https://dash.cloudflare.com/?to=/:account/workers-and-pages`, then select **Create application** > **Pages** > **Connect to Git**. If Cloudflare requires sign-in, complete the account sign-in before continuing.

Expected: the Git provider selection screen is visible.

- [ ] **Step 2: 授权并选择 GitHub 仓库**

Select GitHub, authorize the Cloudflare Pages GitHub App for `GoodTimeGGB/ning-md2wechat`, then select that repository and choose **Begin setup**.

Expected: the build configuration form for `ning-md2wechat` is visible.

- [ ] **Step 3: 配置静态站点的生产部署**

Enter these values in **Set up builds and deployments**:

| Setting | Value |
|---|---|
| Project name | `ning-md2wechat` |
| Production branch | `main` |
| Framework preset | None |
| Build command | `exit 0` |
| Build output directory | `.` |
| Root directory | repository root |

Select **Save and Deploy**.

Expected: Cloudflare starts a production deployment from the current `main` commit.

- [ ] **Step 4: Capture the deployed Pages address**

After the deployment is successful, record the production URL shown in the project dashboard. Use the actual `*.pages.dev` hostname returned by Cloudflare, even if it differs from `https://ning-md2wechat.pages.dev/`.

Expected: the URL returns the project homepage and the deployment is associated with `main`.

### Task 2: Verify the deployed static application

**Files:**
- Verify: deployed `index.html`
- Verify: deployed `examples/demo-themes-v1.html`
- Verify: deployed `examples/demo-themes-v2.html`

- [ ] **Step 1: Verify the production homepage controls**

Open the recorded Cloudflare Pages URL and check for the following unique elements:

```text
#editor
#theme-bar containing 10 .theme-pill elements
#preview-article
#btn-copy
```

Expected: each selector exists once except `.theme-pill`, which exists ten times.

- [ ] **Step 2: Verify theme example pages**

Open these paths using the recorded Pages URL as the base:

```text
/examples/demo-themes-v1.html
/examples/demo-themes-v2.html
```

Expected: both pages return content and load their theme demonstrations.

### Task 3: Publish the Cloudflare address in project documentation

**Files:**
- Modify: `README.md`
- Modify: `docs/RELEASE.md`

- [ ] **Step 1: Replace the primary online-tool and example-page links**

In `README.md`, set the primary online tool link to the recorded Cloudflare Pages URL and set both theme example links to the same host under `/examples/demo-themes-v1.html` and `/examples/demo-themes-v2.html`. Retain the GitHub repository URL.

In `docs/RELEASE.md`, describe Cloudflare Pages as the primary deployment and GitHub Pages as the fallback URL `https://goodtimeggb.github.io/ning-md2wechat/`.

- [ ] **Step 2: Verify all external documentation URLs**

Run:

```powershell
rg -n 'pages\.dev|goodtimeggb\.github\.io|agentos-app|<你的用户名>' README.md docs\RELEASE.md
git diff --check
```

Expected: both documentation files list the actual Cloudflare hostname, retain the GitHub Pages fallback URL, contain no `agentos-app` link or username placeholder, and have no whitespace errors.

- [ ] **Step 3: Commit and push the document updates**

Run:

```powershell
git add README.md docs/RELEASE.md
git commit -m "docs: add Cloudflare Pages links"
git push origin main
```

Expected: the documentation commit reaches `origin/main`, triggering a new Cloudflare production deployment.

- [ ] **Step 4: Verify the automatic deployment after the documentation push**

In the Cloudflare Pages dashboard, confirm the newest production deployment is successful and is associated with the documentation commit. Open the Pages URL once more and confirm the editor, theme bar, preview, and copy button remain present.
