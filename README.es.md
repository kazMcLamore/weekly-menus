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

## Clientes activos (resumen)

### Kaz — [`customers/kaz/AGENTS.md`](customers/kaz/AGENTS.md)
- 100% sin gluten; sabores intensos y con salsa
- ~25 platos/semana (cliente + asistente)
- Batch mié–vie; Playa del Carmen

### Marygel — [`customers/marygel/AGENTS.md`](customers/marygel/AGENTS.md)
- Solo cenas lun–vie × 2 adultos; ~600–800 kcal/cena
- **Alergia estricta a nueces/cacahuate**; sin pescado/camarón; sin vísceras
- Gluten OK; sabores intensos / inclinación india; carbohidratos mixtos (**sin tortillas**)
- Paquetes EN + ES; 2–3 sesiones de cocina/semana; Playa del Carmen
