# 🔍 Design Review — 设计评审

> AI 驱动的 UI/UX 设计评审工具，基于尼尔森十大启发式原则、格式塔原理和认知负荷理论，输出结构化评审报告。

设计到开发流程第二步：**检查文件规范 → 评审设计质量 → 生成设计规范 → 验收 UI 实现**。

## ✨ 核心能力

| 能力 | 说明 |
|------|------|
| **专业评审框架** | 尼尔森十大启发式原则 + 格式塔原理 + 认知负荷理论 + 交互定律 |
| **问题全景表** | 按严重级别分类的问题清单，包含具体位置和可操作建议 |
| **亮点与问题平衡** | 同时指出设计亮点和改进空间，避免纯批评 |
| **AI 局限性声明** | 标注评审的局限性，提醒结合用户测试验证 |

## 📁 文件结构

```
design-review/
├── README.md                       ← 本文件
├── SKILL.md                        ← WorkBuddy 完整版 Skill
├── portable-design-review.md      ← 跨平台便携版（Cursor / Claude Code / Codex）
└── .gitignore
```

## 🚀 安装

### WorkBuddy

```bash
git clone https://github.com/YOUR_USERNAME/design-review.git
cp -r design-review ~/.workbuddy/skills/design-review
```

### Cursor

```bash
mkdir -p .cursor/rules
cp portable-design-review.md .cursor/rules/design-review.mdc
```

### Claude Code

```bash
cat portable-design-review.md >> CLAUDE.md
```

## 📖 使用方式

**触发词**（任一即可）：
- "这个设计怎么样" / "帮我看看"
- "提点意见" / "这样合理吗"
- "有什么问题" / "哪里可以改进"
- "设计评审" / "UI评审" / "UX评审"

**输入**：UI 界面截图 / 设计稿 / 原型图

## 🔗 配套 Skill

| Skill | 说明 |
|-------|------|
| [design-file-audit](https://github.com/YOUR_USERNAME/design-file-audit) | 设计文件规范检查 |
| [design-spec-generator](https://github.com/YOUR_USERNAME/design-spec-generator) | 设计规范文档生成 |
| [ui-acceptance-checker](https://github.com/YOUR_USERNAME/ui-acceptance-checker) | UI 验收（Figma vs 实现对比） |

## 📄 License

MIT
