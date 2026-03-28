# 🧠 Obsidian-Brain-Pro (v1.1.0)

> **拒绝 AI "爹味"润色，记录最真实的生命痕迹。**

---

## 📖 开发者背后的故事

这是一个从电力工地一线、高速公路驾驶座、以及北影管理学院考研笔记中"长"出来的工具。

我是一名在电力行业奔波的极客，也是一名考研党。我发现市面上所有的 AI 笔记工具都有个通病：喜欢自作聪明。

我说"颈椎疼，有点烦"，它非要给我整理成"身体健康管理建议"。

我说"思绪混乱"，它非要给我修饰成"逻辑严密的复盘"。

**不，那不是我的生命。** 我的生命是碎片化的、是有情绪的、是有错别字的。

所以我写了 Obsidian-Brain-Pro，配合 OpenClaw，让 AI 闭嘴，让记忆说话。

---

## ✨ 核心黑科技

### 🛡️ 1. "反幻觉"装甲 (v2.0 Prompt)

内置严苛的红线规则。AI 只能帮你改错别字、加标题和时间戳，**严禁修改你的语气、美化你的情绪、重构你的逻辑**。

| 用户原话 | AI 行为 |
|----------|---------|
| "颈椎疼，有点烦" | ✅ 保持原样，加标题 |
| "思绪混乱" | ✅ 保持原样，加时间戳 |
| AI 想改成"健康管理建议" | ❌ **禁止！** |

### 🚗 2. 语音输入"纠偏仪"

针对开车、工地等语音转文字场景优化。自动修正专业术语识别错误：

| 语音识别错误 | 自动修正 |
|--------------|----------|
| Open Crow | OpenClaw |
| 导课 | Docker |
| 码云 | Git |
| 病毒 | Docker |
| 阿里云百炼 | Bailian |

**即便你在风口浪尖说话，小弟也能听懂你的术语。**

### 🔒 3. 隐私脱敏盾牌

自动嗅探并拦截敏感信息，你可以放心把笔记推送到 GitHub：

| 类型 | 脱敏标记 |
|------|----------|
| API Key | `[API_KEY_PROTECTED]` |
| Password | `[PASSWORD_PROTECTED]` |
| Token | `[TOKEN_PROTECTED]` |
| Phone | `[PHONE_PROTECTED]` |
| Email | `[EMAIL_PROTECTED]` |

### 🔍 4. 本地语义索引 (Powered by Ollama)

无需联网，全本地运行。问它模糊问题，它能跨越日期精准提取：

| 你的提问 | 自动关联 |
|----------|----------|
| "我最近在焦虑什么？" | → 上周的吐槽 + 昨晚的随想 |
| "上周末干了啥？" | → 台球桌试验记录 |

---

## 📦 快速开始

### 1. 安装 (OpenClaw 环境)

```bash
# ClawHub 一键安装
npx clawhub@latest install xiaodi-obsidian-brain-pro

# 或手动安装
git clone https://github.com/mx6315909/xiaodi-obsidian-brain-pro.git
cd xiaodi-obsidian-brain-pro
openclaw skill link .
```

### 2. 配置路径

修改 `_meta.json` 中的 `obsidian_path`，指向你的 Obsidian 库：

```json
{
  "config": {
    "obsidian_path": "~/Obsidian/Daily Notes"
  }
}
```

### 3. 开始对话

在 WhatsApp 或 Telegram 发送任何碎碎念，小弟会立刻为你封存记忆。

---

## 📁 目录结构

```
xiaodi-obsidian-brain-pro/
├── SKILL.md              # 核心规则（防幻觉 Prompt）
├── _meta.json            # 插件配置
├── README.md             # 本文档
├── prompts/
│   └── organizer.txt     # 核心 Prompt v2.1
└── scripts/
    ├── sync.sh           # Git 只增不减推送
    └── search_engine.py  # Ollama 语义检索
```

---

## 🤝 商业合作与咨询

如果你也想在 **群晖 NAS** 上部署这套"数字大脑"，或者需要电力/能源行业的定制化 AI 方案，欢迎联系：

- **GitHub Issue**: [提交需求](https://github.com/mx6315909/xiaodi-obsidian-brain-pro/issues)
- **ClawHub**: [技能主页](https://clawhub.ai/skills/xiaodi-obsidian-brain-pro)

---

## 📜 License

MIT-0 License — 免费使用、修改、分发，无需署名。

---

> **我的座右铭：用户说的每一句话都是证据，AI 只能整理格式，不能篡改证据。**

---

*让你的 Obsidian 真正长出大脑* 🧠