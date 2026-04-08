# 抽象带篮子 Skill

一个可直接安装的“带篮子人格对话” Skill：默认直接和用户对话，按需切换成放飞文案，并内置语料增强与风险分层。

## 功能亮点

- 默认人格对话：先聊观点和态度，再按需改写文案。
- 默认风格：放飞版本（可按需指定稳妥/标准）。
- 默认强度：辛辣优先（可手动要求温和版）。
- 证据驱动：内置 `references/research/` 语料与来源锚点。
- 风险可控：`v2 labeled` 语料含 `risk_score`，默认仅采样 `risk<=1`。

## 安装

### 1) 从 GitHub 安装（推荐）

```bash
npx skills add ocFunder/dailanzi-skill -y -g
```

### 2) 本地开发模式

将本仓库内容拷贝到：

```bash
~/.codex/skills/chouxiang-dailanzi-framework
```

## 效果示例

```text
用户      ❯ 这帮人总拿学历阴阳我，怎么回？

带篮子    ❯ 学历是简历封面，不是交付结果。真到救火那天，
            他们还得排队找你补锅。先干事，再让结果说话。
```

```text
用户      ❯ 项目又延期了，群里怎么发不尴尬？

带篮子    ❯ 你就直说：今天先认账，明天把脸打回来。
            表面是延期通知，实则二次冲刺动员。继续往里进。
```

```text
用户      ❯ 给我一句短视频开场，要狠一点。

带篮子    ❯ 别先研究你行不行，先动手干一轮。
            拖延症这玩意，不是聊没的，是干没的。
```

## 他蒸馏了什么

| 心智模型 | 一句话 |
|---------|--------|
| 反差放大镜 | 用“预期A + 现实B”做记忆点 |
| 节奏切片法 | 长句拆短拍，先结论后补刀 |
| 梗密度配额 | 梗是调味料，不是主食 |
| 画面先行原则 | 先让人看见，再让人认同 |
| 情绪锚点机制 | 关键位置放情绪词，保证传播力 |

并包含 10 条决策启发式 + 风险分层采样规则（默认 `risk<=1`）。

## 素材来源

- 公开视频条目抓取与去重：552 条
- 高精度过滤语料：271 条
- v2 标签样本：376 条（含 `style_labels` / `scene_labels` / `risk_score`）
- 证据层文档：`references/research/00-07`

完整语料与结构化数据在 `references/research/`。

## 诚实边界

| 维度 | 说明 |
|------|------|
| 首发原话还原 | 社区传播句不等于逐字首发原话 |
| 时效性 | 热梗更新快，语料需要持续刷新 |
| 商务语境 | 默认降档，避免高冲突表达 |
| 语义还原 | 当前更擅长风格迁移，不是人物真身复制 |

## 目录结构

```text
dailanzi-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── style-playbook.md
│   ├── platform-contexts.md
│   ├── mental-models-heuristics.md
│   ├── safety-boundaries.md
│   └── research/
│       ├── 00-method-and-scope.md
│       ├── 01-quotes-evidence.md
│       ├── 02-scene-index.md
│       ├── 03-style-signals.md
│       ├── 04-risk-boundaries.md
│       ├── 05-corpus-v1.md
│       ├── 06-corpus-v1-curated.md
│       ├── 07-corpus-v2-labeled.md
│       ├── raw-corpus.jsonl
│       ├── raw-corpus-curated.jsonl
│       └── raw-corpus-v2-labeled.jsonl
├── README.md
├── README_EN.md
└── LICENSE
```

## 版本说明

- `v1`：规则驱动 + 基础语料。
- `v1 curated`：高精度过滤，降低噪声。
- `v2 labeled`：逐条标签 + 风险分，可直接做采样策略。

## 合规与边界

- 本项目用于风格研究与文案改写，不用于人身攻击、歧视、网暴。
- 语料中“社区传播句”不等同“逐字首发原话”。
- 如用于品牌/商务场景，建议固定使用 `risk<=1`。

## 致谢

- 灵感与方法参考：[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)

## License

MIT
