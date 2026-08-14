# 主题：活动宣发风 (launch)

**调用名**：宣发风 / launch

活动海报感，高对比蓝黄配色，徽章 + 胶囊 CTA + 海报卡。最适合线下 Meetup、Workshop、产品发布、活动预告类推文。触发词："宣发""活动""launch""预告"。

## 设计令牌

```
深蓝主色:   #1E40AF  (标题/徽章/海报卡底)
亮黄高亮:   #F4E94B  (荧光笔/重音符/CTA点缀)
正黑:       #1A1A1A  (正文/代码块底)
奶油底:     #F8F4EA  (页面背景)
浅奶油:     #FAF7EE  (引用/卡片底)
边框米:     #ECE6D3  (表格分隔/卡片边)
副蓝:       #3B6FD4  (副标题)
圆角:       12px(卡片) / 4px(徽章) / 30px(胶囊CTA)
字体:       系统无衬线 -apple-system,'PingFang SC','Microsoft YaHei',sans-serif
核心特色:   活动预告徽章、日期标签、蓝色方块编号、黑底黄字现场快报、蓝黄海报卡、胶囊CTA
```

---

## 1. 标题区（活动预告）

```html
<section style="margin-bottom:36px;">
  <section style="display:flex;align-items:center;gap:10px;margin-bottom:18px;">
    <span style="display:inline-block;background:#1E40AF;color:#FFFFFF;font-size:12px;padding:5px 14px;border-radius:4px;font-weight:700;letter-spacing:1px;">活动预告</span>
    <span style="display:inline-block;background:#FFFFFF;color:#1E40AF;font-size:12px;padding:5px 14px;border:1.5px solid #1E40AF;border-radius:4px;font-weight:700;letter-spacing:1px;">2026.08.22</span>
  </section>
  <h1 style="font-size:28px;font-weight:900;color:#1E40AF;line-height:1.35;margin:0 0 10px;letter-spacing:-.5px;">宁的AI小站 · 线下 Meetup 第 1 期</h1>
  <p style="font-size:15px;color:#3B6FD4;margin:0 0 14px;font-weight:600;">——和 GoodTime 面对面聊 Agent 实战</p>
  <section style="height:4px;width:60px;background:#1E40AF;"></section>
</section>
```

---

## 2. 系列导语 → 活动速览

```html
<section style="background:#1E40AF;color:#FFFFFF;border-radius:12px;padding:22px 26px;margin:0 0 28px;box-shadow:0 8px 24px rgba(30,64,175,.25);">
  <p style="font-size:13px;letter-spacing:2px;color:#F4E94B;font-weight:700;margin:0 0 10px;">— 活动速览 —</p>
  <p style="margin:0;font-size:15px;color:#FFFFFF;line-height:1.9;">本期 Meetup 聚焦 AI Agent 从概念到落地：半天时间，3 场实战分享 + 1 次现场结对开发。无论你是刚入门还是已经在用 Agent 提效，都能带走可复用的经验。</p>
</section>
```

---

## 3. 章节标题（蓝色方块编号）

```html
<section style="margin:40px 0 18px;">
  <section style="display:flex;align-items:center;gap:14px;">
    <span style="display:inline-flex;align-items:center;justify-content:center;min-width:40px;height:40px;background:#1E40AF;color:#FFFFFF;font-size:16px;font-weight:800;border-radius:8px;padding:0 10px;flex-shrink:0;">一</span>
    <h2 style="font-size:19px;font-weight:800;color:#1A1A1A;margin:0;line-height:1.4;">这次 Meetup 能带给你什么？</h2>
  </section>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size:17px;font-weight:700;color:#1E40AF;margin:28px 0 12px;padding-left:12px;border-left:4px solid #F4E94B;">一个真实例子</h3>
```

---

## 5. 正文段落

```html
<p style="font-size:16px;line-height:1.9;color:#1A1A1A;margin:0 0 22px;letter-spacing:.3px;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断（荧光笔高亮）

```html
<section style="margin:0 0 22px;">
  <p style="font-size:18px;line-height:1.9;color:#1A1A1A;margin:0;font-weight:800;"><span style="background:linear-gradient(180deg,transparent 60%,#F4E94B 60%);padding:0 2px;">Chatbot 只能"说话"，Agent 能"做事"。</span></p>
</section>
```

行内高亮：

```html
<span style="background:linear-gradient(180deg,transparent 60%,#F4E94B 60%);padding:0 2px;font-weight:700;">关键文字</span>
```

---

## 7. 类比引用块 → 现场快报（黑底黄字）

```html
<section style="background:#1A1A1A;color:#F4E94B;border-radius:12px;padding:22px 26px;margin:24px 0;box-shadow:0 4px 16px rgba(0,0,0,.18);">
  <p style="font-size:13px;letter-spacing:2px;color:#F4E94B;font-weight:700;margin:0 0 10px;">— 现场快报 —</p>
  <p style="margin:0;font-size:17px;color:#F4E94B;line-height:1.9;font-weight:700;">你去餐厅，Chatbot 像只会念菜单的服务员；Agent 像真正的餐厅经理——你给目标，他自己安排到底。</p>
</section>
```

---

## 8. 金句引用块（蓝条浅底）

```html
<section style="margin:28px 0;border-left:4px solid #1E40AF;background:#FAF7EE;border-radius:0 12px 12px 0;padding:18px 22px;">
  <p style="margin:0 0 8px;font-size:18px;color:#1E40AF;line-height:1.7;font-weight:800;">Agent 是 AI 的"嘴 + 手 + 脑"。</p>
  <p style="margin:0;font-size:14px;color:#1A1A1A;line-height:1.9;">它不只是能聊天，而是能自己感知、规划、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin:24px 0;overflow-x:auto;">
  <table style="width:100%;border-collapse:collapse;font-size:14px;border-radius:8px;overflow:hidden;">
    <thead>
      <tr>
        <th style="padding:12px;text-align:center;color:#FFFFFF;font-weight:700;background:#1E40AF;letter-spacing:1px;">维度</th>
        <th style="padding:12px;text-align:center;color:#FFFFFF;font-weight:700;background:#1E40AF;">线下 Meetup</th>
        <th style="padding:12px;text-align:center;color:#FFFFFF;font-weight:700;background:#1E40AF;">纯看文章</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;font-weight:700;background:#FFFFFF;border-bottom:1px solid #ECE6D3;">互动</td>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;background:#FAF7EE;border-bottom:1px solid #ECE6D3;">现场提问、结对开发</td>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;background:#FFFFFF;border-bottom:1px solid #ECE6D3;">单向阅读</td>
      </tr>
      <tr>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;font-weight:700;background:#FFFFFF;">留存</td>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;background:#FAF7EE;">认识同行、加群持续学</td>
        <td style="padding:10px 12px;text-align:center;color:#1A1A1A;background:#FFFFFF;">易看完即忘</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display:flex;gap:12px;margin:24px 0;">
  <section style="flex:1;background:#FFFFFF;border:2px solid #ECE6D3;border-top:4px solid #1E40AF;border-radius:0 0 12px 12px;padding:18px;text-align:center;">
    <p style="font-size:12px;color:#3B6FD4;margin:0 0 8px;">传统方式</p>
    <p style="font-size:18px;font-weight:800;color:#1A1A1A;margin:0 0 4px;">2万+ / 4个月</p>
    <p style="font-size:13px;color:#666;margin:0;">需技术团队</p>
  </section>
  <section style="flex:1;background:#1E40AF;border-radius:12px;padding:18px;text-align:center;box-shadow:0 4px 12px rgba(30,64,175,.25);">
    <p style="font-size:12px;color:#F4E94B;margin:0 0 8px;">用 Agent</p>
    <p style="font-size:18px;font-weight:800;color:#FFFFFF;margin:0 0 4px;">&lt;50元 / &lt;1小时</p>
    <p style="font-size:13px;color:rgba(255,255,255,.85);margin:0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块（深色）

```html
<section style="background:#1A1A1E;border-radius:12px;padding:16px;margin:20px 0;overflow-x:auto;">
  <pre style="margin:0;font-size:13px;line-height:1.7;color:#E0E0E0;font-family:Consolas,Monaco,monospace;white-space:pre-wrap;word-wrap:break-word;"><code># 角色设定
你是一个"反内耗闺蜜"

# 核心功能
1. 潜台词翻译
2. 高情商回怼
3. 情绪急救包</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin:32px 0;text-align:center;">
  <img src="IMAGE_URL" alt="活动主视觉" style="max-width:100%;border-radius:12px;display:block;margin:0 auto;border:4px solid #FFFFFF;box-shadow:0 8px 32px rgba(0,0,0,.18);" />
  <p style="font-size:13px;color:#1E40AF;margin:12px 0 0;font-weight:600;letter-spacing:1px;">图：活动主视觉 —— 替换成你的海报</p>
</section>
```

---

## 13. 提示标注块

### 关键数据（蓝条）
```html
<section style="background:#FAF7EE;border-left:4px solid #1E40AF;border-radius:0 12px 12px 0;padding:14px 20px;margin:20px 0;">
  <p style="margin:0;font-size:15px;color:#1A1A1A;line-height:1.9;"><strong style="color:#1E40AF;">关键数据</strong>　本期限额 50 人，现场 3 场分享 + 1 次结对开发。</p>
</section>
```

### 实测体验（黄条）
```html
<section style="background:#FAF7EE;border-left:4px solid #F4E94B;border-radius:0 12px 12px 0;padding:14px 20px;margin:20px 0;">
  <p style="margin:0;font-size:15px;color:#1A1A1A;line-height:1.9;"><strong style="color:#1A1A1A;">实测体验</strong>　上期线上版 40 分钟讲完，线下预计能多留 1 小时答疑。</p>
</section>
```

### 收获标注（蓝边）
```html
<section style="background:#FAF7EE;border-left:4px solid #3B6FD4;border-radius:0 12px 12px 0;padding:14px 20px;margin:20px 0;">
  <p style="margin:0;font-size:15px;color:#1A1A1A;line-height:1.9;"><strong style="color:#3B6FD4;">收获：</strong>　带来一套可直接复用的 Agent 实战工作流。</p>
</section>
```

### 踩坑提醒（黑条）
```html
<section style="background:#FAF7EE;border-left:4px solid #1A1A1A;border-radius:0 12px 12px 0;padding:14px 20px;margin:20px 0;">
  <p style="margin:0;font-size:15px;color:#1A1A1A;line-height:1.9;"><strong style="color:#1A1A1A;">踩坑提醒</strong>　报名后请加群，场地变更只在群里通知。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin:28px 0 22px;">
  <section style="text-align:center;margin-bottom:12px;">
    <span style="display:inline-block;background:#1E40AF;color:#FFFFFF;font-size:13px;font-weight:700;padding:4px 18px;border-radius:20px;letter-spacing:1px;">第一步</span>
  </section>
  <p style="font-size:17px;font-weight:800;color:#1A1A1A;text-align:center;margin:0 0 12px;">用自然语言描述你的需求</p>
  <p style="font-size:16px;line-height:1.9;color:#1A1A1A;margin:0;text-align:center;">进报名页选票种，大白话把想解决的问题说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin:24px 0;padding-left:28px;border-left:2px dashed #ECE6D3;">
  <section style="margin-bottom:22px;position:relative;">
    <span style="position:absolute;left:-37px;top:0;display:inline-flex;align-items:center;justify-content:center;width:24px;height:24px;background:#1E40AF;color:#FFFFFF;font-size:12px;font-weight:700;border-radius:50%;">1</span>
    <p style="font-size:16px;color:#1A1A1A;margin:0 0 4px;font-weight:800;">13:30 签到</p>
    <p style="font-size:15px;color:#666;margin:0;line-height:1.9;">领取物料，自由交流</p>
  </section>
  <section style="margin-bottom:22px;position:relative;">
    <span style="position:absolute;left:-37px;top:0;display:inline-flex;align-items:center;justify-content:center;width:24px;height:24px;background:#F4E94B;color:#1A1A1A;font-size:12px;font-weight:700;border-radius:50%;">2</span>
    <p style="font-size:16px;color:#1A1A1A;margin:0 0 4px;font-weight:800;">14:00 主题分享</p>
    <p style="font-size:15px;color:#666;margin:0;line-height:1.9;">3 场 Agent 实战拆解</p>
  </section>
  <section style="position:relative;">
    <span style="position:absolute;left:-37px;top:0;display:inline-flex;align-items:center;justify-content:center;width:24px;height:24px;background:#1A1A1A;color:#F4E94B;font-size:12px;font-weight:700;border-radius:50%;">3</span>
    <p style="font-size:16px;color:#1A1A1A;margin:0 0 4px;font-weight:800;">16:30 结对开发</p>
    <p style="font-size:15px;color:#666;margin:0;line-height:1.9;">现场组队，把想法做出 Demo</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin:28px 0;background:#FAF7EE;border:2px solid #ECE6D3;border-radius:12px;padding:4px;">
  <section style="border:1px dashed #ECE6D3;border-radius:10px;padding:18px;text-align:center;">
    <p style="font-size:13px;color:#1E40AF;margin:0 0 6px;font-weight:700;letter-spacing:1px;">— 往期案例 —</p>
    <p style="font-size:17px;font-weight:800;color:#1A1A1A;margin:0 0 4px;">心情日记 App</p>
    <p style="font-size:13px;color:#666;margin:0 0 12px;">个人工具 · 心理健康类</p>
    <p style="font-size:16px;line-height:1.9;color:#1A1A1A;margin:0;">核心功能：每天记心情、emoji 打分、看历史趋势图、支持照片。</p>
  </section>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin:20px 0;">
  <p style="font-size:16px;font-weight:800;color:#1E40AF;margin:0 0 6px;">第一站 · Chatbot（纯对话）</p>
  <section style="background:#FAF7EE;border-left:4px solid #1E40AF;border-radius:0 12px 12px 0;padding:12px 18px;margin:0 0 16px;">
    <p style="margin:0;font-size:15px;color:#1A1A1A;line-height:1.9;">只能文字交互，你说一句它回一句。早期 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size:16px;line-height:1.9;color:#1A1A1A;padding-left:22px;margin:0 0 22px;letter-spacing:.3px;list-style:none;">
  <li style="margin-bottom:10px;"><span style="color:#1E40AF;margin-right:8px;">▪</span><strong style="color:#1E40AF;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom:10px;"><span style="color:#F4E94B;margin-right:8px;">▪</span><strong style="color:#1A1A1A;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom:0;"><span style="color:#1E40AF;margin-right:8px;">▪</span><strong style="color:#1E40AF;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size:16px;line-height:1.9;color:#1A1A1A;padding-left:24px;margin:0 0 22px;letter-spacing:.3px;">
  <li style="margin-bottom:10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom:10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom:0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线

```html
<section style="text-align:center;margin:36px 0;">
  <span style="display:inline-block;width:60px;height:3px;background:#1A1A1A;"></span>
</section>
```

---

## 20. 下一篇预告（蓝卡）

```html
<section style="margin:28px 0;background:#1E40AF;border-radius:12px;padding:18px 22px;text-align:center;box-shadow:0 4px 12px rgba(30,64,175,.25);">
  <p style="font-size:13px;color:#F4E94B;letter-spacing:2px;margin:0 0 6px;font-weight:700;">— 下期预告 —</p>
  <p style="font-size:15px;color:#FFFFFF;margin:0;line-height:1.9;">下一篇我们聊 <strong style="color:#F4E94B;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align:center;margin:36px 0 20px;">
  <p style="font-size:14px;color:#1E40AF;margin:0;letter-spacing:4px;font-weight:700;">— 活动未完 —</p>
</section>
```

---

## 22. 作者签名（胶囊 CTA + 蓝卡）

```html
<section style="text-align:center;margin:40px 0 24px;">
  <section style="display:inline-block;background:#1E40AF;color:#FFFFFF;padding:10px 36px;border-radius:30px;font-size:14px;font-weight:700;letter-spacing:2px;box-shadow:0 4px 12px rgba(30,64,175,.3);">8月22日 · 不见不散</section>
</section>
<section style="margin-top:32px;background:#1E40AF;color:#FFFFFF;border-radius:16px;padding:28px 30px;box-shadow:0 8px 24px rgba(30,64,175,.25);">
  <p style="font-size:15px;color:#FFFFFF;line-height:2;margin:0 0 8px;">我是 <strong style="color:#F4E94B;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color:#F4E94B;">【宁的AI小站】</strong>——用技术让AI更实用。</p>
  <p style="font-size:14px;color:rgba(255,255,255,.85);line-height:2;margin:0 0 10px;">点击主页加群或者私信加群一起学习AI。</p>
  <p style="font-size:15px;color:#FFFFFF;line-height:2;margin:0;">如果你觉得今天这篇有收获，欢迎<strong style="color:#F4E94B;">点赞、在看、转发</strong>三连，我们下篇见。</p>
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
  <title>预览 - 活动宣发风</title>
  <style>
    body { background: #ECE6D3; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #F8F4EA; border-radius: 12px; overflow: hidden; border: 1px solid #D8D0BC; }
    .toolbar { padding: 12px 20px; background: #1E40AF; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #FFFFFF; font-family: -apple-system,'PingFang SC',sans-serif; }
    .toolbar button { background: #F4E94B; color: #1A1A1A; border: none; padding: 6px 16px; border-radius: 20px; cursor: pointer; font-size: 13px; font-weight: 700; }
    .toolbar button:hover { background: #E0D43E; }
    .content { padding: 24px 20px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>LAUNCH · 活动宣发风 · 宁的AI小站</span>
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
