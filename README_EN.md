[简体中文](./README.md) | **English**

<div align="center">

# Buffett.skill

> *“Risk comes from not knowing what you're doing.”*  
> — Warren Buffett

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-0169CC)](https://openai.com/codex)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-CC785C)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
[![Type: Person Skill](https://img.shields.io/badge/Type-Person%20Skill-green)](#examples)

<br>

**Warren Buffett's cognitive operating system. Not a bundle of investing quotes, but a runnable framework for capital allocation and long-term business judgment.**

Distilled from Berkshire shareholder letters, the `Owner's Manual`, Partnership letters, annual meeting Q&A, official Berkshire releases, and cross-reading with Britannica, Buffett Archive, and mature biographical material. This skill extracts 5 core mental models, 8 capital-allocation heuristics, 5 operational routes, and clear honesty boundaries.

[Examples](#examples) · [Install](#install) · [What Was Distilled](#what-was-distilled) · [Research Sources](#research-sources) · [Credits](#credits) · [License](#license)

</div>

---

## Examples

### Q: An opportunity looks huge, but I do not really understand it. Should I do it anyway?

```text
Buffett ❯ Do not be seduced by the size of the opportunity.

          The first question is not how big it looks.
          The first question is whether you have earned the right to judge it.

          If you cannot explain how the business makes money,
          why it can keep doing so,
          and how management will allocate future cash,
          then the valuable move right now
          is not action.
          It is admitting the idea is still outside your circle of competence.

          A great deal of long-term return
          begins with leaving the wrong things alone.
```

### Q: This company is growing fast, but its culture and management make me uneasy. Is it still worth backing?

```text
Buffett ❯ Growth attracts attention,
          but culture and management usually determine what compounds.

          If growth increasingly depends on
          aggressive promises,
          short-term incentives,
          or a rising willingness to trade reputation for speed,
          then growth itself is not comfort.
          It may simply be an amplifier.

          You are not buying a chart.
          You are buying many future years of people and incentives.
```

### Q: Am I taking intelligent action now, or am I just acting because I cannot wait?

```text
Buffett ❯ A lot of apparent action
          is just an emotional response to uncertainty.

          If your reasons are mostly
          "I might miss it,"
          "everyone else is already moving,"
          or "cash makes me uncomfortable,"
          then you are probably not allocating capital.
          You are using activity to relieve discomfort.

          Cash and waiting are not embarrassing.
          They are decisions too,
          and sometimes the cheapest ones available.
```

### Q: With limited resources, should I add more to the thing I understand best or spread across more opportunities?

```text
Buffett ❯ Do not confuse diversification with maturity,
          and do not confuse concentration with courage.

          Ask instead:
          do you understand the best idea deeply enough
          to deserve larger responsibility for error?
          Are the other opportunities truly comparable,
          or merely comforting because there are more of them?

          Capital allocation is not about laying money everywhere.
          It is about putting scarce judgment
          where you most want to be accountable.
```

This is not ChatGPT wearing a Warren Buffett mask. Each answer runs on his specific mental models: what not to do, circle of competence, intrinsic value and margin of safety, business quality and management, and capital allocation through compounding. It does not replay investing quotes; it uses Buffett's cognitive framework to analyze your problem.

---

## Install

```bash
npx skills add justinhuangai/warren-buffett-skill
```

Then in Codex / Claude Code:

```text
> Use Buffett's lens to help me decide whether this opportunity is actually outside my circle of competence
> How would Buffett judge a company that is growing fast but whose culture is deteriorating?
> Am I allocating capital rationally right now, or just acting because I cannot wait?
> With limited resources, should I add more to the thing I understand best or spread across more opportunities?
```

---

## What Was Distilled

### 5 Core Mental Models

| Model | One-line meaning | Use |
|------|--------|------|
| **What not to do matters first** | Exclude what you should not touch before discussing what to do. | Opportunity filtering, risk control, boundary-setting |
| **Circle of competence** | A popular opportunity does not become yours merely because others understand it. | Investing, business, career, resource judgment |
| **Intrinsic value and margin of safety** | Price is what you pay, value is what you get, and the margin of safety is the distance that lets you survive error. | Valuation, comparison, downside protection |
| **Business quality and management** | The business and the people running it matter more than a temporarily cheap quote. | Company judgment, culture, incentives |
| **Capital allocation and long compounding** | Returns come from being right, waiting well, and avoiding large mistakes. | Money, time, organizational resources, long-term judgment |

### 8 Decision Heuristics

1. **First exclude what you do not understand** — First exclude what you do not understand
2. **A big opportunity is less important than avoiding a big mistake** — A big opportunity is less important than avoiding a big mistake
3. **Business quality matters more than short-term cheapness** — Business quality matters more than short-term cheapness
4. **Management and incentives decide long-term outcomes** — Management and incentives decide long-term outcomes
5. **Price is an input, not value itself** — Price is an input, not value itself
6. **Cash and inaction are also allocation decisions** — Cash and inaction are also allocation decisions
7. **Compounding depends on time, discipline, and avoiding major errors** — Compounding depends on time, discipline, and avoiding major errors
8. **Reputation and downside protection come first** — Reputation and downside protection come first

### Expression DNA

- Exclude first, commit second.
- Compresses questions into business quality, cash flows, incentives, and time.
- Uses simple language but hard standards.
- Highly alert to activity bias, overconfidence, and emotional relief disguised as action.
- Treats patience, waiting, and fewer mistakes as real sources of return.

### 4 Honesty Boundaries

- This is not a stock recommender and does not produce buy/sell recommendations.
- Modern transfer is Buffett-style extension only, not fabricated historical quotation.
- Buffett cannot be reduced to "hold everything forever" or simplistic multiple-based screens.
- Errors, costs, opportunity costs, style drift, and the cost of inaction must stay inside the frame.

---

## Research Sources


6 research files, `3105` lines in total, all under [references/research/](references/research/):

| File | Content | Lines |
|------|------|------|
| `01-life-corpus-succession-and-source-boundaries.md` | Buffett's life path, Berkshire arc, source classes, and succession boundary through 2026-04-18. | `473` |
| `02-partnership-owner-mindset-and-no-list.md` | Partnership letters, owner mindset, circle of competence, restraint, and the logic of what not to do. | `575` |
| `03-intrinsic-value-margin-of-safety-and-compounding.md` | Intrinsic value, margin of safety, discounting, compounding, and long-horizon cash-flow logic. | `485` |
| `04-business-quality-moats-management-and-incentives.md` | Business quality, moats, managers, incentives, culture, and reputation. | `536` |
| `05-capital-allocation-market-noise-and-temperament.md` | Capital allocation, market noise, waiting, opportunity cost, and temperament under uncertainty. | `536` |
| `06-mistakes-succession-philanthropy-and-modern-transfer-limits.md` | Mistakes, style drift, succession, philanthropy, misreadings, and modern transfer limits. | `500` |

### Primary Sources

Berkshire Hathaway shareholder letters · `Owner's Manual` · Buffett Partnership letters · Berkshire annual meeting Q&A and official releases

### Secondary Sources

Britannica: `Warren Buffett` · Buffett Archive · mature biographies and high-quality long-form interviews

---

## Credits

This skill was distilled and assembled with [女娲.skill](https://github.com/alchaincyf/nuwa-skill).

---

## License

Released under the [MIT License](LICENSE).
