# Menús Semanales — BatchCraft

Archivo multi-cliente de planes de comida semanales. Cada cliente tiene su propia carpeta, perfil y semanas.

## Estructura

```
customers/
  kaz/                    # Kaz — batch cooking en Playa del Carmen
    AGENTS.md             # Perfil dietético y de cocina
    2026-06-15-week/      # Una carpeta por semana
    …
  <otro-cliente>/
    AGENTS.md
    YYYY-MM-DD-week/
```

El `AGENTS.md` de la raíz dirige al cliente correcto. **No mezclar clientes.**

## Carpeta de semana por cliente

Archivos típicos en `customers/<id>/YYYY-MM-DD-week/`:

- `weekly-menu.md` — plan completo en inglés
- `menu-semanal-espanol.md` — copia de cocina en español
- `weekly-supplement.md` — guía de compras + tips (inglés)
- `suplemento-semanal-espanol.md` — guía de compras + tips (español)

## Agregar un cliente nuevo

1. Crear `customers/<id-corto>/`
2. Escribir `customers/<id-corto>/AGENTS.md`
3. Listarlo en el `AGENTS.md` de la raíz
4. Planear semanas solo dentro de esa carpeta

## Kaz (cliente principal actual)

- 100% sin gluten; sabores intensos y con salsa
- ~25 platos/semana (cliente + asistente de cocina)
- Batch mié–vie; tiendas en Playa del Carmen
- Reglas completas: [`customers/kaz/AGENTS.md`](customers/kaz/AGENTS.md)
