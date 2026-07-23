# Weekly Menus — BatchCraft

Multi-customer gluten-free (and other) weekly meal-plan archive. Each customer has their own folder, profile, and weeks.

## Layout

```
customers/
  kaz/                    # Kaz — Playa del Carmen batch cooking
    AGENTS.md             # Durable dietary + cook profile
    2026-06-15-week/      # One folder per week
    …
  <other-customer>/
    AGENTS.md
    YYYY-MM-DD-week/
```

Root `AGENTS.md` routes agents to the correct customer. **Never mix customers.**

## Per-customer week folder

Typical files inside `customers/<id>/YYYY-MM-DD-week/`:

- `weekly-menu.md` — full English plan (macros, sources, method)
- `menu-semanal-espanol.md` — Spanish kitchen copy (when used)
- `weekly-supplement.md` — shopping guide + cooking tips
- `suplemento-semanal-espanol.md` — Spanish shopping + tips

## Adding a new customer

1. Create `customers/<short-id>/`
2. Write `customers/<short-id>/AGENTS.md` (diet, macros, household, schedule, location)
3. List them in root `AGENTS.md` under Active customers
4. Plan weeks only under that folder

## Kaz (current primary)

- 100% gluten-free; bold/saucy flavours
- ~25 plate-combos/week (customer + assistant cook)
- Wed–Fri rolling batch; Playa del Carmen stores (Chedraui, Walmart, DAC, etc.)
- Full rules: [`customers/kaz/AGENTS.md`](customers/kaz/AGENTS.md)
