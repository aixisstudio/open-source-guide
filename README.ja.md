# Open Source Guide

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

初めてのオープンソース貢献、ステップバイステップ

_詳細なコンテンツ（リスト・リンク・説明）は保守のため英語です。以下のセクションがガイドになります。_

## 🗺️ Your first open-source contribution, step by step

### 1. Find a beginner-friendly project

- https://goodfirstissue.dev — curated `good first issue`s across projects
- GitHub topic search: [`good-first-issue`](https://github.com/topics/good-first-issue)
- Docs & translations are the easiest entry points — every project wants them

### 2. Understand the workflow

```
fork → clone → branch → edit → commit → push → pull request → review → merge
```

- **Fork** = your own server-side copy you can push to
- **Branch** = don't work on `main`, ever
- **PR** = your proposal + the discussion around it

### 3. PRs that get accepted

- Read `CONTRIBUTING.md` first — always
- One change per PR — small beats big
- Explain **why**, not just what — maintainers merge context, not code
- Be responsive in review — a PR you abandon dies

### 4. Practice safely first

Warm up on purpose-built sandboxes (no judgment, bots merge instantly):

- [first-pull-request](https://github.com/aixisstudio/first-pull-request) — your very first PR
- [add-your-name](https://github.com/aixisstudio/add-your-name) — join the contributors wall

### 5. Level up

- Issues → reproductions → fixes: the trust ladder
- Answer Discussions — maintainers remember helpers
- Consistency beats bursts: one small PR/week builds a real profile

## 🔬 How to read an unfamiliar codebase

1. `README.md` + `CONTRIBUTING.md` — the intent
2. `git log --oneline -50` — what's actively changing
3. Tests — they document behavior better than docs
4. Find the entrypoint, follow one request end-to-end
5. `rg "TODO|FIXME|HACK"` — where the maintainers know it hurts

## 📬 Your first PR — the etiquette

- **Small is respected**: typo fix > half-broken feature
- **Read the last 10 merged PRs**: they teach the project's review style
- **Don't ask "can I work on this"**: just open the PR or comment once, briefly
- **Conventional commits**: `feat:`, `fix:`, `docs:` — check the log first
- **CI red = unmergeable**: run the checks locally first

## 🎓 Programs worth knowing

| Program | For | Prize |
|---|---|---|
| Hacktoberfest | everyone | digital rewards |
| Google Summer of Code | students | stipend + mentorship |
| MLH Fellowship | students | remote internship |
| Outreachy | underrepresented | $7k internship |
| Sovereign Tech Fund | maintainers | funding |

## ⚖️ License quick-decision

| You want | Pick |
|---|---|
| "Just use it" | MIT |
| Credit + patent protection | Apache-2.0 |
| Share-alike | GPL-3.0 |
| Docs/content | CC-BY-4.0 |
| Public domain | Unlicense |

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
