# SmartLib 科研工具集

> 跨平台科研效率工具 — 文献检索（12亿文献）+ AI引用核查 + 学术知识库

## 包含技能

| 技能 | 描述 |
|------|------|
| **keji-skill-showcase** | 精选合集入口，根据需求自动引导到对应专项技能 |
| **global-biblio-base** | 全球12亿文献知识库（8千万中文期刊可下载）— AI对话检索+全文下载 |
| **smartlib-citation-checker** | 参考文献验真、AI引用核查 — 防ChatGPT/豆包生成的假参考文献 |
| **academic-knowledge-base** | 个人文献知识库 — AI整理笔记+向量语义检索 |

## 快速开始

### Claude Code

```
/plugin install smartlib-skills@claude-plugins-official
```

### Codex CLI

```
# 添加本仓库为插件市场源
/plugin marketplace add J-levee/smartlib-skills

# 安装插件
/plugin install smartlib-skills@smartlib-skills

# 重载激活
/reload-plugins
```

安装后直接对话使用：
- "帮我找几篇关于深度学习的论文"
- "核查这篇论文的参考文献是否真实"
- "把这篇文章保存到我的知识库"

新用户自动注册，免费 100 次/月。同一邮箱跨技能共享配额。

## 平台支持

| 平台 | 状态 |
|------|:--:|
| Claude Code 官方市场 | ✅（审核中） |
| Codex CLI | ✅ |
| SkillHub | ✅ |
| ClawHub | ✅ |

## 许可证

MIT License — 详见 [LICENSE](./LICENSE)
