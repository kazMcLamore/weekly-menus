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

## Active customers (summary)

### Kaz — [`customers/kaz/AGENTS.md`](customers/kaz/AGENTS.md)
- 100% gluten-free; bold/saucy flavours
- ~25 plate-combos/week (customer + assistant cook)
- Wed–Fri rolling batch; Playa del Carmen

### Marygel — [`customers/marygel/AGENTS.md`](customers/marygel/AGENTS.md)
- Dinner only Mon–Fri × 2 adults; ~600–800 kcal/dinner
- **Strict nut allergy** (incl. cross-contact caution); no fish/shrimp; no organ/exotic meats
- **No oven** — stovetop-only recipes
- Gluten OK; bold / Indian-leaning; mixed carbs (**no tortillas**)
- EN + ES packs; 2–3 cook sessions/week; Playa del Carmen
