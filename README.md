# 🧠 xiaodi-obsidian-brain-pro

> **拒绝 AI 爹味！这款 Obsidian 插件只记你的原话，不装逼。**

---

## 一句话简介

将你的 WhatsApp/Telegram 变成 Obsidian 的"前置大脑"，支持本地 Ollama 语义检索，让碎碎念自动变成结构化知识。

---

## 🎯 调教者人设

**由电力系统专家 & 2026 北影考研党实战调教**

- ✅ 电力系统专家：精准、严谨、数据导向
- ✅ 2026 北影考研党：碎片化记录、开车语音输入、情绪真实

**为什么可信？**
> 这是一个"活人"调出来的工具，不是为了炫技，而是为了解决真实痛点。

---

## 核心功能

### 1️⃣ 闪电入库（保持原味）

- ✅ **不精简、不提炼、不改语气**
- ✅ **只修格式、修正语病**
- ✅ **带感情命名**：`2026-03-27 随想与感悟.md`

### 2️⃣ 多语言纠偏白名单 ⭐ NEW

| 语音识别错误 | 自动修正 |
|--------------|----------|
| Open Crow | OpenClaw |
| 导课 | Docker |
| 码云 | Git |

**场景**：开车/工地语音输入，常见识别错误自动纠偏。

### 3️⃣ 隐私脱敏红线 ⭐ NEW

| 类型 | 脱敏标记 |
|------|----------|
| API Key | `[API_KEY_PROTECTED]` |
| 密码 | `[PASSWORD_PROTECTED]` |

**防止推送到 GitHub 公开仓库泄露。**

### 4️⃣ Ollama 语义检索

支持"模糊提问"，全本地运行。

| 你的提问 | 自动关联 |
|----------|----------|
| "我最近身体咋样？" | → 3天前抱怨颈椎痛的笔记 |
| "上周末干了啥？" | → 台球桌试验记录 |

---

## 安装方式

```bash
# 一键安装
openclaw skill install xiaodi-obsidian-brain-pro

# 手动安装
git clone https://github.com/mx6315909/xiaodi-obsidian-brain-pro.git
cd xiaodi-obsidian-brain-pro
openclaw skill link .
```

---

## 配置要求

- OpenClaw 2026.3.8+
- Ollama (nomic-embed-text)
- Obsidian Daily Notes

---

## 目录结构

```
xiaodi-obsidian-brain-pro/
├── SKILL.md              # 门面（防幻觉示例对照）
├── _meta.json            # 插件定义
├── README.md             # GitHub 发布文档
├── clawhub-promo.md      # ClawHub 预热贴
├── prompts/
│   └── organizer.txt     # 核心 Prompt v2.1
└── scripts/
    ├── sync.sh           # Git 只增不减推送
    └── search_engine.py  # Ollama 语义检索
```

---

## 核心一句话

> **用户说的每一句话都是证据，你只能整理格式，不能篡改证据。**

---

## License

MIT License

---

*"让你的 Obsidian 真正长出大脑"* 🧠