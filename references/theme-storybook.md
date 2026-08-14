# 主题：枕边故事风 (storybook)

**调用名**：故事风 / storybook

温暖的叙事感，像一本睡前翻开的插画故事书。首字下沉、章节装饰框、双线书页边框。最适合把技术讲成故事的科普文。

## 设计令牌

```
米色底:     #fdf8ef  (书页暖米)
可可棕:     #5c4a3a  (正文主色)
故事橙:     #e07b39  (主强调)
鼠尾草绿:   #7a9b76  (辅助)
玫瑰粉:     #e8a0a0  (点缀)
金棕:       #c9a05a
浅米:       #f5eddc  (引用底)
边框:       #e0d3b8  (书页边)
代码底:     #3a3227  (暖黑)
圆角:       8px
字体:       标题 'Georgia','Noto Serif SC',serif / 正文 'Noto Serif SC',serif
核心特色:   章节装饰框(第一章)、首字下沉、双线书页框、✦❧装饰符号、温暖叙事
```

---

## 1. 标题区

```html
<section style="margin-bottom: 36px; text-align: center;">
  <p style="font-size: 20px; color: #c9a05a; margin: 0 0 10px;">✦ ❦ ✦</p>
  <p style="font-size: 12px; color: #b09a7a; letter-spacing: 3px; margin-bottom: 12px; font-family: 'Georgia',serif;">AI 基础设施科普 · 第五章</p>
  <h1 style="font-size: 25px; font-weight: 700; color: #5c4a3a; line-height: 1.5; margin: 0 0 12px; font-family: 'Georgia','Noto Serif SC',serif;">不只是"聊天机器人"</h1>
  <p style="font-size: 15px; color: #a08a70; margin: 0 0 14px; font-family: 'Noto Serif SC',serif; font-style: italic;">——AI Agent 到底是什么？</p>
  <p style="font-size: 13px; color: #b09a7a; margin: 0;">让 AI 从"只会说话"变成"会自己干活"</p>
</section>
```

---

## 2. 系列导语

```html
<section style="background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 18px 22px; margin: 0 0 28px; text-align: center;">
  <p style="font-size: 14px; color: #a08a70; margin: 0 0 6px; font-family: 'Georgia',serif;">— 前情提要 —</p>
  <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">本文是「AI 基础设施科普」系列第 <strong style="color: #e07b39;">5</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 20px; text-align: center;">
  <section style="display: inline-block; border: 2px solid #e07b39; border-radius: 8px; padding: 8px 24px;">
    <p style="font-size: 13px; color: #e07b39; margin: 0 0 2px; font-family: 'Georgia',serif; letter-spacing: 2px;">第一章</p>
    <h2 style="font-size: 18px; font-weight: 700; color: #5c4a3a; margin: 0; line-height: 1.5; font-family: 'Georgia','Noto Serif SC',serif;">Chatbot 和 Agent 有什么区别？</h2>
  </section>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 700; color: #e07b39; margin: 28px 0 12px; font-family: 'Georgia','Noto Serif SC',serif; text-align: center;">❧ 一个真实例子 ❧</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 2; color: #5c4a3a; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

首段首字下沉版：

```html
<p style="font-size: 16px; line-height: 2; color: #5c4a3a; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><span style="float: left; font-size: 48px; line-height: 1; font-weight: 700; color: #e07b39; margin: 4px 10px 0 0; font-family: 'Georgia','Noto Serif SC',serif;">你</span>可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<section style="margin: 0 0 22px; text-align: center;">
  <p style="font-size: 18px; line-height: 2; color: #e07b39; margin: 0; font-weight: 700; font-family: 'Georgia','Noto Serif SC',serif;"><strong>Chatbot 只能"说话"，Agent 能"做事。"</strong></p>
</section>
```

行内高亮：

```html
<span style="color: #e07b39; font-weight: 600; border-bottom: 2px dotted #e07b39;">关键文字</span>
```

---

## 7. 类比引用块（书页双线框）

```html
<section style="background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 4px; margin: 0 0 22px;">
  <section style="border: 1px dashed #e0d3b8; border-radius: 6px; padding: 14px 18px;">
    <p style="margin: 0 0 6px; font-size: 13px; color: #c9a05a; text-align: center; font-family: 'Georgia',serif;">❦ 打个比方 ❦</p>
    <p style="margin: 0 0 12px; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
    <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜。</p>
  </section>
</section>
```

---

## 8. 金句引用块

```html
<section style="margin: 28px 0; text-align: center; padding: 0 16px;">
  <p style="font-size: 24px; color: #c9a05a; margin: 0 0 8px;">❦</p>
  <p style="margin: 0 0 10px; font-size: 18px; color: #5c4a3a; line-height: 2; font-weight: 700; font-family: 'Georgia','Noto Serif SC',serif;"><strong>Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</strong></p>
  <p style="margin: 0; font-size: 14px; color: #a08a70; line-height: 2; font-family: 'Noto Serif SC',serif;">它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px; font-family: 'Noto Serif SC',serif;">
    <thead>
      <tr>
        <th style="padding: 11px 12px; text-align: center; color: #fdf8ef; font-weight: 700; background: #7a9b76; border-radius: 8px 0 0 0;">维度</th>
        <th style="padding: 11px 12px; text-align: center; color: #fdf8ef; font-weight: 700; background: #7a9b76;">Chatbot</th>
        <th style="padding: 11px 12px; text-align: center; color: #fdf8ef; font-weight: 700; background: #7a9b76; border-radius: 0 8px 0 0;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #5c4a3a; font-weight: 700; background: #f5eddc; border-bottom: 1px solid #e0d3b8;">交互方式</td>
        <td style="padding: 10px 12px; text-align: center; color: #a08a70; border-bottom: 1px solid #e0d3b8;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; text-align: center; color: #a08a70; border-bottom: 1px solid #e0d3b8;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #5c4a3a; font-weight: 700; background: #f5eddc;">工具使用</td>
        <td style="padding: 10px 12px; text-align: center; color: #a08a70;">不能调用外部工具</td>
        <td style="padding: 10px 12px; text-align: center; color: #a08a70;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 12px; margin: 24px 0;">
  <section style="flex: 1; background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #a08a70; margin: 0 0 8px;">传统开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #e8a0a0; margin: 0 0 4px;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #b09a7a; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; background: #f5eddc; border: 2px solid #7a9b76; border-radius: 8px; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #a08a70; margin: 0 0 8px;">秒哒开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #7a9b76; margin: 0 0 4px;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #b09a7a; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0;">
  <p style="font-size: 12px; color: #b09a7a; margin: 0 0 6px; text-align: center; font-family: 'Georgia',serif;">— Prompt 卷轴 —</p>
  <section style="background: #3a3227; border-radius: 8px; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e8dcc8; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code># 角色设定
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
<section style="background: #3a3227; border-radius: 8px; padding: 16px; margin: 20px 0; overflow-x: auto;">
  <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e8dcc8; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code>100000 / 1688 * 1688</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0; text-align: center;">
  <section style="display: inline-block; border: 2px solid #e0d3b8; border-radius: 8px; padding: 6px; background: #fff;">
    <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; border-radius: 4px; display: block;" />
  </section>
  <p style="font-size: 13px; color: #b09a7a; margin: 8px 0 0; font-style: italic;">图：秒哒主页 —— 「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="background: #f5eddc; border-left: 4px solid #e8a0a0; border-radius: 0 8px 8px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #e07b39;">关键数据</strong>　传统开发成本2万元、耗时4个月；秒哒不到50元、不到1小时。</p>
</section>
```

### 实测体验
```html
<section style="background: #f5eddc; border-left: 4px solid #7a9b76; border-radius: 0 8px 8px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #7a9b76;">实测体验</strong>　前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。</p>
</section>
```

### 收获标注
```html
<section style="background: #f5eddc; border-left: 4px solid #c9a05a; border-radius: 0 8px 8px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #c9a05a;">收获：</strong>　验证了秒哒对个人工具类App的支撑能力。</p>
</section>
```

### 踩坑提示
```html
<section style="background: #f5eddc; border-left: 4px solid #e8a0a0; border-radius: 0 8px 8px 0; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #e8a0a0;">踩坑提醒</strong>　Windows 下路径有空格会导致安装失败。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="text-align: center; margin-bottom: 12px;">
    <span style="display: inline-block; background: #e07b39; color: #fdf8ef; font-size: 13px; font-weight: 700; padding: 4px 18px; border-radius: 20px; font-family: 'Georgia',serif; letter-spacing: 1px;">第一步</span>
  </section>
  <p style="font-size: 17px; font-weight: 700; color: #5c4a3a; text-align: center; margin: 0 0 12px; font-family: 'Georgia','Noto Serif SC',serif;">用自然语言描述你的需求</p>
  <p style="font-size: 16px; line-height: 2; color: #5c4a3a; margin: 0; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 28px; border-left: 2px dashed #e0d3b8;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 24px; height: 24px; background: #7a9b76; color: #fdf8ef; font-size: 12px; font-weight: 700; border-radius: 50%;">壹</span>
    <p style="font-size: 16px; color: #5c4a3a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #a08a70; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 24px; height: 24px; background: #c9a05a; color: #fdf8ef; font-size: 12px; font-weight: 700; border-radius: 50%;">贰</span>
    <p style="font-size: 16px; color: #5c4a3a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">思考（Think）</p>
    <p style="font-size: 15px; color: #a08a70; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -37px; top: 0; display: inline-flex; align-items: center; justify-content: center; width: 24px; height: 24px; background: #e07b39; color: #fdf8ef; font-size: 12px; font-weight: 700; border-radius: 50%;">叁</span>
    <p style="font-size: 16px; color: #5c4a3a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">行动（Act）</p>
    <p style="font-size: 15px; color: #a08a70; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 4px;">
  <section style="border: 1px dashed #e0d3b8; border-radius: 6px; padding: 18px;">
    <p style="font-size: 13px; color: #c9a05a; margin: 0 0 6px; text-align: center; font-family: 'Georgia',serif;">❦ 第一个故事 ❦</p>
    <p style="font-size: 17px; font-weight: 700; color: #5c4a3a; margin: 0 0 4px; text-align: center; font-family: 'Georgia','Noto Serif SC',serif;">心情日记App</p>
    <p style="font-size: 13px; color: #b09a7a; margin: 0 0 12px; text-align: center;">个人工具 · 心理健康类</p>
    <p style="font-size: 16px; line-height: 2; color: #5c4a3a; margin: 0; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
  </section>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 700; color: #7a9b76; margin: 0 0 6px; font-family: 'Georgia','Noto Serif SC',serif;">第一站 · Chatbot（纯对话）</p>
  <section style="background: #f5eddc; border-left: 4px solid #e0d3b8; border-radius: 0 8px 8px 0; padding: 12px 18px; margin: 0 0 16px;">
    <p style="margin: 0; font-size: 15px; color: #5c4a3a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 2; color: #5c4a3a; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif; list-style: none;">
  <li style="margin-bottom: 10px;"><span style="color: #c9a05a; margin-right: 8px;">✦</span><strong style="color: #e07b39;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><span style="color: #c9a05a; margin-right: 8px;">✦</span><strong style="color: #e07b39;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><span style="color: #c9a05a; margin-right: 8px;">✦</span><strong style="color: #e07b39;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 2; color: #5c4a3a; padding-left: 24px; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">
  <li style="margin-bottom: 10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线（故事书花饰）

```html
<section style="text-align: center; margin: 36px 0;">
  <span style="color: #c9a05a; font-size: 16px; letter-spacing: 8px;">✦ ❦ ✦</span>
</section>
```

---

## 20. 下一篇预告

```html
<section style="margin: 28px 0; background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 18px 22px; text-align: center;">
  <p style="font-size: 13px; color: #c9a05a; letter-spacing: 2px; margin: 0 0 6px; font-family: 'Georgia',serif;">❦ 第六章预告 ❦</p>
  <p style="font-size: 15px; color: #5c4a3a; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">下一篇我们聊 <strong style="color: #e07b39;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <p style="font-size: 15px; color: #c9a05a; margin: 0; letter-spacing: 4px; font-family: 'Georgia',serif;">— 故事未完 —</p>
  <p style="font-size: 12px; color: #b09a7a; margin: 6px 0 0; font-style: italic;">to be continued…</p>
</section>
```

---

## 22. 作者签名

```html
<section style="margin-top: 40px; background: #f5eddc; border: 2px solid #e0d3b8; border-radius: 8px; padding: 22px; text-align: center;">
  <p style="font-size: 14px; color: #c9a05a; margin: 0 0 12px; font-family: 'Georgia',serif;">— 讲故事的人 —</p>
  <p style="font-size: 15px; color: #5c4a3a; line-height: 2; margin: 0 0 8px; font-family: 'Noto Serif SC',serif;">
    我是 <strong style="color: #e07b39;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #e07b39;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #a08a70; line-height: 2; margin: 0 0 10px; font-family: 'Noto Serif SC',serif;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #5c4a3a; line-height: 2; margin: 0; font-family: 'Noto Serif SC',serif;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #e07b39;">点赞、在看、转发</strong>三连，我们下篇见。
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
  <title>预览 - 枕边故事风</title>
  <style>
    body { background: #e8dcc8; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #fdf8ef; border-radius: 8px; overflow: hidden; border: 1px solid #d8c8a8; }
    .toolbar { padding: 12px 20px; background: #5c4a3a; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #fdf8ef; font-family: Georgia,serif; }
    .toolbar button { background: #e07b39; color: #fff; border: none; padding: 6px 16px; border-radius: 20px; cursor: pointer; font-size: 13px; }
    .toolbar button:hover { background: #c96a2e; }
    .content { padding: 24px 20px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>❦ STORYBOOK · 枕边故事风 · 宁的AI小站</span>
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
