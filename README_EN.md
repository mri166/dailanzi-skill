# Chouxiang Dailanzi Skill

A ready-to-install persona skill that talks like “Dailanzi” by default, and rewrites text only when needed, with evidence-backed corpus enhancement and risk controls.

## Highlights

- Persona-first conversation by default; rewriting on demand.
- Default style: Wild version (Safe/Standard only when requested).
- Default intensity: spicy tone first (switch to gentle mode on request).
- Evidence-backed references in `references/research/`.
- Risk-aware sampling with `risk_score` (default: use `risk<=1`).

## Installation

### 1) Install from GitHub

```bash
npx skills add ocFunder/dailanzi-skill -y -g
```

### 2) Local development

Copy this repo into:

```bash
~/.codex/skills/chouxiang-dailanzi-framework
```

## Conversation Examples

```text
User       ❯ People keep mocking my education background. How do I reply?

Dailanzi   ❯ Education is a cover page, not delivery output.
             When real work burns, they still queue for whoever can fix it.
```

```text
User       ❯ The project got delayed again. How do I post in team chat?

Dailanzi   ❯ Say it straight: we take the hit today, we win it back tomorrow.
             Looks like a delay notice, actually a sprint re-launch.
```

```text
User       ❯ Give me one hard-hitting opening line for a short video.

Dailanzi   ❯ Stop debating whether you can do it. Ship one round first.
             Procrastination is not talked away, it's executed away.
```

## What Is Distilled

- 5 core mental models
- 10 decision heuristics
- Persona-first dialogue protocol
- Evidence-backed corpus with risk scoring (`risk<=1` by default)

## Structure

```text
SKILL.md
agents/openai.yaml
references/
references/research/
README.md
README_EN.md
LICENSE
```

## Compliance Notes

- For style research and copywriting assistance only.
- No harassment, hate, or targeted abuse.
- Community-spread phrases are not equal to first-source verbatim quotes.

## Credits

- Inspired by [nuwa-skill](https://github.com/alchaincyf/nuwa-skill)

## License

MIT
