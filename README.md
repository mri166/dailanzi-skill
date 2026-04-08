# 抽象带篮子 Skill

一个可直接安装的中文文案风格 Skill：把普通表达改写成“抽象、带梗、带节奏、可发布”的版本，并内置语料增强与风险分层。

## 功能亮点

- 多场景改写：评论区、短视频字幕、口播稿、通用文案。
- 默认输出：放飞版本（可按需指定稳妥/标准）。
- 证据驱动：内置 `references/research/` 语料与来源锚点。
- 风险可控：`v2 labeled` 语料含 `risk_score`，默认仅采样 `risk<=1`。

## 安装

### 1) 从 GitHub 安装（推荐）

```bash
npx skills add mri166/dailanzi-skill -y -g
```

### 2) 本地开发模式

将本仓库内容拷贝到：

```bash
~/.codex/skills/chouxiang-dailanzi-framework
```

## 触发词（示例）

- 抽象带篮子
- 带梗改写
- 评论区神回复
- 口播稿抽象化
- 整活文案 / 发癫文学

## 快速示例

### 示例1：学历梗

输入：
```text
今天又被人拿学历开玩笑。
```

放飞版：
```text
985、211先别急着上嘴脸，最后还得跟大专哥一起冲KPI。
```

### 示例2：开会加需求

输入：
```text
产品会刚结束，又临时加了三个需求。
```

放飞版：
```text
今天这会主打一个“来都来了再加两层楼”，表面复盘，实则需求开盲盒。
```

### 示例3：评论区神回复

输入：
```text
有人在评论区阴阳怪气：你这也配讲经验？
```

放飞版：
```text
都给我往里进，经验不是看学历封面，是看你挨过几顿项目毒打。
```

### 示例4：打工人情绪句

输入：
```text
今天上班太累了，感觉要撑不住。
```

放飞版：
```text
吃饱喝足继续冲，累是流程，崩是插曲，打工人今天照样把进度条拽到终点。
```

### 示例5：口播开场

输入：
```text
帮我写一句短视频开场，主题是“别焦虑，先动手”。
```

放飞版：
```text
大可不必先研究自己行不行，先动手干一轮，焦虑自然会被执行力拷起来。
```

### 示例6：反差收尾

输入：
```text
项目延期了，怎么发群里不那么尴尬？
```

放飞版：
```text
表面是延期通知，实则是二次冲刺动员：今天先认账，明天把进度追回来，继续往里进。
```

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
