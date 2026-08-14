# 主题：杂志编辑风 (editorial)

**调用名**：杂志风 / editorial

像翻开一本精品技术杂志。衬线大标题、首字下沉、红色编辑标记、细线分栏。适合深度长文和行业分析。

## 设计令牌

```
背景色:     #f5f2eb  (奶油纸)
墨色:       #1a1a1a  (印刷黑)
编辑红:     #c0392b  (编辑标记红)
灰:         #6b6b6b
浅灰:       #a8a29a
边框色:     #d6cfc2
引用底:     #efeae0
代码底:     #1e1e1e
圆角:       0px (印刷品无圆角)
边框风格:   细线 + 双线 (印刷风格)
字体:       标题 'Georgia','Noto Serif SC',serif / 正文 'Noto Serif SC','Songti SC',serif
核心特色:   Kicker眉题 + 巨大衬线标题 + byline署名、首字下沉、红色编辑标记、No.期号
```

---

## 1. 标题区

```html
<section style="margin-bottom: 36px;">
  <section style="border-top: 1px solid #1a1a1a; border-bottom: 1px solid #1a1a1a; padding: 8px 0; margin-bottom: 24px;">
    <p style="font-size: 11px; color: #1a1a1a; letter-spacing: 3px; margin: 0; text-align: center; font-family: 'Georgia',serif;">宁的AI小站 · AI INFRA SERIES · No.05</p>
  </section>
  <h1 style="font-size: 30px; font-weight: 800; color: #1a1a1a; line-height: 1.3; margin: 0 0 12px; font-family: 'Georgia','Noto Serif SC',serif; letter-spacing: 0.5px;">不只是"聊天机器人"</h1>
  <p style="font-size: 16px; color: #6b6b6b; margin: 0 0 16px; font-family: 'Georgia',serif; font-style: italic;">——AI Agent 到底是什么？</p>
  <p style="font-size: 13px; color: #a8a29a; margin: 0; font-family: 'Georgia',serif;">文 / GoodTime　·　2026.07</p>
</section>
```

---

## 2. 系列导语

```html
<section style="border-top: 3px double #1a1a1a; border-bottom: 1px solid #d6cfc2; padding: 14px 4px; margin: 0 0 28px;">
  <p style="margin: 0 0 6px; font-size: 11px; color: #c0392b; letter-spacing: 3px; font-family: 'Georgia',serif;">卷首语 FROM THE EDITOR</p>
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">本文是「AI 基础设施科普」系列第 <strong style="color: #c0392b;">5</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 18px; border-bottom: 1px solid #d6cfc2; padding-bottom: 10px;">
  <h2 style="font-size: 20px; font-weight: 800; color: #1a1a1a; margin: 0; line-height: 1.5; font-family: 'Georgia','Noto Serif SC',serif;"><span style="color: #c0392b; margin-right: 10px;">01</span>Chatbot 和 Agent 有什么区别？</h2>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 700; color: #1a1a1a; margin: 28px 0 12px; font-family: 'Georgia','Noto Serif SC',serif;"><span style="color: #c0392b; margin-right: 6px;">§</span>一个真实例子</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 2; color: #2a2a2a; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC','Songti SC',serif;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

首段首字下沉版：

```html
<p style="font-size: 16px; line-height: 2; color: #2a2a2a; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><span style="float: left; font-size: 52px; line-height: 1; font-weight: 800; color: #1a1a1a; margin: 4px 10px 0 0; font-family: 'Georgia','Noto Serif SC',serif;">你</span>可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<section style="margin: 0 0 22px; text-align: center;">
  <p style="font-size: 20px; line-height: 1.8; color: #1a1a1a; margin: 0; font-weight: 800; font-family: 'Georgia','Noto Serif SC',serif;"><span style="color: #c0392b;">「</span>Chatbot 只能"说话"，Agent 能"做事。"<span style="color: #c0392b;">」</span></p>
</section>
```

行内高亮：

```html
<span style="color: #c0392b; font-weight: 600;">关键文字</span>
```

---

## 7. 类比引用块

```html
<section style="background: #efeae0; padding: 18px 22px; margin: 0 0 22px; border-left: 1px solid #1a1a1a;">
  <p style="margin: 0 0 8px; font-size: 11px; color: #6b6b6b; letter-spacing: 3px; font-family: 'Georgia',serif;">打个比方 BY ANALOGY</p>
  <p style="margin: 0 0 12px; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜。</p>
</section>
```

---

## 8. 金句引用块（杂志拉页大字引语）

```html
<section style="margin: 28px 0; text-align: center; padding: 8px 20px;">
  <p style="font-size: 40px; color: #c0392b; margin: 0 0 4px; line-height: 0.5; font-family: 'Georgia',serif;">"</p>
  <p style="margin: 0; font-size: 20px; color: #1a1a1a; line-height: 1.8; font-weight: 800; font-family: 'Georgia','Noto Serif SC',serif;">Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</p>
  <p style="margin: 10px 0 0; font-size: 14px; color: #6b6b6b; line-height: 2; font-family: 'Noto Serif SC',serif;">它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px; font-family: 'Noto Serif SC',serif;">
    <thead>
      <tr>
        <th style="padding: 10px 12px; text-align: left; color: #1a1a1a; font-weight: 800; border-top: 3px double #1a1a1a; border-bottom: 1px solid #1a1a1a; letter-spacing: 1px;">维度</th>
        <th style="padding: 10px 12px; text-align: left; color: #1a1a1a; font-weight: 800; border-top: 3px double #1a1a1a; border-bottom: 1px solid #1a1a1a; letter-spacing: 1px;">Chatbot</th>
        <th style="padding: 10px 12px; text-align: left; color: #1a1a1a; font-weight: 800; border-top: 3px double #1a1a1a; border-bottom: 1px solid #1a1a1a; letter-spacing: 1px;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; color: #1a1a1a; font-weight: 700; border-bottom: 1px solid #d6cfc2;">交互方式</td>
        <td style="padding: 10px 12px; color: #6b6b6b; border-bottom: 1px solid #d6cfc2;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; color: #6b6b6b; border-bottom: 1px solid #d6cfc2;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; color: #1a1a1a; font-weight: 700; border-bottom: 1px solid #d6cfc2;">工具使用</td>
        <td style="padding: 10px 12px; color: #6b6b6b; border-bottom: 1px solid #d6cfc2;">不能调用外部工具</td>
        <td style="padding: 10px 12px; color: #6b6b6b; border-bottom: 1px solid #d6cfc2;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 0; margin: 24px 0; border-top: 1px solid #1a1a1a; border-bottom: 1px solid #1a1a1a;">
  <section style="flex: 1; padding: 18px; text-align: center; border-right: 1px solid #d6cfc2;">
    <p style="font-size: 11px; color: #a8a29a; margin: 0 0 8px; letter-spacing: 2px; font-family: 'Georgia',serif;">传统开发</p>
    <p style="font-size: 20px; font-weight: 800; color: #c0392b; margin: 0 0 4px; font-family: 'Georgia',serif;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #a8a29a; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; padding: 18px; text-align: center; background: #efeae0;">
    <p style="font-size: 11px; color: #6b6b6b; margin: 0 0 8px; letter-spacing: 2px; font-family: 'Georgia',serif;">秒哒开发</p>
    <p style="font-size: 20px; font-weight: 800; color: #1a1a1a; margin: 0 0 4px; font-family: 'Georgia',serif;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #a8a29a; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0;">
  <p style="font-size: 11px; color: #6b6b6b; margin: 0 0 6px; letter-spacing: 2px; font-family: 'Georgia',serif;">LISTING 1 — Prompt</p>
  <section style="background: #1e1e1e; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d4d4d4; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code># 角色设定
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
<section style="background: #1e1e1e; padding: 16px; margin: 20px 0; overflow-x: auto;">
  <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d4d4d4; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code>100000 / 1688 * 1688</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0;">
  <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; display: block; border: 1px solid #d6cfc2;" />
  <p style="font-size: 12px; color: #a8a29a; margin: 8px 0 0; font-family: 'Georgia',serif;">图 1 — 秒哒主页：「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="border-left: 3px solid #c0392b; padding: 4px 0 4px 16px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #c0392b;">关键数据　</strong>传统开发成本2万元、耗时4个月；秒哒不到50元、不到1小时。</p>
</section>
```

### 实测体验
```html
<section style="border-left: 3px solid #1a1a1a; padding: 4px 0 4px 16px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #1a1a1a;">实测体验　</strong>前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。</p>
</section>
```

### 收获标注
```html
<section style="border-left: 3px solid #1a1a1a; padding: 4px 0 4px 16px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #1a1a1a;">收获　</strong>验证了秒哒对个人工具类App的支撑能力。</p>
</section>
```

### 踩坑提示
```html
<section style="background: #efeae0; border-left: 3px solid #c0392b; padding: 12px 16px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #4a4a4a; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;"><strong style="color: #c0392b;">踩坑提醒　</strong>Windows 下路径有空格会导致安装失败。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="display: flex; align-items: baseline; gap: 12px; margin-bottom: 10px; border-bottom: 1px solid #d6cfc2; padding-bottom: 8px;">
    <span style="font-size: 24px; font-weight: 800; color: #c0392b; font-family: 'Georgia',serif;">1</span>
    <span style="font-size: 17px; font-weight: 700; color: #1a1a1a; font-family: 'Noto Serif SC',serif;">用自然语言描述你的需求</span>
  </section>
  <p style="font-size: 16px; line-height: 2; color: #2a2a2a; margin: 0; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 26px; border-left: 1px solid #d6cfc2;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -30px; top: 4px; width: 8px; height: 8px; background: #c0392b;"></span>
    <p style="font-size: 16px; color: #1a1a1a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #6b6b6b; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -30px; top: 4px; width: 8px; height: 8px; background: #1a1a1a;"></span>
    <p style="font-size: 16px; color: #1a1a1a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">思考（Think）</p>
    <p style="font-size: 15px; color: #6b6b6b; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -30px; top: 4px; width: 8px; height: 8px; background: #1a1a1a;"></span>
    <p style="font-size: 16px; color: #1a1a1a; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">行动（Act）</p>
    <p style="font-size: 15px; color: #6b6b6b; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; border-top: 3px double #1a1a1a; border-bottom: 1px solid #d6cfc2; padding: 18px 4px;">
  <p style="font-size: 11px; color: #c0392b; letter-spacing: 3px; margin: 0 0 6px; font-family: 'Georgia',serif;">案例研究 CASE STUDY 01</p>
  <p style="font-size: 18px; font-weight: 800; color: #1a1a1a; margin: 0 0 4px; font-family: 'Georgia','Noto Serif SC',serif;">心情日记App</p>
  <p style="font-size: 13px; color: #a8a29a; margin: 0 0 12px; font-family: 'Georgia',serif;">个人工具 · 心理健康类</p>
  <p style="font-size: 16px; line-height: 2; color: #2a2a2a; margin: 0; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 800; color: #1a1a1a; margin: 0 0 6px; font-family: 'Georgia','Noto Serif SC',serif;"><span style="color: #c0392b; margin-right: 8px;">Ⅰ</span>Chatbot（纯对话）</p>
  <section style="border-left: 1px solid #d6cfc2; padding: 4px 0 4px 16px; margin: 0 0 16px;">
    <p style="margin: 0; font-size: 15px; color: #6b6b6b; line-height: 2; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 2; color: #2a2a2a; padding-left: 20px; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif; list-style: none;">
  <li style="margin-bottom: 10px;"><span style="color: #c0392b; margin-right: 8px;">■</span><strong style="color: #1a1a1a;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><span style="color: #c0392b; margin-right: 8px;">■</span><strong style="color: #1a1a1a;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><span style="color: #c0392b; margin-right: 8px;">■</span><strong style="color: #1a1a1a;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 2; color: #2a2a2a; padding-left: 24px; margin: 0 0 22px; letter-spacing: 0.3px; font-family: 'Noto Serif SC',serif;">
  <li style="margin-bottom: 10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线（杂志细-粗双线）

```html
<section style="margin: 36px 0;">
  <hr style="border: none; border-top: 1px solid #1a1a1a; margin: 0 0 3px;" />
  <hr style="border: none; border-top: 3px solid #1a1a1a; margin: 0;" />
</section>
```

---

## 20. 下一篇预告

```html
<section style="margin: 28px 0; border-top: 1px solid #1a1a1a; border-bottom: 1px solid #1a1a1a; padding: 14px 4px;">
  <p style="font-size: 11px; color: #c0392b; letter-spacing: 3px; margin: 0 0 6px; font-family: 'Georgia',serif;">下期预告 NEXT ISSUE</p>
  <p style="font-size: 15px; color: #4a4a4a; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">下一篇我们聊 <strong style="color: #c0392b;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <p style="font-size: 14px; color: #1a1a1a; margin: 0; letter-spacing: 6px; font-family: 'Georgia',serif;">— 完 —</p>
</section>
```

---

## 22. 作者签名（杂志版权页风格）

```html
<section style="margin-top: 40px; border-top: 3px double #1a1a1a; padding-top: 18px;">
  <p style="font-size: 11px; color: #a8a29a; letter-spacing: 3px; margin: 0 0 10px; font-family: 'Georgia',serif;">关于作者 ABOUT THE AUTHOR</p>
  <p style="font-size: 15px; color: #2a2a2a; line-height: 2; margin: 0 0 8px; font-family: 'Noto Serif SC',serif;">
    我是 <strong style="color: #c0392b;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #c0392b;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #6b6b6b; line-height: 2; margin: 0 0 10px; font-family: 'Noto Serif SC',serif;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #2a2a2a; line-height: 2; margin: 0; font-family: 'Noto Serif SC',serif;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #c0392b;">点赞、在看、转发</strong>三连，我们下篇见。
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
  <title>预览 - 杂志编辑风</title>
  <style>
    body { background: #d9d4c7; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #f5f2eb; overflow: hidden; border: 1px solid #c9c2b2; }
    .toolbar { padding: 12px 20px; background: #1a1a1a; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #f5f2eb; font-family: Georgia,serif; letter-spacing: 1px; }
    .toolbar button { background: #c0392b; color: #fff; border: none; padding: 6px 16px; cursor: pointer; font-size: 13px; font-family: Georgia,serif; }
    .toolbar button:hover { background: #a93226; }
    .content { padding: 24px 20px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>EDITORIAL · 杂志编辑风 · 宁的AI小站</span>
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
