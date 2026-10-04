# Sweet Crunch Society

A printable, single-page recipe card for **Golden Bread & Butter Pickles**, a refrigerator (no-canning) clone of the store-bought classic. A second card, `index-zesty.html`, covers **Zesty Garlic Dill Refrigerator Pickles**.

![Preview of the Golden Bread & Butter Pickles card](docs/preview.png)

![Preview of the Zesty Garlic Dill Refrigerator Pickles card](docs/preview-zesty.png)

## Warnings

**Make this at your own risk.** This is a home recipe shared as-is, with no warranty. You are responsible for food safety. **Pickles made from this recipe may not be sold.**

Refrigerator pickles are not canned or heat-processed, so they are **not shelf-stable**. Follow these rules:

- **Keep them cold.** Store the jars in the refrigerator at 40°F (4°C) or below at all times. Do not leave them at room temperature except while serving.
- **Start clean.** Wash your hands, use clean utensils, and sterilize the jars before filling them.
- **Use 5% vinegar.** Use distilled white vinegar labeled 5% acidity, and do not reduce the vinegar or swap in a vinegar of unknown strength. The acid level is what makes the pickles safe.
- **Do not can this recipe.** It has not been tested for water-bath canning. Keep it as a refrigerator pickle only.
- **Keep the vegetables under the brine.** Submerged food stays safer and firmer.
- **Toss questionable jars.** Discard the jar if you see mold, slime, fizzing or unusual bubbling, a bulging lid, or an off smell. When in doubt, throw it out.

Sources: [UMN Extension: Pickling basics](https://extension.umn.edu/preserving-and-preparing/pickling-basics) and the [National Center for Home Food Preservation](https://nchfp.uga.edu/how/pickle/general-information-pickling/general-information-on-pickling/).

## Why

Store-bought bread & butter pickles are sweet, tangy, and very crunchy. This recipe recreates that at home with Kirby pickling cucumbers, a salt-and-ice soak, and calcium chloride for extra snap. Kirbys are used because they are firmer and lower in water than European cucumbers, which shriveled in early test batches. The card is one self-contained HTML file that prints cleanly on US Letter paper, so it can live on the fridge or in a recipe binder.

## The recipes at a glance

| Detail | Golden Bread & Butter | Zesty Garlic Dill |
|---|---|---|
| **Style** | Refrigerator, no canning | Refrigerator, no canning |
| **Profile** | Sweet & tangy | Savory & garlicky |
| **Cut** | 3/8" rounds | Spears (quartered lengthwise) |
| **Prep time** | 20 mins + 2 hr soak | 20 mins + 2 hr soak |
| **Yield** | 2 pint jars | 2 pint jars |
| **Brine** | 1 1/2 cups vinegar + 1 1/2 cups sugar (about 3.3% acidity once dissolved) | 1 1/2 cups vinegar + 1 cup water (about 3.0% acidity) |
| **Min. chill** | 24-48 hours | 72 hours |
| **Peak flavor** | Days 5-14 | Days 5-12 |
| **Keeps** | Up to 1 month | Up to 3-4 weeks |

## Accessibility

- Semantic HTML: one `h1`, `h2` sections, and `h3` cards, with `<header>`, `<main>`, and `<footer>` landmarks
- Steps are an ordered list and ingredients are a list
- Decorative SVGs are hidden from screen readers with `aria-hidden`; the society name is also plain text in the header and footer
- Text colors were chosen for readable contrast on their backgrounds

## Editing the recipe

All recipe text is plain HTML in `index.html` (sweet B&B) and `index-zesty.html` (garlic dill). Ingredients are `<li>` items in the Ingredients section, steps are `<li>` items in the Preparation Steps `<ol>`, and the four customization cards are at the bottom. The page is fixed to one Letter sheet, so if you add a lot of text, check the print preview for overflow.
