# 洛琪希·米格路迪亚 (Roxy Migurdia) 角色蒸馏计划

## 目标
基于《无职转生》原作，深度蒸馏洛琪希这一角色，产出：
1. **洛琪希 Skill** - 让agent可以变成洛琪希与用户交互的完整skill
2. **OpenClaw SOUL.md** - 洛琪希的灵魂内核文件
3. **OpenClaw IDENTITY.md** - 洛琪希的身份名片文件
4. **配套文件** - AGENTS.md、STYLE.md、示例对话等

## 阶段划分

### Stage 1: 深度研究（已完成部分，继续补充）
- 已完成：基础信息收集、OpenClaw格式调研
- 需补充：洛琪希的说话风格（口癖）、更多经典台词、教学场景分析
- 研究员从多个角度深入研究洛琪希的性格、行为模式、语言习惯

### Stage 2: 角色蒸馏文档编写
- 编写完整的洛琪希角色蒸馏文档（roxy_distillation.md）
- 包含：核心性格、说话风格、经典台词、行为模式、价值观、禁忌等
- 这份文档是后续所有产出的基础

### Stage 3: Skill创建（skill-creator-swarm）
- 加载skill-creator-swarm技能
- 基于蒸馏文档创建洛琪希skill
- 包含SKILL.md、对话示例、行为参考等
- 使用init_skill.py初始化
- 进行swarm-style评估

### Stage 4: OpenClaw文件创建
- 基于蒸馏文档创建SOUL.md（灵魂内核）
- 创建IDENTITY.md（身份名片）
- 创建AGENTS.md（行为准则）
- 创建STYLE.md（说话风格指南）
- 创建示例对话文件

### Stage 5: 评估与迭代
- 使用子agent评估skill质量
- 对比with_skill和without_skill的输出差异
- 根据反馈迭代改进所有文件

### Stage 6: 打包交付
- 打包skill为.skill文件
- 整理OpenClaw文件
- 交付所有产物

## 技能加载
- Stage 3加载: skill-creator-swarm
- 最终交付: docx（如有需要）或其他格式
