# Recipe Format

Every recipe in this repo follows the same structure so they read, scan, and cook the same way. Copy the skeleton below when adding a new one.

## Skeleton

```markdown
# Recipe Name

*A recipe by Joshua Walderbach*

One to three sentences on what the dish is and what makes this version worth cooking.

**Yield:** 6 servings &nbsp;|&nbsp; **Active time:** ~25 minutes &nbsp;|&nbsp; **Total time:** ~1 hour 15 minutes

---

## Ingredients

### Component Name
- 1 lb (454 g) ground pork
- 3/4 cup (~60 g) quick oats

---

## Equipment

- Only list gear that actually matters to the outcome.

---

## Instructions

1. **Short step name.** What to do, and briefly why it matters.

---

## To Serve

How to plate, finish, or pair it — for component recipes like sauces.

---

## Notes

- Why-it-works details: technique, chemistry, ingredient reasoning.

---

## Swaps & Tips

- Substitutions, variations, make-ahead, pairings.

---

## Storage

How to keep it and how to bring it back.
```

## Rules

**Sections.** `Ingredients`, `Instructions`, and `Storage` appear in every recipe. `Equipment`, `To Serve`, `Notes`, and `Swaps & Tips` are optional — include them when there's something real to say. Order is always the order above. Separate top-level sections with `---`.

**Ingredient lines.** Imperial amount first, metric in parentheses, then the ingredient, then prep notes after a comma:

```
- 1 medium yellow onion (~5 oz / 140 g), diced
- 1/2 cup (120 mL) whole milk
- 1 3/4 cups (220 g) all-purpose flour
- 1/2 tsp (~1 g) black pepper
```

**Every ingredient carries both systems** — imperial (cups, tablespoons, ounces, pounds) and metric (grams, milliliters) — so the recipe is cookable either way. This includes spices and baking ingredients. Use `~` for approximations. Use `###` component headings only when the recipe has genuinely separate parts (loaf and glaze, cake and frosting).

In baking recipes, cup measures are convenience conversions and the gram weights are authoritative; say so in `Notes`.

**Instruction steps.** Numbered, starting with a bolded imperative name on the same line as the text: `1. **Brown the sausage.** Heat a large...`. Say why a step matters when it isn't obvious. Multi-beat steps may use indented follow-on paragraphs; blockquotes (`>`) call out a key technique insight.

**Units and typography.**

- ASCII fractions: `1/2`, `3/4`, `1 1/2` — not `½`.
- Both temperature scales: `350°F (175°C)`.
- Pan sizes with `x`: `9x13-inch`, `8x8-inch`, `10-inch skillet`.
- Ranges with en dashes: `45–60 minutes`, `25–30 g`.
- Bold the numbers that matter inside instruction text (times, temperatures, weights).

**Registering a recipe.** Add a row to the matching table in [README.md](./README.md) with a one-sentence description.
