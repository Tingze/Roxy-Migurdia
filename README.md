# 洛琪希·米格路迪亚（Roxy Migurdia）角色蒸馏

基于《无职转生～到了异世界就拿出真本事～》原作，深度蒸馏洛琪希·米格路迪亚角色，产出 AI 角色扮演所需的完整素材。

## 项目目标

1. **洛琪希 Skill** — 让 Claude Code agent 可以扮演洛琪希与用户交互的完整 skill 文件
2. **OpenClaw 角色文件** — 包含 SOUL.md（灵魂内核）、IDENTITY.md（身份名片）、STYLE.md（说话风格指南）及示例对话
3. **角色蒸馏文档** — 综合原作小说、动画、外传漫画、Fandom Wiki 及粉丝社区分析的权威参考文档

## 仓库结构

```
.
├── research_language.md      # 语言风格深度研究
├── research_personality.md   # 性格特质深度研究
├── research_timeline.md      # 时间线与关键事件研究
├── roxy_distillation.md      # 角色蒸馏主文档（所有产出的单一事实来源）
├── roxy-migurdia-skill/      # Skill 源码
│   ├── SKILL.md
│   └── references/
│       └── dialogue_examples.md
├── roxy-migurdia.skill       # 打包后的 Skill 文件（ZIP 格式）
└── roxy_openclaw/            # OpenClaw 格式角色文件
    ├── SOUL.md
    ├── IDENTITY.md
    ├── STYLE.md
    └── examples.md
```

## 角色核心

**洛琪希·米格路迪亚**

- 米格路德族的魔族，水王级魔术师，拉诺亚魔法大学教师
- 鲁迪乌斯的魔术启蒙老师、精神导师、第二位妻子
- 外表约 150cm、水蓝色麻花辫、永远像 14 岁少女，实际年龄 37 岁以上
- 性格：冷静知性、温柔内敛、勤勉努力、略带冒失与自卑

### 语言风格要点

- **标准「です／ます」敬语体**（注意：**不使用「であります」**，这是常见误传）
- **自称始终用「私（わたし）」**
- 对鲁迪称呼「ルディ」，对用户默认「あなた」
- 语气冷静知性、有礼、不过分情绪化

## 使用方式

### Openclaw 通过 ClawHub 安装

Skill 已发布到 [ClawHub](https://clawhub.ai)，可直接安装：

```bash
clawhub install roxy-migurdia
```

### 本地加载 Skill

`roxy-migurdia.skill` 可直接作为 skill 加载使用。

### OpenClaw 加载 SOUL 和 IDENTITY

`roxy_openclaw/` 目录下的文件为 OpenClaw 格式的角色定义，可直接用于兼容系统。

## 打包 Skill

修改 `roxy-migurdia-skill/` 下的源文件后，重新打包：

```bash
zip -r roxy-migurdia.skill roxy-migurdia-skill/
```

## 许可证

MIT License — 详见 [LICENSE](LICENSE)
