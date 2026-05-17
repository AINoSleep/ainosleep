# AINoSleep · X 内容运营大脑

> 从趋势感知到内容生产、排期复盘的完整运营闭环。零 API 费用，全程本地运行。

---

## 安装

```bash
# 1. 克隆仓库
git clone https://github.com/AINoSleep/ainosleep

# 2. 在 Claude Code 中安装 Skill
claude skill install ./ainosleep

# 3. 初始化工作区
ainosleep init
```

---

## 五大模块

| 模块 | 触发词 | 功能 |
|------|--------|------|
| 🏭 Factory 内容工厂 | `写推文` / `写 thread` / `写长文章` | 素材→短推/Thread/X Article/封面/评论/预热，六格同出 |
| 📅 Publisher 发布台 | `排期` / `日历` | 可视化周历，分条复制，草稿管理 |
| 🧠 Strategist 军师 | `作战计划` / `策略` | 首次建档/周度/季度三模式，执行纪律评分 |
| 📊 Analyst 复盘台 | `复盘` / `分析数据` | 录入数据，归因分析，更新数据护照 |
| 📡 Radar 雷达 | `热点` / `竞品` | 趋势评分，竞品监控，一键移交 Factory |

---

## 本地工具

| 工具 | 位置 | 用途 |
|------|------|------|
| Thread Composer | `tools/thread-composer.html` | Thread 可视化编排，逐条复制 |
| WeChat Composer | `tools/wechat-composer.html` | 公众号一键排版，复制即带格式 |
| Dashboard | `tools/dashboard.html` | 本地数据看板，互动率趋势图 |

浏览器直接打开，无需安装，数据存储在浏览器本地。

---

## 工作流示例

```
# 日常创作
写推文  →  粘贴文章  →  获得5种格式内容  →  保存草稿  →  排期  →  手动发布

# 竞品监控
热点  →  粘贴竞品推文  →  获得今日话题评分  →  write [话题]  →  自动进入 Factory

# 每周复盘
复盘  →  录入数据  →  获得归因分析  →  更新 passport.json  →  下周作战计划
```

---

## 目录结构

```
ainosleep/
├── SKILL.md                   # 主入口（Claude Code Skill 定义）
├── modules/
│   ├── factory.md             # 内容工厂
│   ├── publisher.md           # 发布台
│   ├── strategist.md          # 军师
│   ├── analyst.md             # 复盘台
│   └── radar.md               # 雷达
├── templates/
│   ├── config.example.yaml    # 账号配置模板
│   ├── voice.example.md       # 声音指南模板
│   ├── benchmarks.example.md  # 对标账号模板
│   └── passport.example.json  # 数据护照模板
└── tools/
    ├── thread-composer.html   # Thread 编排工具
    └── dashboard.html         # 本地数据看板
```

---

## 设计原则

- **零 API 费用**：不依赖 X API，发布全程手动复制
- **数据本地**：所有数据存储在本地文件和浏览器，不上传任何服务器
- **模块联动**：Radar → Factory → Publisher → Analyst 数据自动流转
- **声音一致**：每次生成内容自动校验风格，低于阈值自动重写

---

Made by [@AINoSleep](https://x.com/AINoSleep)
