# 主题：暗夜棱镜风 (prism)

**调用名**：棱镜风 / prism

深空暗色块 + 棱镜渐变光。像 SpaceX 发布会和 AGI 科幻电影的视觉——最适合 AI 前沿、模型发布、硬核技术内容。

## 设计令牌

```
正文背景:   #ffffff  (正文区白底保证阅读)
深空:       #0a0e1a  (暗色块背景)
棱镜紫:     #7c5cff
棱镜青:     #00d4ff
棱镜粉:     #ff5ca8
棱镜渐变:   linear-gradient(135deg, #7c5cff 0%, #00d4ff 100%)
暗夜文字:   #e8eaf0  (暗色块上的亮文字)
暗夜次要:   #9aa0b4
正文墨色:   #23263a
正文次要:   #6b7086
边框色:     #e4e6f0
引用底:     #f4f5fb
圆角:       10px
字体:       -apple-system,'PingFang SC','Microsoft YaHei',sans-serif
核心特色:   暗色 hero 区 + 霓虹强调 + 白底正文，明暗交替的节奏感
```

**设计原则**：暗色块只用于标题区、金句、代码块、预告、签名五个"重音"位置，正文保持白底，形成明暗节奏。

---

## 1. 标题区（暗色 hero）

```html
<section style="margin-bottom: 32px; background: linear-gradient(160deg, #0a0e1a 0%, #141b3a 60%, #1a1040 100%); border-radius: 10px; padding: 32px 26px; text-align: center;">
  <section style="display: inline-block; border: 1px solid #7c5cff; color: #b8a9ff; font-size: 11px; padding: 4px 16px; border-radius: 20px; margin-bottom: 18px; letter-spacing: 2px;">AI 基础设施科普 · 第 5 篇</section>
  <h1 style="font-size: 26px; font-weight: 800; color: #ffffff; line-height: 1.4; margin: 0 0 12px;">不只是"聊天机器人"</h1>
  <p style="font-size: 15px; margin: 0 0 14px; background: linear-gradient(90deg, #7c5cff, #00d4ff); -webkit-background-clip: text; color: #00d4ff; font-weight: 600;">——AI Agent 到底是什么？</p>
  <section style="height: 2px; width: 80px; margin: 0 auto 14px; background: linear-gradient(90deg, #7c5cff, #00d4ff);"></section>
  <p style="font-size: 13px; color: #9aa0b4; margin: 0;">让 AI 从"只会说话"变成"会自己干活"</p>
</section>
```

注：`-webkit-background-clip:text` 在公众号不稳定，渐变文字改用纯色 `#00d4ff` 替代。

---

## 2. 系列导语

```html
<section style="background: #f4f5fb; border-left: 3px solid #7c5cff; border-radius: 0 10px 10px 0; padding: 16px 20px; margin: 0 0 28px;">
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;">本文是「AI 基础设施科普」系列第 <strong style="color: #7c5cff;">5</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 18px;">
  <section style="display: flex; align-items: center; gap: 12px;">
    <span style="display: inline-flex; align-items: center; justify-content: center; min-width: 34px; height: 34px; background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; font-size: 15px; font-weight: 800; border-radius: 8px; padding: 0 8px;">一</span>
    <h2 style="font-size: 19px; font-weight: 800; color: #23263a; margin: 0; line-height: 1.5;">Chatbot 和 Agent 有什么区别？</h2>
  </section>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 700; color: #7c5cff; margin: 28px 0 12px;">▍一个真实例子</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 1.9; color: #23263a; margin: 0 0 22px; letter-spacing: 0.3px;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<p style="font-size: 17px; line-height: 1.9; color: #7c5cff; margin: 0 0 22px; font-weight: 800;"><strong>Chatbot 只能"说话"，Agent 能"做事。"</strong></p>
```

行内高亮：

```html
<span style="color: #ff5ca8; font-weight: 600;">关键文字</span>
```

---

## 7. 类比引用块

```html
<section style="background: #f4f5fb; border: 1px solid #e4e6f0; border-left: 3px solid #00d4ff; border-radius: 0 10px 10px 0; padding: 16px 20px; margin: 0 0 22px;">
  <p style="margin: 0 0 12px; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜。</p>
</section>
```

---

## 8. 金句引用块（暗色重音）

```html
<section style="background: linear-gradient(160deg, #0a0e1a 0%, #141b3a 70%, #1a1040 100%); border-radius: 10px; padding: 24px 26px; margin: 28px 0;">
  <section style="height: 2px; width: 40px; background: linear-gradient(90deg, #7c5cff, #00d4ff); margin-bottom: 14px;"></section>
  <p style="margin: 0 0 10px; font-size: 18px; color: #ffffff; line-height: 1.8; font-weight: 800;"><strong>Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</strong></p>
  <p style="margin: 0; font-size: 14px; color: #9aa0b4; line-height: 1.9;">它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto; border-radius: 10px; border: 1px solid #e4e6f0;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px;">
    <thead>
      <tr>
        <th style="padding: 12px; text-align: center; color: #fff; font-weight: 700; background: #23263a;">维度</th>
        <th style="padding: 12px; text-align: center; color: #fff; font-weight: 700; background: #23263a;">Chatbot</th>
        <th style="padding: 12px; text-align: center; color: #fff; font-weight: 700; background: #23263a;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #23263a; font-weight: 700; background: #f4f5fb; border-bottom: 1px solid #e4e6f0;">交互方式</td>
        <td style="padding: 10px 12px; text-align: center; color: #6b7086; border-bottom: 1px solid #e4e6f0;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; text-align: center; color: #6b7086; border-bottom: 1px solid #e4e6f0;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #23263a; font-weight: 700; background: #f4f5fb;">工具使用</td>
        <td style="padding: 10px 12px; text-align: center; color: #6b7086;">不能调用外部工具</td>
        <td style="padding: 10px 12px; text-align: center; color: #6b7086;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 12px; margin: 24px 0;">
  <section style="flex: 1; background: #f4f5fb; border: 1px solid #e4e6f0; border-radius: 10px; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #6b7086; margin: 0 0 8px;">传统开发</p>
    <p style="font-size: 20px; font-weight: 800; color: #ff5ca8; margin: 0 0 4px;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #9aa0b4; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; background: linear-gradient(160deg, #0a0e1a, #141b3a); border-radius: 10px; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #9aa0b4; margin: 0 0 8px;">秒哒开发</p>
    <p style="font-size: 20px; font-weight: 800; color: #00d4ff; margin: 0 0 4px;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #9aa0b4; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0; border-radius: 10px; overflow: hidden;">
  <section style="background: #141b3a; padding: 8px 16px; display: flex; align-items: center; justify-content: space-between;">
    <span style="font-size: 12px; color: #9aa0b4;">prompt.md</span>
    <span style="font-size: 11px; color: #7c5cff; border: 1px solid #7c5cff; border-radius: 12px; padding: 1px 10px;">Prompt</span>
  </section>
  <section style="background: #0a0e1a; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e8eaf0; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code># 角色设定
你是一个"反内耗闺蜜"

# 核心功能
1. 潜台词翻译
2. 高情商回怼
3. 情绪急救包</code></pre>
  </section>
</section>
```

### 普通代码块
```html
<section style="background: #0a0e1a; border-radius: 10px; padding: 16px; margin: 20px 0; overflow-x: auto;">
  <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e8eaf0; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code>100000 / 1688 * 1688</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0; text-align: center;">
  <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; border-radius: 10px; display: block; margin: 0 auto; border: 1px solid #e4e6f0;" />
  <p style="font-size: 13px; color: #9aa0b4; margin: 8px 0 0;">图：秒哒主页 —— 「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="background: #f4f5fb; border-left: 3px solid #ff5ca8; border-radius: 0 10px 10px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;"><strong style="color: #ff5ca8;">关键数据</strong>　传统开发成本2万元、耗时4个月；秒哒不到50元、不到1小时。</p>
</section>
```

### 实测体验
```html
<section style="background: #f4f5fb; border-left: 3px solid #00d4ff; border-radius: 0 10px 10px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;"><strong style="color: #00a8cc;">实测体验</strong>　前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。</p>
</section>
```

### 收获标注
```html
<section style="background: #f4f5fb; border-left: 3px solid #7c5cff; border-radius: 0 10px 10px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;"><strong style="color: #7c5cff;">收获：</strong>　验证了秒哒对个人工具类App的支撑能力。</p>
</section>
```

### 踩坑提示
```html
<section style="background: #fff4f8; border-left: 3px solid #ff5ca8; border-radius: 0 10px 10px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #23263a; line-height: 1.9; letter-spacing: 0.3px;"><strong style="color: #ff5ca8;">踩坑提醒</strong>　Windows 下路径有空格会导致安装失败。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 10px;">
    <span style="display: inline-flex; align-items: center; justify-content: center; min-width: 30px; height: 30px; background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; font-size: 14px; font-weight: 800; border-radius: 8px; padding: 0 8px;">01</span>
    <span style="font-size: 17px; font-weight: 700; color: #23263a;">用自然语言描述你的需求</span>
  </section>
  <p style="font-size: 16px; line-height: 1.9; color: #23263a; margin: 0; letter-spacing: 0.3px;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 28px; border-left: 2px solid #e4e6f0;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 22px; height: 22px; background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; font-size: 11px; font-weight: 800; border-radius: 6px;">1</span>
    <p style="font-size: 16px; color: #23263a; margin: 0 0 4px; font-weight: 700;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #6b7086; margin: 0; line-height: 1.9;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 22px; height: 22px; background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; font-size: 11px; font-weight: 800; border-radius: 6px;">2</span>
    <p style="font-size: 16px; color: #23263a; margin: 0 0 4px; font-weight: 700;">思考（Think）</p>
    <p style="font-size: 15px; color: #6b7086; margin: 0; line-height: 1.9;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 22px; height: 22px; background: linear-gradient(135deg, #ff5ca8, #ff8fb0); color: #fff; font-size: 11px; font-weight: 800; border-radius: 6px;">3</span>
    <p style="font-size: 16px; color: #23263a; margin: 0 0 4px; font-weight: 700;">行动（Act）</p>
    <p style="font-size: 15px; color: #6b7086; margin: 0; line-height: 1.9;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; background: #f4f5fb; border: 1px solid #e4e6f0; border-radius: 10px; padding: 20px;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 8px;">
    <span style="background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; font-size: 12px; font-weight: 700; padding: 3px 12px; border-radius: 6px;">CASE 01</span>
    <span style="font-size: 16px; font-weight: 700; color: #23263a;">心情日记App</span>
  </section>
  <p style="font-size: 13px; color: #9aa0b4; margin: 0 0 12px;">个人工具 · 心理健康类</p>
  <p style="font-size: 16px; line-height: 1.9; color: #23263a; margin: 0; letter-spacing: 0.3px;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 700; color: #7c5cff; margin: 0 0 6px;">Level 1：Chatbot（纯对话）</p>
  <section style="background: #f4f5fb; border-radius: 8px; padding: 12px 18px; margin: 0 0 16px;">
    <p style="margin: 0; font-size: 15px; color: #6b7086; line-height: 1.9; letter-spacing: 0.3px;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 1.9; color: #23263a; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.3px;">
  <li style="margin-bottom: 10px;"><strong style="color: #7c5cff;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><strong style="color: #7c5cff;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><strong style="color: #7c5cff;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 1.9; color: #23263a; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.3px;">
  <li style="margin-bottom: 10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线

```html
<section style="text-align: center; margin: 36px 0;">
  <span style="display: inline-block; width: 50px; height: 2px; background: linear-gradient(90deg, #7c5cff, #00d4ff);"></span>
</section>
```

---

## 20. 下一篇预告（暗色）

```html
<section style="margin: 28px 0; background: linear-gradient(160deg, #0a0e1a 0%, #141b3a 100%); border-radius: 10px; padding: 18px 22px;">
  <p style="font-size: 11px; color: #7c5cff; letter-spacing: 2px; margin: 0 0 6px;">NEXT ▸ 下一篇预告</p>
  <p style="font-size: 15px; color: #e8eaf0; margin: 0; line-height: 1.9;">下一篇我们聊 <strong style="color: #00d4ff;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <section style="display: inline-block; width: 50px; height: 2px; background: linear-gradient(90deg, #7c5cff, #00d4ff);"></section>
  <p style="font-size: 12px; color: #9aa0b4; margin: 8px 0 0; letter-spacing: 3px;">END</p>
</section>
```

---

## 22. 作者签名（暗色收尾）

```html
<section style="margin-top: 40px; background: linear-gradient(160deg, #0a0e1a 0%, #141b3a 100%); border-radius: 10px; padding: 24px 26px;">
  <section style="height: 2px; width: 40px; background: linear-gradient(90deg, #7c5cff, #00d4ff); margin-bottom: 14px;"></section>
  <p style="font-size: 15px; color: #e8eaf0; line-height: 2; margin: 0 0 8px;">
    我是 <strong style="color: #00d4ff;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #00d4ff;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #9aa0b4; line-height: 2; margin: 0 0 10px;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #e8eaf0; line-height: 2; margin: 0;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #ff5ca8;">点赞、在看、转发</strong>三连，我们下篇见。
  </p>
</section>
```

---

## 23. 预览外壳

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>预览 - 暗夜棱镜风</title>
  <style>
    body { background: #05070f; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #fff; border-radius: 12px; overflow: hidden; box-shadow: 0 0 60px rgba(124,92,255,0.2); }
    .toolbar { padding: 12px 20px; background: #0a0e1a; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #9aa0b4; }
    .toolbar button { background: linear-gradient(135deg, #7c5cff, #00d4ff); color: #fff; border: none; padding: 6px 16px; border-radius: 6px; cursor: pointer; font-size: 13px; }
    .content { padding: 24px 20px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>◢ PRISM · 暗夜棱镜风 · 宁的AI小站</span>
      <button onclick="copyContent()">复制到公众号</button>
    </div>
    <div class="content" id="article-content">
      <!-- 这里放 section 正文 -->
    </div>
  </div>
  <script>
    function copyContent() {
      var content = document.getElementById('article-content');
      var range = document.createRange();
      range.selectNodeContents(content);
      var sel = window.getSelection();
      sel.removeAllRanges();
      sel.addRange(range);
      document.execCommand('copy');
      sel.removeAllRanges();
      alert('已复制！到公众号编辑器 Ctrl+V 粘贴');
    }
  </script>
</body>
</html>
```
