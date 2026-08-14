# 主题：青绿山水风 (landscape)

**调用名**：山水风 / landscape

青绿山水画的现代演绎——青绿与黛蓝层叠、宣纸底、朱砂小印。与水墨书法风（黑白墨）不同，这套是「有颜色的东方」。适合文化向科普、年终特稿、AI与人文交叉话题。

## 设计令牌

```
宣纸:       #f6f3ec  (暖白)
青绿:       #2f7a6d  (主色，石绿)
黛蓝:       #4a6fa5  (山远)
翠色:       #3a9188  (山中)
墨色:       #2b3a34  (深墨绿黑)
雾灰:       #9db3a8
朱砂:       #b03a2e  (小面积印章红)
金粉:       #c9a05a  (点缀)
引用底:     #eef0e8  (浅绢色)
代码底:     #22312c  (墨绿黑)
圆角:       2px (绢本感)
字体:       'Noto Serif SC','Songti SC','SimSun',serif
核心特色:   青绿→黛蓝渐变条(山峦层叠)、卷轴编号(卷一/卷二)、朱砂小章、绢本质感
```

---

## 1. 标题区

```html
<section style="margin-bottom: 36px; text-align: center;">
  <section style="display: flex; align-items: center; justify-content: center; gap: 0; margin-bottom: 18px;">
    <span style="display: inline-block; width: 30px; height: 6px; background: #4a6fa5; border-radius: 3px 0 0 3px;"></span>
    <span style="display: inline-block; width: 30px; height: 6px; background: #3a9188;"></span>
    <span style="display: inline-block; width: 30px; height: 6px; background: #2f7a6d; border-radius: 0 3px 3px 0;"></span>
  </section>
  <p style="font-size: 12px; color: #9db3a8; letter-spacing: 3px; margin-bottom: 12px; font-family: 'Noto Serif SC',serif;">AI 基础设施科普 · 卷五</p>
  <h1 style="font-size: 25px; font-weight: 700; color: #2b3a34; line-height: 1.5; margin: 0 0 12px; font-family: 'Noto Serif SC',serif; letter-spacing: 2px;">不只是"聊天机器人"</h1>
  <p style="font-size: 15px; color: #4a6fa5; margin: 0 0 16px; font-family: 'Noto Serif SC',serif;">——AI Agent 到底是什么？</p>
  <section style="display: inline-block; border: 1px solid #b03a2e; padding: 2px 10px;">
    <p style="font-size: 12px; color: #b03a2e; margin: 0; letter-spacing: 2px; font-family: 'Noto Serif SC',serif;">GoodTime 记</p>
  </section>
</section>
```

---

## 2. 系列导语

```html
<section style="background: #eef0e8; border-left: 4px solid #2f7a6d; padding: 16px 20px; margin: 0 0 28px;">
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">本文是「AI 基础设施科普」系列第 <strong style="color: #2f7a6d;">五</strong> 篇。上一篇我们聊了上下文窗口，知道了 AI 为什么会"变笨"。今天聊一个更根本的进化：AI 正在从"只会说话"变成"会自己干活"。</p>
</section>
```

---

## 3. 章节标题

```html
<section style="margin: 40px 0 18px;">
  <section style="display: flex; align-items: center; gap: 0; margin-bottom: 8px;">
    <span style="display: inline-block; width: 24px; height: 4px; background: #4a6fa5; border-radius: 2px 0 0 2px;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #3a9188;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #2f7a6d; border-radius: 0 2px 2px 0;"></span>
  </section>
  <h2 style="font-size: 19px; font-weight: 700; color: #2b3a34; margin: 0; line-height: 1.5; font-family: 'Noto Serif SC',serif; letter-spacing: 1px;">卷一 · Chatbot 和 Agent 有何不同？</h2>
</section>
```

---

## 4. 子章节标题

```html
<h3 style="font-size: 17px; font-weight: 700; color: #2f7a6d; margin: 28px 0 12px; font-family: 'Noto Serif SC',serif;">· 一个真实例子 ·</h3>
```

---

## 5. 正文段落

```html
<p style="font-size: 16px; line-height: 2; color: #2b3a34; margin: 0 0 22px; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">你可能用过 ChatGPT 聊天，也听过"AI Agent"这个词。它们最大的区别可以用一句话说清：</p>
```

---

## 6. 核心论断

```html
<section style="margin: 0 0 22px; text-align: center;">
  <p style="font-size: 18px; line-height: 2; color: #2f7a6d; margin: 0; font-weight: 700; font-family: 'Noto Serif SC',serif; letter-spacing: 1px;"><strong>Chatbot 只能"说话"，Agent 能"做事。"</strong></p>
</section>
```

行内高亮：

```html
<span style="color: #b03a2e; font-weight: 600;">关键文字</span>
```

---

## 7. 类比引用块

```html
<section style="background: #eef0e8; border-left: 4px solid #9db3a8; padding: 16px 20px; margin: 0 0 22px;">
  <p style="margin: 0 0 12px; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">你去餐厅，Chatbot 像一个只会念菜单的服务员——你问什么它答什么，但不会帮你下单、上菜、结账。</p>
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">Agent 像一个真正的餐厅经理——你告诉他"我要办一场十人聚餐"，他自己安排菜单、下单、排座位、催菜。</p>
</section>
```

---

## 8. 金句引用块

```html
<section style="margin: 28px 0; text-align: center;">
  <section style="display: flex; align-items: center; justify-content: center; gap: 0; margin-bottom: 14px;">
    <span style="display: inline-block; width: 24px; height: 4px; background: #4a6fa5; border-radius: 2px 0 0 2px;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #3a9188;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #2f7a6d; border-radius: 0 2px 2px 0;"></span>
  </section>
  <p style="margin: 0 0 10px; font-size: 18px; color: #2b3a34; line-height: 2; font-weight: 700; font-family: 'Noto Serif SC',serif; letter-spacing: 1px;"><strong>Chatbot 是 AI 的"嘴"，Agent 是 AI 的"嘴 + 手 + 脑。"</strong></p>
  <p style="margin: 0; font-size: 14px; color: #6a7a72; line-height: 2; font-family: 'Noto Serif SC',serif;">它不只是能聊天，而是能自己感知环境、规划步骤、调用工具、循环执行，直到把任务做完。</p>
  <section style="display: flex; align-items: center; justify-content: center; gap: 0; margin-top: 14px;">
    <span style="display: inline-block; width: 24px; height: 4px; background: #2f7a6d; border-radius: 2px 0 0 2px;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #3a9188;"></span>
    <span style="display: inline-block; width: 24px; height: 4px; background: #4a6fa5; border-radius: 0 2px 2px 0;"></span>
  </section>
</section>
```

---

## 9. 对比表格

```html
<section style="margin: 24px 0; overflow-x: auto;">
  <table style="width: 100%; border-collapse: collapse; font-size: 14px; font-family: 'Noto Serif SC',serif;">
    <thead>
      <tr>
        <th style="padding: 11px 12px; text-align: center; color: #f6f3ec; font-weight: 700; background: #2f7a6d; letter-spacing: 1px;">维度</th>
        <th style="padding: 11px 12px; text-align: center; color: #f6f3ec; font-weight: 700; background: #2f7a6d; letter-spacing: 1px;">Chatbot</th>
        <th style="padding: 11px 12px; text-align: center; color: #f6f3ec; font-weight: 700; background: #2f7a6d; letter-spacing: 1px;">Agent</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #2b3a34; font-weight: 700; background: #eef0e8; border-bottom: 1px solid #d8dcd0;">交互方式</td>
        <td style="padding: 10px 12px; text-align: center; color: #6a7a72; border-bottom: 1px solid #d8dcd0;">你说一句，它回一句</td>
        <td style="padding: 10px 12px; text-align: center; color: #6a7a72; border-bottom: 1px solid #d8dcd0;">你给目标，它拆步骤执行</td>
      </tr>
      <tr>
        <td style="padding: 10px 12px; text-align: center; color: #2b3a34; font-weight: 700; background: #eef0e8;">工具使用</td>
        <td style="padding: 10px 12px; text-align: center; color: #6a7a72;">不能调用外部工具</td>
        <td style="padding: 10px 12px; text-align: center; color: #6a7a72;">可以读写文件、搜索网络</td>
      </tr>
    </tbody>
  </table>
</section>
```

---

## 10. 左右对比块

```html
<section style="display: flex; gap: 12px; margin: 24px 0;">
  <section style="flex: 1; background: #eef0e8; border-top: 4px solid #9db3a8; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #9db3a8; margin: 0 0 8px; font-family: 'Noto Serif SC',serif;">传统开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #b03a2e; margin: 0 0 4px; font-family: 'Noto Serif SC',serif;">2万+ / 4个月</p>
    <p style="font-size: 13px; color: #9db3a8; margin: 0;">需技术团队</p>
  </section>
  <section style="flex: 1; background: #eef0e8; border-top: 4px solid #2f7a6d; padding: 18px; text-align: center;">
    <p style="font-size: 12px; color: #9db3a8; margin: 0 0 8px; font-family: 'Noto Serif SC',serif;">秒哒开发</p>
    <p style="font-size: 20px; font-weight: 700; color: #2f7a6d; margin: 0 0 4px; font-family: 'Noto Serif SC',serif;">&lt;50元 / &lt;1小时</p>
    <p style="font-size: 13px; color: #9db3a8; margin: 0;">零代码基础</p>
  </section>
</section>
```

---

## 11. 代码块

### Prompt 代码块
```html
<section style="margin: 20px 0;">
  <p style="font-size: 12px; color: #9db3a8; margin: 0 0 6px; font-family: 'Noto Serif SC',serif; letter-spacing: 2px;">「 Prompt 」</p>
  <section style="background: #22312c; padding: 16px; overflow-x: auto;">
    <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d8e0da; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code># 角色设定
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
<section style="background: #22312c; padding: 16px; margin: 20px 0; overflow-x: auto;">
  <pre style="margin: 0; font-size: 13px; line-height: 1.7; color: #d8e0da; font-family: 'Consolas','Monaco',monospace; white-space: pre-wrap; word-wrap: break-word;"><code>100000 / 1688 * 1688</code></pre>
</section>
```

---

## 12. 图片组件

```html
<section style="margin: 22px 0; text-align: center;">
  <img src="IMAGE_URL" alt="说明文字" style="max-width: 100%; display: block; margin: 0 auto; border: 1px solid #d8dcd0; padding: 4px; background: #fff;" />
  <p style="font-size: 13px; color: #9db3a8; margin: 8px 0 0; font-family: 'Noto Serif SC',serif;">图：秒哒主页 —— 「一句话 做应用」</p>
</section>
```

---

## 13. 提示标注块

### 关键数据
```html
<section style="background: #eef0e8; border-left: 4px solid #b03a2e; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;"><strong style="color: #b03a2e;">关键数据</strong>　传统开发成本2万元、耗时4个月；秒哒不到50元、不到1小时。</p>
</section>
```

### 实测体验
```html
<section style="background: #eef0e8; border-left: 4px solid #4a6fa5; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;"><strong style="color: #4a6fa5;">实测体验</strong>　前后迭代七八轮，总共40分钟。传统开发光出UI设计稿就得一周。</p>
</section>
```

### 收获标注
```html
<section style="background: #eef0e8; border-left: 4px solid #2f7a6d; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;"><strong style="color: #2f7a6d;">收获：</strong>　验证了秒哒对个人工具类App的支撑能力。</p>
</section>
```

### 踩坑提示
```html
<section style="background: #eef0e8; border-left: 4px solid #b03a2e; padding: 14px 20px; margin: 20px 0;">
  <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;"><strong style="color: #b03a2e;">踩坑提醒</strong>　Windows 下路径有空格会导致安装失败。</p>
</section>
```

---

## 14. STEP 步骤块

```html
<section style="margin: 28px 0 22px;">
  <section style="display: flex; align-items: center; gap: 12px; margin-bottom: 10px;">
    <span style="display: inline-block; border: 1px solid #2f7a6d; color: #2f7a6d; font-size: 13px; font-weight: 700; padding: 2px 10px; font-family: 'Noto Serif SC',serif; letter-spacing: 2px;">其一</span>
    <span style="font-size: 17px; font-weight: 700; color: #2b3a34; font-family: 'Noto Serif SC',serif;">用自然语言描述你的需求</span>
  </section>
  <p style="font-size: 16px; line-height: 2; color: #2b3a34; margin: 0; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">打开秒哒，进创作页面选类型——H5网页、小程序或App。然后大白话把需求说出来就行。</p>
</section>
```

---

## 15. 竖向时间线

```html
<section style="margin: 24px 0; padding-left: 26px; border-left: 2px solid #d8dcd0;">
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -30px; top: 6px; width: 8px; height: 8px; background: #4a6fa5; border-radius: 50%;"></span>
    <p style="font-size: 16px; color: #2b3a34; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">感知（Perceive）</p>
    <p style="font-size: 15px; color: #6a7a72; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">收到用户需求，或上一步工具执行的结果</p>
  </section>
  <section style="margin-bottom: 22px; position: relative;">
    <span style="position: absolute; left: -30px; top: 6px; width: 8px; height: 8px; background: #3a9188; border-radius: 50%;"></span>
    <p style="font-size: 16px; color: #2b3a34; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">思考（Think）</p>
    <p style="font-size: 15px; color: #6a7a72; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">分析任务，决定下一步做什么</p>
  </section>
  <section style="position: relative;">
    <span style="position: absolute; left: -30px; top: 6px; width: 8px; height: 8px; background: #2f7a6d; border-radius: 50%;"></span>
    <p style="font-size: 16px; color: #2b3a34; margin: 0 0 4px; font-weight: 700; font-family: 'Noto Serif SC',serif;">行动（Act）</p>
    <p style="font-size: 15px; color: #6a7a72; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">调用工具执行，拿到结果后回到第一步循环</p>
  </section>
</section>
```

---

## 16. CASE 案例块

```html
<section style="margin: 28px 0; background: #eef0e8; padding: 20px; border-top: 4px solid #2f7a6d;">
  <section style="display: flex; align-items: center; gap: 10px; margin-bottom: 8px;">
    <span style="display: inline-block; border: 1px solid #b03a2e; color: #b03a2e; font-size: 11px; font-weight: 700; padding: 2px 8px; font-family: 'Noto Serif SC',serif; letter-spacing: 2px;">案例一</span>
    <span style="font-size: 16px; font-weight: 700; color: #2b3a34; font-family: 'Noto Serif SC',serif;">心情日记App</span>
  </section>
  <p style="font-size: 13px; color: #9db3a8; margin: 0 0 12px; font-family: 'Noto Serif SC',serif;">个人工具 · 心理健康类</p>
  <p style="font-size: 16px; line-height: 2; color: #2b3a34; margin: 0; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">核心功能：每天记心情状态、用emoji打分、看历史趋势图、支持添加照片。</p>
</section>
```

---

## 17. Level 进阶层级

```html
<section style="margin: 20px 0;">
  <p style="font-size: 16px; font-weight: 700; color: #4a6fa5; margin: 0 0 6px; font-family: 'Noto Serif SC',serif;">第一重 · Chatbot（纯对话）</p>
  <section style="background: #eef0e8; border-left: 4px solid #9db3a8; padding: 12px 18px; margin: 0 0 16px;">
    <p style="margin: 0; font-size: 15px; color: #3a4a44; line-height: 2; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">只能文字交互，你说一句它回一句。早期的 ChatGPT 就是这个阶段。</p>
  </section>
</section>
```

---

## 18. 列表

### 无序列表
```html
<ul style="font-size: 16px; line-height: 2; color: #2b3a34; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">
  <li style="margin-bottom: 10px;"><strong style="color: #2f7a6d;">Cursor</strong>：AI 编程助手，能自动读代码、改代码</li>
  <li style="margin-bottom: 10px;"><strong style="color: #2f7a6d;">Claude Code</strong>：命令行 Agent，能自主完成开发任务</li>
  <li style="margin-bottom: 0;"><strong style="color: #2f7a6d;">GitHub Copilot</strong>：从 Issue 到 PR 全自动</li>
</ul>
```

### 有序列表
```html
<ol style="font-size: 16px; line-height: 2; color: #2b3a34; padding-left: 22px; margin: 0 0 22px; letter-spacing: 0.5px; font-family: 'Noto Serif SC',serif;">
  <li style="margin-bottom: 10px;"><strong>感知</strong>：收到用户需求</li>
  <li style="margin-bottom: 10px;"><strong>思考</strong>：决定调用什么工具</li>
  <li style="margin-bottom: 0;"><strong>行动</strong>：执行操作，拿到结果</li>
</ol>
```

---

## 19. 分隔线（山峦三段）

```html
<section style="text-align: center; margin: 36px 0;">
  <span style="display: inline-block; width: 24px; height: 4px; background: #4a6fa5; border-radius: 2px 0 0 2px;"></span>
  <span style="display: inline-block; width: 24px; height: 4px; background: #3a9188;"></span>
  <span style="display: inline-block; width: 24px; height: 4px; background: #2f7a6d; border-radius: 0 2px 2px 0;"></span>
</section>
```

---

## 20. 下一篇预告

```html
<section style="text-align: center; margin: 28px 0; padding: 16px 20px; background: #eef0e8; border-top: 4px solid #4a6fa5;">
  <p style="font-size: 12px; color: #9db3a8; letter-spacing: 3px; margin: 0 0 6px; font-family: 'Noto Serif SC',serif;">下卷预告</p>
  <p style="font-size: 15px; color: #3a4a44; margin: 0; line-height: 2; font-family: 'Noto Serif SC',serif;">下一篇我们聊 <strong style="color: #4a6fa5;">RAG（检索增强生成）</strong>——让 AI 读你的私有数据而不是瞎编。</p>
</section>
```

---

## 21. END 标记

```html
<section style="text-align: center; margin: 36px 0 20px;">
  <section style="display: inline-block; border: 2px solid #b03a2e; padding: 4px 12px;">
    <p style="font-size: 13px; color: #b03a2e; margin: 0; letter-spacing: 4px; font-family: 'Noto Serif SC',serif; font-weight: 700;">卷终</p>
  </section>
</section>
```

---

## 22. 作者签名

```html
<section style="margin-top: 40px; padding-top: 24px; border-top: 2px solid #d8dcd0;">
  <p style="font-size: 15px; color: #2b3a34; line-height: 2; margin: 0 0 8px; font-family: 'Noto Serif SC',serif; letter-spacing: 0.5px;">
    我是 <strong style="color: #2f7a6d;">GoodTime</strong>，｜全栈·AI讲师·社区主理人｜公众号<strong style="color: #2f7a6d;">【宁的AI小站】</strong>——用技术让AI更实用。
  </p>
  <p style="font-size: 14px; color: #9db3a8; line-height: 2; margin: 0 0 10px; font-family: 'Noto Serif SC',serif; letter-spacing: 0.5px;">
    点击主页加群或者私信加群一起学习AI。
  </p>
  <p style="font-size: 15px; color: #2b3a34; line-height: 2; margin: 0; font-family: 'Noto Serif SC',serif; letter-spacing: 0.5px;">
    如果你觉得今天这篇有收获，欢迎<strong style="color: #b03a2e;">点赞、在看、转发</strong>三连，我们下篇见。
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
  <title>预览 - 青绿山水风</title>
  <style>
    body { background: #dfe4da; margin: 0; padding: 40px 20px; }
    .preview-wrapper { max-width: 677px; margin: 0 auto; background: #f6f3ec; overflow: hidden; border: 1px solid #c9cfbe; }
    .toolbar { padding: 12px 20px; background: #2f7a6d; font-size: 13px; display: flex; justify-content: space-between; align-items: center; color: #f6f3ec; font-family: 'Noto Serif SC',serif; letter-spacing: 1px; }
    .toolbar button { background: #f6f3ec; color: #2f7a6d; border: none; padding: 6px 16px; cursor: pointer; font-size: 13px; font-family: 'Noto Serif SC',serif; }
    .content { padding: 24px 20px; }
  </style>
</head>
<body>
  <div class="preview-wrapper">
    <div class="toolbar">
      <span>青绿山水 · 宁的AI小站</span>
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
