# 主题：代码极客风 (geek)

终端美学、暗色代码块、> 提示符、monospace 标签。像AI博主的命令行——技术感拉满。

## 设计令牌

```
背景色:     #0d1117  (深色底，仅用于代码区/标签)
正文背景:   #ffffff
主色:       #0969da  (GitHub蓝)
强调色:     #1a7f37  (终端绿)
辅助色:     #8250df  (紫色)
墨色:       #24292f
次要色:     #636c76
浅灰:       #f6f8fa
边框色:     #d0d7de
引用底:     #f6f8fa
代码底:     #0d1117
代码文字:   #e6edf3
圆角:       6px
边框风格:   1px solid #d0d7de
字体:       正文 -apple-system,sans-serif / 标签 'Cascadia Code','Consolas',monospace
装饰:       > 提示符，// 注释风格，$ 命令行符，{ } 方括号
```

---

## 1. 标题区

```html
<section style="margin-bottom: 36px;">
  <p style="font-size: 12px; color: #636c76; margin-bottom: 12px; font-family: 'Cascadia Code','Consolas',monospace;">// AI_基础设施科普 / ep.05</p>
  <h1 style="font-size: 24px; font-weight: 800; color: #24292f; line-height: 1.4; margin: 0 0 8px;">不只是"聊天机器人"</h1>
  <p style="font-size: 15px; color: #0969da; margin: 0 0 12px; font-family: 'Cascadia Code','Consolas',monospace;">$ AI Agent --what-is-it</p>
  <p style="font-size: 14px; color: #636c76; margin: 0;">&gt; 让 AI 从"只会说话"变成"会自己干活"</p>
</section>
```

---

## 2. 系列导语

```html
<section style="background: #f6f8fa; border-left: 3px solid #0969da; padding: 14px 18px; margin: 0 0 28px; border-radius: 0 6px 6px 0;">
  <p style="margin: 0; font-size: 13px; color: #636c76; font-family: 'Cascadia Code','Consolas',monospace; margin-bottom: 6px;">README.md</p>
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">本文是「AI 基础设施科普」系列第 <strong style="color: #0969da;">5</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"——这个转变的核心，就是 Agent。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 18px;">
  <h2 style="font-size: 19px; font-weight: 700; color: #24292f; margin: 0; line-height: 1.5;">
    <span style="color: #8250df; font-family: 'Cascadia Code','Consolas',monospace; font-size: 16px; margin-right: 8px;">##</span>一、Chatbot 和 Agent 有什么区别？
  </h2>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 600; color: #0969da; margin: 28px 0 12px;">
  <span style="font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px;">###</span>一个真实例子
</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 1.9; color: #24292f; margin: 0 0 22px; letter-spacing: 0.3px;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<section style="background: #f6f8fa; border-radius: 6px; padding: 12px 16px; margin: 0 0 22px; border-left: 3px solid #1a7f37;">
  <p style="margin: 0; font-size: 16px; line-height: 1.9; color: #1a7f37; font-weight: 700;">
    <span style="font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px;">&gt;</span><strong>Chatbot 只能"说话"，Agent 能"做事。"</strong>
  </p>
</section>
```

行内高亮：
```html
<span style="color: #cf222e; font-weight: 600;">关键文字</span>
```

---

## 7. 类比引用块

```html
<section style="background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 6px; padding: 16px 18px; margin: 0 0 22px;">
  <p style="margin: 0 0 6px; font-size: 12px; color: #636c76; font-family: 'Cascadia Code','Consolas',monospace;">// 生活类比</p>
  <p style="margin: 0 0 12px; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜。</p>
</section>
```

---

## 8. 金句引用块

```html
<section style="background: #0d1117; border-radius: 6px; padding: 18px 20px; margin: 24px 0;">
  <p style="margin: 0 0 6px; font-size: 12px; color: #1a7f37; font-family: 'Cascadia Code','Consolas',monospace;">// key takeaway</p>
  <p style="margin: 0; font-size: 16px; color: #e6edf3; line-height: 1.9; font-weight: 600;"><strong>Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</strong></p>
  <p style="margin: 6px 0 0; font-size: 14px; color: #8b949e; line-height: 1.9;">它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px; border: 1px solid #d0d7de; border-radius: 6px; overflow: hidden;">
    <thead>
      <tr style="background: #f6f8fa;">
        <th style="padding: 10px 12px; text-align: left; color: #24292f; font-weight: 700; border-bottom: 1px solid #d0d7de; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">dimension</th>
        <th style="padding: 10px 12px; text-align: left; color: #24292f; font-weight: 700; border-bottom: 1px solid #d0d7de; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">Chatbot</th>
        <th style="padding: 10px 12px; text-align: left; color: #24292f; font-weight: 700; border-bottom: 1px solid #d0d7de; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; color: #24292f; font-weight: 600; border-bottom: 1px solid #d0d7de;">交互方式</td>
        <td style="padding: 10px 12px; color: #636c76; border-bottom: 1px solid #d0d7de;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; color: #636c76; border-bottom: 1px solid #d0d7de;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; color: #24292f; font-weight: 600;">工具使用</td>
        <td style="padding: 10px 12px; color: #636c76;">不能调用外部工具</td>
        <td style="padding: 10px 12px; color: #636c76;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 12px; margin: 24px 0;">
  <section style="flex: 1; border: 1px solid #d0d7de; border-radius: 6px; padding: 16px; text-align: center;">
    <p style="font-size: 12px; color: #636c76; margin: 0 0 8px; font-family: 'Cascadia Code','Consolas',monospace;">// traditional</p>
    <p style="font-size: 20px; font-weight: 800; color: #cf222e; margin: 0 0 4px;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #8b949e; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; border: 1px solid #1a7f37; border-radius: 6px; padding: 16px; text-align: center; background: #dafbe4;">
    <p style="font-size: 12px; color: #1a7f37; margin: 0 0 8px; font-family: 'Cascadia Code','Consolas',monospace;">// miaData</p>
    <p style="font-size: 20px; font-weight: 800; color: #1a7f37; margin: 0 0 4px;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #636c76; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0; border-radius: 6px; overflow: hidden; border: 1px solid #d0d7de;">
  <section style="background: #f6f8fa; padding: 8px 16px; border-bottom: 1px solid #d0d7de; display: flex; align-items: center; gap: 8px;">
    <span style="display: inline-block; width: 10px; height: 10px; background: #ff5f56; border-radius: 50%;"></span>
    <span style="display: inline-block; width: 10px; height: 10px; background: #ffbd2e; border-radius: 50%;"></span>
    <span style="display: inline-block; width: 10px; height: 10px; background: #27c93f; border-radius: 50%;"></span>
    <span style="font-size: 12px; color: #636c76; margin-left: 8px; font-family: 'Cascadia Code','Consolas',monospace;">prompt.txt — Prompt</span>
  </section>
  <section style="background: #0d1117; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e6edf3; font-family: 'Cascadia Code','Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code><span style="color: #8b949e;"># 角色设定</span>
你是一个"反内耗闺蜜"

<span style="color: #8b949e;"># 核心功能</span>
1. 潜台词翻译
2. 高情商回怼
3. 情绪急救包</code></pre>
  </section>
</section>
```

### 普通代码块
```html
<section style="margin: 20px 0; border-radius: 6px; overflow: hidden; border: 1px solid #d0d7de;">
  <section style="background: #0d1117; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #e6edf3; font-family: 'Cascadia Code','Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code><span style="color: #1a7f37;">$</span> 100000 / 1688 * 1688</code></pre>
  </section>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0; text-align: center;">
  <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; border-radius: 6px; display: block; margin: 0 auto; border: 1px solid #d0d7de;" />
  <p style="font-size: 13px; color: #636c76; margin: 8px 0 0; font-family: 'Cascadia Code','Consolas',monospace;">// 图：秒哒主页 —— 「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="background: #fff1f0; border: 1px solid #ffa39e; border-radius: 6px; padding: 14px 18px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">
    <span style="color: #cf222e; font-weight: 700; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">[ERROR]</span> <strong style="color: #cf222e;">关键数据</strong>　传统开发成本2万元、耗时4个月；秒哒不到50元、不到1小时。
  </p>
</section>
```

### 实测体验
```html
<section style="background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 6px; padding: 14px 18px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">
    <span style="color: #0969da; font-weight: 700; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">[INFO]</span> <strong style="color: #0969da;">实测体验</strong>　前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。
  </p>
</section>
```

### 收获标注
```html
<section style="background: #dafbe4; border: 1px solid #aceebb; border-radius: 6px; padding: 14px 18px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">
    <span style="color: #1a7f37; font-weight: 700; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">[SUCCESS]</span> <strong style="color: #1a7f37;">收获：</strong>　验证了秒哒对个人工具类App的支撑能力。
  </p>
</section>
```

### 踩坑提示
```html
<section style="background: #fff8c5; border: 1px solid #d4a72c; border-radius: 6px; padding: 14px 18px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9; letter-spacing: 0.3px;">
    <span style="color: #9a6700; font-weight: 700; font-family: 'Cascadia Code','Consolas',monospace; font-size: 13px;">[WARNING]</span> <strong style="color: #9a6700;">踩坑提醒</strong>　Windows 下路径有空格会导致安装失败。
  </p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 10px;">
    <span style="background: #0969da; color: #fff; font-size: 12px; font-weight: 700; padding: 3px 10px; border-radius: 4px; font-family: 'Cascadia Code','Consolas',monospace;">STEP_01</span>
    <span style="font-size: 17px; font-weight: 700; color: #24292f;">用自然语言描述你的需求</span>
  </section>
  <p style="font-size: 16px; line-height: 1.9; color: #24292f; margin: 0; letter-spacing: 0.3px;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 26px; border-left: 2px solid #d0d7de;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -33px; top: 2px; background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 3px; padding: 1px 5px; font-size: 11px; color: #0969da; font-family: 'Cascadia Code','Consolas',monospace; font-weight: 700;">01</span>
    <p style="font-size: 16px; color: #24292f; margin: 0 0 4px; font-weight: 700;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #636c76; margin: 0; line-height: 1.9;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -33px; top: 2px; background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 3px; padding: 1px 5px; font-size: 11px; color: #0969da; font-family: 'Cascadia Code','Consolas',monospace; font-weight: 700;">02</span>
    <p style="font-size: 16px; color: #24292f; margin: 0 0 4px; font-weight: 700;">思考（Think）</p>
    <p style="font-size: 15px; color: #636c76; margin: 0; line-height: 1.9;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -33px; top: 2px; background: #dafbe4; border: 1px solid #1a7f37; border-radius: 3px; padding: 1px 5px; font-size: 11px; color: #1a7f37; font-family: 'Cascadia Code','Consolas',monospace; font-weight: 700;">03</span>
    <p style="font-size: 16px; color: #24292f; margin: 0 0 4px; font-weight: 700;">行动（Act）</p>
    <p style="font-size: 15px; color: #636c76; margin: 0; line-height: 1.9;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; border: 1px solid #d0d7de; border-radius: 6px; padding: 20px;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 8px;">
    <span style="background: #8250df; color: #fff; font-size: 12px; font-weight: 700; padding: 3px 10px; border-radius: 4px; font-family: 'Cascadia Code','Consolas',monospace;">CASE_01</span>
    <span style="font-size: 16px; font-weight: 700; color: #24292f;">心情日记App</span>
  </section>
  <p style="font-size: 13px; color: #636c76; margin: 0 0 12px; font-family: 'Cascadia Code','Consolas',monospace;">// type: personal_tool | category: mental_health</p>
  <p style="font-size: 16px; line-height: 1.9; color: #24292f; margin: 0; letter-spacing: 0.3px;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 700; color: #24292f; margin: 0 0 6px;">
    <span style="font-family: 'Cascadia Code','Consolas',monospace; color: #8250df; margin-right: 6px;">L1:</span>Chatbot（纯对话）
  </p>
  <section style="background: #f6f8fa; border-left: 3px solid #d0d7de; padding: 10px 16px; margin: 0 0 16px; border-radius: 0 6px 6px 0;">
    <p style="margin: 0; font-size: 15px; color: #636c76; line-height: 1.9; letter-spacing: 0.3px;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 1.9; color: #24292f; padding-left: 24px; margin: 0 0 22px; letter-spacing: 0.3px; list-style: none;">
  <li style="margin-bottom: 10px;"><span style="color: #0969da; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px;">→</span><strong style="color: #0969da;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><span style="color: #0969da; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px;">→</span><strong style="color: #0969da;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><span style="color: #0969da; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px;">→</span><strong style="color: #0969da;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 1.9; color: #24292f; padding-left: 24px; margin: 0 0 22px; letter-spacing: 0.3px; list-style: none;">
  <li style="margin-bottom: 10px;"><span style="color: #8250df; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px; font-weight: 700;">01.</span><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><span style="color: #8250df; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px; font-weight: 700;">02.</span><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><span style="color: #8250df; font-family: 'Cascadia Code','Consolas',monospace; margin-right: 6px; font-weight: 700;">03.</span><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线

```html
<section style="text-align: center; margin: 36px 0;">
  <span style="font-family: 'Cascadia Code','Consolas',monospace; color: #d0d7de; font-size: 13px;">// ────────────────────</span>
</section>
```

---

## 20. 下一篇预告

```html
<section style="background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 6px; padding: 16px 18px; margin: 28px 0;">
  <p style="margin: 0 0 4px; font-size: 12px; color: #636c76; font-family: 'Cascadia Code','Consolas',monospace;">// next_episode</p>
  <p style="margin: 0; font-size: 15px; color: #24292f; line-height: 1.9;">下一篇我们聊 <strong style="color: #0969da;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <p style="font-size: 13px; color: #d0d7de; margin: 0; font-family: 'Cascadia Code','Consolas',monospace;">
    <span style="color: #1a7f37;">$</span> <span style="color: #636c76;">exit 0</span> <span style="color: #d0d7de;">// EOF</span>
  </p>
</section>
```

---

## 22. 作者签名

```html
<section style="margin-top: 40px; padding-top: 24px; border-top: 1px solid #d0d7de;">
  <p style="margin: 0 0 4px; font-size: 12px; color: #636c76; font-family: 'Cascadia Code','Consolas',monospace;">// author</p>
  <p style="font-size: 15px; color: #24292f; line-height: 2; margin: 0 0 8px;">
    我是 <strong style="color: #0969da;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #0969da;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #636c76; line-height: 2; margin: 0 0 10px;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #24292f; line-height: 2; margin: 0;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #cf222e;">点赞、在看、转发</strong>三连，我们下篇见。
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
  <title>预览 - 代码极客风</title>
  <style>
    body { background: #0d1117; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #fff; border-radius: 8px; overflow: hidden; border: 1px solid #d0d7de; }
    .toolbar { padding: 10px 16px; background: #f6f8fa; border-bottom: 1px solid #d0d7de; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #24292f; font-family: 'Cascadia Code','Consolas',monospace; }
    .toolbar .dots span { display: inline-block; width: 10px; height: 10px; border-radius: 50%; margin-right: 5px; }
    .toolbar button { background: #1a7f37; color: #fff; border: none; padding: 5px 14px; border-radius: 4px; cursor: pointer; font-size: 13px; font-family: 'Cascadia Code','Consolas',monospace; }
    .toolbar button:hover { background: #15803d; }
    .content { padding: 20px 16px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span class="dots">
        <span style="background:#ff5f56;"></span><span style="background:#ffbd2e;"></span><span style="background:#27c93f;"></span>
      </span>
      <span>geek_style.md — 宁的AI小站</span>
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
