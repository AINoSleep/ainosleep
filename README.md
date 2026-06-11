<div align="center">

# AINoSleep

**做内容的人，遇到麻烦自己做工具自救，顺手开源给同行**

🧰 [免费工具站](https://tools.ainosleep.com) · 🏠 [主页](https://ainosleep.com) · 𝕏 [@AINoSleep](https://x.com/AINoSleep)

</div>

---

## 4 个免费工具，浏览器直接打开

不收钱，不要注册，不上传内容，本地运行。

| 工具 | 解决什么麻烦 | 在线打开 |
|------|------|------|
| 🎨 **封面工坊** | 出封面图反复换平台尺寸。一次出 7 个平台，26 套配色 + 6 种装饰防同质化 | [cover.html](https://tools.ainosleep.com/cover.html) |
| 📝 **图文工坊** | 图文卡片排版手调到崩。粘文字自动排版，要点 / 引用块 / 高亮全自动 | [article.html](https://tools.ainosleep.com/article.html) |
| ✍️ **公众号一键排版** | Markdown 转格式繁琐。5 套主题切换，复制即带样式 | [wechat.html](https://tools.ainosleep.com/wechat.html) |
| 🔍 **去 AI 味检测器** | AI 写的稿满是黑话。270 个词库自动高亮，给替换建议，AI 浓度评分 | [detox.html](https://tools.ainosleep.com/detox.html) |

---

## 我能帮你做什么

主页 [ainosleep.com](https://ainosleep.com) 三档服务，明码标价，不满意可退。

- **Paperclip AI 公司搭建陪跑** · ¥299 起
- **AI 内容代写** · 先免费做 5 条
- **1v1 X 内容运营咨询** · 按需开放

---

## 工具源码

这个仓库就是所有工具的源码，全部静态 HTML，看得懂就拿走改。

```
ainosleep/
├── site/                       # tools.ainosleep.com 部署目录
│   ├── index.html              #   工具箱首页
│   ├── cover.html              #   封面工坊
│   ├── article.html            #   图文工坊
│   ├── wechat.html             #   公众号一键排版
│   └── detox.html              #   去 AI 味检测器
└── home/                       # ainosleep.com 部署目录
    └── index.html              #   个人主页
```

设计语言：深色科技风（`#0f1115` 底色 + `#4f8cff` 蓝），单页应用，零依赖（少数从 CDN 加载字体）。

---

## 找我

- 𝕏 [@AINoSleep](https://x.com/AINoSleep) — 主战场，更新最频
- 微信公众号 **AINoSleep** — 长文沉淀
- 抖音 **AINoSleep** — 图文实录
- 📧 GitHub Issue 或 X 私信，都看

---

<details>
<summary>给 Claude Code 用户：内容运营大脑 Skill</summary>

本仓库同时是一个 Claude Code Skill — X 内容运营大脑（趋势感知/内容生产/排期/复盘），零 API 费用本地运行。详细文档见 [SKILL.md](./SKILL.md)。

```bash
git clone https://github.com/AINoSleep/ainosleep
claude skill install ./ainosleep
```

</details>

---

<div align="center">

不收钱。<br>
有用，记住我。<br>
有需要，回来找我。

</div>
