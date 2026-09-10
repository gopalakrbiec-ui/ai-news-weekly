# AI News Weekly

A weekly, source-verified roundup of AI industry news. One markdown file per week, every claim linked to a primary announcement or an established outlet.

## Editions

| Week | Dates | Edition |
|---|---|---|
| 2026-W36 | Sep 1 – Sep 10, 2026 | [2026-w36.md](editions/2026-w36.md) |
| 2026-08 (monthly) | Aug 1 – Aug 31, 2026 | [2026-08-monthly.md](editions/2026-08-monthly.md) |

## Structure

```
.
├── README.md              # this file — index of all editions
├── editions/
│   └── YYYY-wNN.md        # one file per week
└── .claude/
    └── commands/
        └── ai-brief.md    # /ai-brief slash command for Claude Code
```

## Sourcing rules

1. A social-media roundup is a **lead**, never a source. Confirm every item against the company's own announcement or an established outlet before it enters a table.
2. Two links per entry maximum: primary announcement first, one independent outlet second.
3. Use the **announcement date**, not the date it was read.
4. State the caveat explicitly when something is:
   - an agreement rather than a completed deal,
   - a personal opinion rather than a company position,
   - a vendor-run benchmark rather than an independent one.
5. Include the number that matters — price, benchmark, dollar amount — or leave the entry out.

## Section template

Each edition uses these sections, dropping any that have no entries that week:

1. Model & product launches
2. Safety, security and incidents
3. Policy, regulation and legal
4. Deals, money and infrastructure
5. Signals and commentary
6. Themes of the week (3–4 numbered observations, not a summary of the tables)

## Workflow

```bash
# in Claude Code, from the repo root
/ai-brief
```

Then review, commit, push:

```bash
git add editions/ README.md
git commit -m "Add 2026-wNN edition"
git push
```
