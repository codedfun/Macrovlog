# Recomp Macro Log

A simple macro tracker for losing fat while building muscle.

- **Targets:** works out daily calories from your stats (Mifflin-St Jeor × activity, minus a 10–25% deficit), with protein at 1 g per lb of body weight, fat at 25% of calories and carbs for the rest.
- **Meal photos:** take a picture of a meal; when opened as a Claude artifact, Claude estimates each food's grams and macros for you to review.
- **Food search with amounts:** about 130 common foods with USDA values per 100 g. Type an amount with the food ("100g mango", "2 eggs", "6 oz chicken breast") to get macros for exactly that amount. Foods not on the list can be looked up with Claude and are saved for next time.
- **Barcode scanning:** photograph a barcode (or type its number). In this standalone version, products are looked up in Open Food Facts. In the Claude version, the first scan of a product asks for a photo of its nutrition label, which Claude reads; the product is saved, so later scans fill in instantly.
- **Weight trend:** 7-day average and weekly rate, with guidance to stay at 0.25–1% loss per week.

## Running it

It's a single file, `index.html`. Open it in a browser, or host it with GitHub Pages.

Outside Claude, your log is saved in that browser only, and Claude features (meal photo estimates, label reading, food lookups) are unavailable. Barcode lookups through Open Food Facts work here, which the Claude version can't reach. Live version: https://claude.ai/artifact/GUZ98Ax9dXSkVg4PHKmpF5
