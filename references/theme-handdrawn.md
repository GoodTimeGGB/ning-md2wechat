# 主题：手绘笔记风 (handdrawn)

像翻开AI博主的笔记本。虚线边框、暖色底、手写感装饰，有温度但不花哨。

## 设计令牌

```
背景色:     #faf8f3  (米黄纸感)
主色:       #3d6ea5  (手绘蓝)
强调色:     #e8814a  (手绘橙)
墨色:       #4a4a4a  (笔记墨色)
次要色:     #8a8a8a
边框色:     #d4cfc4  (纸边色)
引用底:     #f5f1e8  (浅米黄)
代码底:     #2d2d2d
虚线色:     #c4bda8
圆角:       6px
边框风格:   2px dashed (虚线手绘感)
字体:       标题 'Georgia','Noto Serif SC',serif / 正文 sans-serif
```

---

## 1. 标题区

```html
<section style="margin-bottom: 36px; text-align: center;">
  <p style="font-size: 12px; color: #8a8a8a; letter-spacing: 2px; margin-bottom: 12px; font-family: 'Georgia',serif;">AI 基础设施科普 · 第 5 篇</p>
  <h1 style="font-size: 24px; font-weight: 700; color: #3d6ea5; line-height: 1.5; margin: 0 0 10px; font-family: 'Georgia','Noto Serif SC',serif;">不只是"聊天机器人"</h1>
  <p style="font-size: 15px; color: #8a8a8a; margin: 0 0 14px; font-family: 'Georgia',serif;">——AI Agent 到底是什么？</p>
  <section style="display: inline-block; border-bottom: 2px dashed #c4bda8; padding-bottom: 4px; padding: 0 20px 4px;">
    <p style="font-size: 13px; color: #b0a890; margin: 0;">让 AI 从"只会说话"变成"会自己干活"</p>
  </section>
</section>
```

---

## 2. 系列导语

```html
<section style="background: #f5f1e8; border: 2px dashed #c4bda8; border-radius: 6px; padding: 16px 20px; margin: 0 0 28px;">
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 1.9; letter-spacing: 0.5px;">本文是「AI 基础设施科普」系列第 <strong style="color: #3d6ea5;">5</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"——这个转变的核心，就是 Agent。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 18px;">
  <h2 style="font-size: 19px; font-weight: 700; color: #4a4a4a; margin: 0; padding-left: 14px; border-left: 3px solid #3d6ea5; line-height: 1.5; font-family: 'Georgia','Noto Serif SC',serif;">一、Chatbot 和 Agent 有什么区别？</h2>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 600; color: #3d6ea5; margin: 28px 0 12px; font-family: 'Georgia','Noto Serif SC',serif;">一个真实例子</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 1.9; color: #4a4a4a; margin: 0 0 22px; letter-spacing: 0.5px;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<p style="font-size: 17px; line-height: 1.9; color: #3d6ea5; margin: 0 0 22px; font-weight: 700; letter-spacing: 0.5px;"><strong>Chatbot 只能"说话"，Agent 能"做事。"</strong></p>
```

行内高亮：
```html
<span style="color: #e8814a; font-weight: 600;">关键文字</span>
```

---

## 7. 类比引用块

```html
<section style="background: #f5f1e8; border-left: 3px dashed #c4bda8; padding: 16px 20px; margin: 0 0 22px; border-radius: 0 6px 6px 0;">
  <p style="margin: 0 0 12px; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
  <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜，最后把结果交给你。</p>
</section>
```

---

## 8. 金句引用块

```html
<section style="background: #f5f1e8; border: 2px dashed #3d6ea5; border-radius: 6px; padding: 18px 22px; margin: 24px 0;">
  <p style="margin: 0; font-size: 16px; color: #3d6ea5; line-height: 1.9; font-weight: 600; letter-spacing: 0.5px;"><strong>Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</strong> 它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px;">
    <thead>
      <tr>
        <th style="padding: 10px 12px; text-align: center; color: #3d6ea5; font-weight: 600; border-bottom: 2px dashed #3d6ea5; font-family: 'Georgia',serif;">维度</th>
        <th style="padding: 10px 12px; text-align: center; color: #3d6ea5; font-weight: 600; border-bottom: 2px dashed #3d6ea5; font-family: 'Georgia',serif;">Chatbot</th>
        <th style="padding: 10px 12px; text-align: center; color: #3d6ea5; font-weight: 600; border-bottom: 2px dashed #3d6ea5; font-family: 'Georgia',serif;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #4a4a4a; font-weight: 600; border-bottom: 1px dashed #d4cfc4;">交互方式</td>
        <td style="padding: 10px 12px; text-align: center; color: #8a8a8a; border-bottom: 1px dashed #d4cfc4;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; text-align: center; color: #8a8a8a; border-bottom: 1px dashed #d4cfc4;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #4a4a4a; font-weight: 600; border-bottom: 1px dashed #d4cfc4;">工具使用</td>
        <td style="padding: 10px 12px; text-align: center; color: #8a8a8a; border-bottom: 1px dashed #d4cfc4;">不能调用外部工具</td>
        <td style="padding: 10px 12px; text-align: center; color: #8a8a8a; border-bottom: 1px dashed #d4cfc4;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 12px; margin: 24px 0;">
  <section style="flex: 1; border: 2px dashed #d4cfc4; border-radius: 6px; padding: 16px; text-align: center; background: #faf8f3;">
    <p style="font-size: 12px; color: #8a8a8a; margin: 0 0 8px;">传统开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #e8814a; margin: 0 0 4px;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #b0a890; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; border: 2px dashed #3d6ea5; border-radius: 6px; padding: 16px; text-align: center; background: #f5f1e8;">
    <p style="font-size: 12px; color: #8a8a8a; margin: 0 0 8px;">秒哒开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #3d6ea5; margin: 0 0 4px;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #b0a890; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0;">
  <p style="font-size: 12px; color: #8a8a8a; margin: 0 0 6px; font-family: 'Consolas',monospace;">✏️ Prompt</p>
  <section style="background: #2d2d2d; border-radius: 6px; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d4d4d4; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code># 角色设定
你是一个懂心理学的"反内耗闺蜜"

# 核心功能
1. 潜台词翻译
2. 高情商回怼文案
3. 情绪急救包</code></pre>
  </section>
</section>
```

### 普通代码块
```html
<section style="background: #2d2d2d; border-radius: 6px; padding: 16px; margin: 20px 0; overflow-x: auto;">
  <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d4d4d4; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code>100000 / 1688 * 1688</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0; text-align: center;">
  <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; border-radius: 6px; border: 2px dashed #d4cfc4; display: block; margin: 0 auto; padding: 4px;" />
  <p style="font-size: 13px; color: #b0a890; margin: 8px 0 0; font-style: italic;">图：秒哒主页 —— 「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="background: #f5f1e8; border-left: 3px dashed #e8814a; padding: 14px 20px; margin: 20px 0; border-radius: 0 6px 6px 0;">
  <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;"><strong style="color: #e8814a;">关键数据</strong>　传统开发成本2万元、耗时4个月；秒哒开发不到50元、不到1小时。</p>
</section>
```

### 实测体验
```html
<section style="background: #f5f1e8; border-left: 3px dashed #3d6ea5; padding: 14px 20px; margin: 20px 0; border-radius: 0 6px 6px 0;">
  <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;"><strong style="color: #3d6ea5;">实测体验</strong>　前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。</p>
</section>
```

### 收获标注
```html
<section style="background: #f5f1e8; border-left: 3px dashed #3d6ea5; padding: 14px 20px; margin: 20px 0; border-radius: 0 6px 6px 0;">
  <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;"><strong style="color: #3d6ea5;">收获：</strong>　验证了秒哒对个人工具类App的支撑能力。</p>
</section>
```

### 踩坑提示
```html
<section style="background: #fdf0ea; border-left: 3px dashed #e8814a; padding: 14px 20px; margin: 20px 0; border-radius: 0 6px 6px 0;">
  <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;"><strong style="color: #e8814a;">踩坑提醒</strong>　Windows 下路径有空格会导致安装失败。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 10px;">
    <span style="background: #3d6ea5; color: #fff; font-size: 12px; font-weight: 600; padding: 3px 12px; border-radius: 3px; letter-spacing: 1px;">STEP 1</span>
    <span style="font-size: 17px; font-weight: 600; color: #4a4a4a;">用自然语言描述你的需求</span>
  </section>
  <p style="font-size: 16px; line-height: 1.9; color: #4a4a4a; margin: 0; letter-spacing: 0.5px;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 26px; border-left: 2px dashed #c4bda8;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -32px; top: 4px; width: 10px; height: 10px; background: #3d6ea5; border-radius: 50%; border: 2px solid #faf8f3;"></span>
    <p style="font-size: 16px; color: #4a4a4a; margin: 0 0 4px; font-weight: 600;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #8a8a8a; margin: 0; line-height: 1.9;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -32px; top: 4px; width: 10px; height: 10px; background: #3d6ea5; border-radius: 50%; border: 2px solid #faf8f3;"></span>
    <p style="font-size: 16px; color: #4a4a4a; margin: 0 0 4px; font-weight: 600;">思考（Think）</p>
    <p style="font-size: 15px; color: #8a8a8a; margin: 0; line-height: 1.9;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -32px; top: 4px; width: 10px; height: 10px; background: #e8814a; border-radius: 50%; border: 2px solid #faf8f3;"></span>
    <p style="font-size: 16px; color: #4a4a4a; margin: 0 0 4px; font-weight: 600;">行动（Act）</p>
    <p style="font-size: 15px; color: #8a8a8a; margin: 0; line-height: 1.9;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; border: 2px dashed #d4cfc4; border-radius: 6px; padding: 20px; background: #faf8f3;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 8px;">
    <span style="background: #3d6ea5; color: #fff; font-size: 12px; font-weight: 600; padding: 3px 10px; border-radius: 3px;">CASE 01</span>
    <span style="font-size: 16px; font-weight: 600; color: #4a4a4a;">心情日记App</span>
  </section>
  <p style="font-size: 13px; color: #b0a890; margin: 0 0 12px;">个人工具 · 心理健康类</p>
  <p style="font-size: 16px; line-height: 1.9; color: #4a4a4a; margin: 0; letter-spacing: 0.5px;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 700; color: #3d6ea5; margin: 0 0 6px; font-family: 'Georgia',serif;">Level 1：Chatbot（纯对话）</p>
  <section style="background: #f5f1e8; border-left: 3px dashed #c4bda8; padding: 12px 18px; margin: 0 0 16px; border-radius: 0 6px 6px 0;">
    <p style="margin: 0; font-size: 15px; color: #5a5a5a; line-height: 1.9; letter-spacing: 0.5px;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 1.9; color: #4a4a4a; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.5px;">
  <li style="margin-bottom: 10px;"><strong style="color: #3d6ea5;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><strong style="color: #3d6ea5;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><strong style="color: #3d6ea5;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 1.9; color: #4a4a4a; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.5px;">
  <li style="margin-bottom: 10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线

```html
<section style="text-align: center; margin: 36px 0;">
  <span style="display: inline-block; width: 40px; border-top: 2px dashed #c4bda8;"></span>
  <span style="display: inline-block; margin: 0 8px; color: #c4bda8; font-size: 14px;">✦</span>
  <span style="display: inline-block; width: 40px; border-top: 2px dashed #c4bda8;"></span>
</section>
```

---

## 20. 下一篇预告

```html
<section style="text-align: center; margin: 28px 0; padding: 16px 20px; border: 2px dashed #3d6ea5; border-radius: 6px; background: #faf8f3;">
  <p style="font-size: 14px; color: #8a8a8a; margin: 0; line-height: 1.9;">下一篇我们聊 <strong style="color: #3d6ea5;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <span style="font-size: 18px; color: #c4bda8;">~</span>
  <span style="font-size: 14px; color: #c4bda8; margin: 0 6px; letter-spacing: 2px;">END</span>
  <span style="font-size: 18px; color: #c4bda8;">~</span>
</section>
```

---

## 22. 作者签名

```html
<section style="margin-top: 40px; padding-top: 24px; border-top: 2px dashed #c4bda8;">
  <p style="font-size: 15px; color: #4a4a4a; line-height: 2; margin: 0 0 8px; letter-spacing: 0.5px;">
    我是 <strong style="color: #3d6ea5;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #3d6ea5;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #8a8a8a; line-height: 2; margin: 0 0 10px; letter-spacing: 0.5px;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #4a4a4a; line-height: 2; margin: 0; letter-spacing: 0.5px;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #e8814a;">点赞、在看、转发</strong>三连，我们下篇见。
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
  <title>预览 - 手绘笔记风</title>
  <style>
    body { background: #e8e4dc; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #faf8f3; border-radius: 8px; overflow: hidden; border: 2px dashed #c4bda8; }
    .toolbar { padding: 12px 20px; background: #f5f1e8; border-bottom: 2px dashed #c4bda8; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #4a4a4a; }
    .toolbar button { background: #3d6ea5; color: #fff; border: none; padding: 6px 16px; border-radius: 4px; cursor: pointer; font-size: 13px; }
    .toolbar button:hover { background: #2c5d8e; }
    .content { padding: 20px 16px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>📖 手绘笔记风 · 宁的AI小站</span>
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
