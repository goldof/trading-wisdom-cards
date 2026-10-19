# JX Trading Wisdom Cards

30 numbered trading-discipline cards distilled from **陈江挺《炒股的智慧》** (*Chen Jiangting, "The Wisdom of Stock Trading"*) — each card is a **minimum self-explanatory unit**: number, one-line maxim, source, a falsification condition, and a boundary (when it doesn't apply).

**Source attribution**: every 家训 (maxim) is a compressed quotation from Chen Jiangting's 《炒股的智慧》 — JX01–JX14 from Chapter 5, Section 1 ("华尔街的家训"), JX15–JX30 from a full-book scan against five published inclusion criteria. Brief excerpts, source credited on every card.

Feed any card — image or text — to any LLM and it can explain it. No skill installation required.

- 中文版说明 → [README.zh-CN.md](README.zh-CN.md)

## What this is (and isn't)

This is an **anti-regret tool （防反悔工具）, not stock tips**. It watches the card *holder*, not the market:

- **提醒 ≠ 建议 (reminder ≠ advice).** When a line is crossed, the tool hands back the holder's own words written in advance — it never outputs buy/sell judgments, ratings, or "cut / don't cut" options.
- Each card describes only **what violating the maxim looks like** (证伪条件, falsification condition: observable, decidable, unambiguous at expiry) — for the holder's own self-check.
- Each card carries a **不适用 (boundary)** line: an honest statement of where the card stops applying. A compressed card without its boundary is a deceptive compression.
- Card text never tells you what to buy or sell. It only tells you what breaking your own rule looks like.

## Inclusion criteria

A maxim enters the set only if it is: actionable (guides concrete trading/position/sizing behavior), falsifiable ("what does violating it look like" must be writable), universal (not tied to one stock or moment), non-duplicate, and traceable to the book's original wording. "Borderline, could-go-either-way" candidates are excluded.

## Layout

```
trading-wisdom-cards/
├── README.md / README.zh-CN.md
├── LICENSE               # CC BY-NC-SA 4.0
└── zh/                   # 中文版
    ├── cards.json        # machine-readable, 30 cards
    ├── cards.md          # text version (paste into any LLM)
    └── png/              # 30 illustrated cards (1080×1440)
```

## Cite by number

Numbers are the unit of transmission — "see JX01" carries the whole card. **Numbers JX01–JX30 are never reused and never reordered.** If the set grows, new cards continue from JX31; old numbers never move.

## License

CC BY-NC-SA 4.0 — see [LICENSE](LICENSE). Maxims are brief attributed excerpts from 陈江挺《炒股的智慧》; card design, falsification conditions, and boundary statements are original.
