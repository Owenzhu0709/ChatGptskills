# 欧文 love skills

一套面向 Codex、Claude Code 和其他 Markdown skills 代理的关系支持套件。

它把以下能力放在一个入口中：

- 情绪承接、事实/推测/未知拆分、关系阶段与互惠判断；
- 聊天记录证据提取、固定评分卡、Sternberg 三角理论和社会交换视角；
- 中文、英文、日文及其他语言的自然回复改写；
- 低压认识、邀约、第一次见面、冲突修复和体面退出；
- 角色扮演训练、即时提示和事后复盘；
- PUA、心理压制、煤气灯、间歇性强化、监控和胁迫的识别与防御；
- 家暴、跟踪、私密影像威胁、诈骗和即时危险的安全分流。

## 调用

```text
使用 $owen-love-skills 帮我分析这段聊天，给出一个主判断和下一步。
使用 $owen-love-skills 把这句话改成自然英文，并保留对方拒绝的空间。
使用 $owen-love-skills 和我做一轮聊天训练，最后复盘。
使用 $owen-love-skills 判断这是不是 PUA 或心理控制，并给我边界和退出建议。
```

## 目录

```text
owen-love-skills/
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── 01-evidence-and-relationship-analysis.md
│   ├── 02-communication-and-dating.md
│   ├── 03-multilingual-coach.md
│   ├── 04-training-simulator.md
│   ├── 05-anti-pua-defense.md
│   ├── 06-safety-routing.md
│   ├── 07-privacy-and-memory.md
│   └── 08-source-map.md
└── modules/
    └── goutoujunshi/        # 原有 MIT skill 的兼容副本
```

## 设计边界

“PUA/心理控制”只作为识别、防御、复盘和安全教育主题。套件不教用户绕过拒绝、制造依赖、孤立对方、监控行踪、用性或金钱施压，也不把对方的“不”重新解释成“假性矜持”。

新整合文件遵循父仓库许可证；原始模块和参考项目仍受各自许可证约束。详细来源、版本和许可证记录在 `references/08-source-map.md`。
