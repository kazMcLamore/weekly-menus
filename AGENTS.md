# BatchCraft — Multi-Customer Repo

This repository holds **one folder per customer**. Each customer has their own durable profile and weekly menus. Do not mix customers.

## Directory layout

```
Recipes/
├── AGENTS.md                 ← this file (repo router)
├── README.md / README.es.md
└── customers/
    ├── kaz/
    │   ├── AGENTS.md         ← Kaz's dietary profile, macros, cook schedule
    │   ├── 2026-06-15-week/
    │   ├── 2026-06-22-week/
    │   └── …
    └── <other-customer>/
        ├── AGENTS.md
        └── YYYY-MM-DD-week/
```

## Active customers

| Folder | Who | Notes |
|--------|-----|--------|
| `customers/kaz/` | Kaz | GF athlete; lunch+dinner batch; Spanish packs for assistant cook; Playa del Carmen |
| `customers/marygel/` | Marygel + partner | Dinner Mon–Fri ×2; nut allergy (strict); no fish/shrimp/organs; bold/Indian-leaning; EN+ES; Playa del Carmen |

## Agent rules (always)

1. **Identify the customer first.** If the user does not say who the plan is for, ask before writing files.
2. **Read that customer's `customers/<id>/AGENTS.md`** before planning. Prefer it over this root file for dietary rules, macros, portion counts, and cook cadence.
3. **Create / edit / commit only inside that customer's folder** (`customers/<id>/…`). Never put one customer's week under another's path.
4. **New customer setup:**
   - Create `customers/<short-id>/` (lowercase, no spaces — e.g. `customers/maria/`)
   - Add `customers/<short-id>/AGENTS.md` with their dietary restrictions, macros, household size, cook schedule, location/stores, language needs, and banned sources
   - Add a row to the Active customers table above
   - Weekly folders: `customers/<id>/YYYY-MM-DD-week/`
5. **Shared BatchCraft standards** (every customer unless their AGENTS.md overrides):
   - Never invent recipes — fetch real public sources and cite URLs
   - Sanity-check quantities; document scaling (esp. spices/salt)
   - Calculate macros from named nutrition data (USDA etc.)
   - Deduplicate shopping lists; practical purchase units
6. Root `README.md` is human-facing overview only. Customer-specific truth lives in each `customers/*/AGENTS.md`.

## Default when ambiguous

**Two or more customers are active** (Kaz + Marygel). If the user says “next week’s menu” without a name, **always ask which customer** before writing files. Do not guess.
