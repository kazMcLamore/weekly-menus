# BatchCraft Customer Profile — AGENTS.md

## Dietary Restrictions

- **100% GLUTEN-FREE.** Every recipe must be gluten-free. No wheat, barley, rye, or non-GF oats.
- Cross-contamination awareness: soy sauce must be tamari (GF), avoid malt vinegar, check bouillon/stock cubes, watch for flour-thickened sauces, etc.
- No other allergies declared at this time.

## Customer Profile

- **Age / Sex:** 37-year-old male
- **Activity Level:** Highly active (athlete-level training, regular intense exercise)
- **Macro targets (assumed, to be confirmed):**
  - ~30% protein / ~40% carbs / ~30% fat split
  - Target ~600–700 kcal per meal (adjust based on number of meals/day — clarify with customer)
- **Taste preferences:** Saucy, flavorful, well-seasoned foods. Bold flavours. Dislikes dry/bland food.
- **Cuisine preferences:** Open to all cuisines that can be made GF. Leans toward Mexican, Latin American, Southeast Asian, Mediterranean, and Indian — anything with big flavour.

## Meal Plan Structure

- **Batch cooking cadence:** Weekly (cook once, eat across the week)
- **Days covered per batch:** 5 days (Mon–Fri, unless specified otherwise)
- **Dish count per week:** 5 unique dishes total
  - **3 meat dishes** (chicken, beef, pork, fish, etc.)
  - **2 vegetable/plant dishes** (can include eggs, dairy, legumes)
- **Meal slots per day:** Lunch and dinner (10 meals/week, 2 per day, composed from the 5 dishes)

## Location & Ingredient Availability

- **Location:** Playa del Carmen, Quintana Roo, Mexico
- **Likely grocery stores:** Chedraui, Soriana, Mega, Walmart, local mercados
- **Readily available:** Fresh tropical produce (avocados, limes, tomatoes, tomatillos, chiles of all kinds, cilantro, epazote), corn tortillas & masa harina (naturally GF), dried beans, rice, fresh seafood, chicken, pork, beef, eggs, Mexican cheeses (queso fresco, Oaxaca, crema), plantains, yuca, sweet potatoes
- **May be limited:** Specialty GF products (GF pasta, GF bread, GF wraps), Asian ingredients beyond basics, European specialty items
- **Strategy:** Default to naturally GF ingredients. When a recipe calls for soy sauce, specify tamari (check availability or suggest Mexican alternative like Maggi jugo sazonador which is GF). Lean into the local ingredient ecosystem rather than fighting it.

## Kitchen Equipment (Assumed)

- Standard home kitchen: stove, oven, pots, pans, baking sheets
- Refrigerator and freezer (standard size)
- Blender (standard assumption for Mexican kitchen — salsas, mole)
- Food storage: glass or plastic containers for meal prep
- **To confirm:** Instant Pot / pressure cooker? Air fryer? Slow cooker? Rice cooker?

## Spanish-Speaking Assistant

The customer has a Mexican assistant who does the cooking and speaks Spanish. Every weekly plan must include a Spanish translation.

**File naming:** `menu-semanal-espanol.md` in the same weekly folder.

**What to include in the Spanish document (practical cooking info only):**
- Daily menu table (Día / Almuerzo / Cena)
- All 5 scaled recipes: ingredients with metric/Mexican units (cditas, cdas, tazas, gramos), step-by-step method in Spanish
- Rice cooking instructions
- Packing table (Platillo / Porciones / Contenido por envase / Tipo de envase) and day-by-day grab list
- Deduplicated shopping list (Lista de Compras) organised by supermarket section with Spanish category names (Frutas y Verduras, Carnes/Pescado/Huevo, Abarrotes, Lácteos, Especias y Condimentos, Aceites)
- Notes about GF safety and local ingredient substitutions, written for a Mexican cook (e.g., call out "jitomate" not "tomate", mention local fish like huachinango, name local stores like Chedraui/Walmart)

**What NOT to include in the Spanish document:**
- Macro calculations and nutritional breakdowns
- Source URLs (the English doc already has them)
- Why-this-recipe justifications
- Scaling notes and methodology details

The English document (`weekly-menu.md`) remains the authoritative source with full nutritional data, source citations, and methodology. The Spanish document is the kitchen-ready working copy.

## Storage & Reheating

- Fridge life: assume 4–5 days maximum for most cooked dishes
- Freezer-friendly: flag dishes that freeze well vs. those that don't
- Reheating: microwave assumed primary method. Note if stovetop/oven reheat is strongly preferred for a dish.
- Packing: glass containers preferred. Note container size recommendations per portion.

## Recipe Source Quality

- Prioritise well-reviewed, established recipe sites
- Recipes must be publicly accessible (free, no paywall) or noted if behind one
- All recipes must be fetched and verified — no AI-generated recipes

## Housekeeping

- One directory per week: `YYYY-MM-DD-week` (e.g., `2026-06-15-week`)
- Each week's folder contains:
  - `weekly-menu.md` — full English plan with macros, sources, and methodology
  - `menu-semanal-espanol.md` — Spanish kitchen-ready copy for the assistant
  - Additional files as needed (shopping list, individual dish cards, notes)
- Git commits at each weekly plan completion and profile update
