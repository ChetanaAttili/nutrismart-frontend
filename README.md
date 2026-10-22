# NutriSmart — Nutrition Awareness & Budget Diet Planner

A React + Vite frontend for nutrition education and affordable Indian meal planning.

## Features

- Responsive nutrition-awareness homepage
- Food suggestions with category, preference, budget and search filters
- Expanded Indian meal dataset with estimated serving costs and ingredient lists
- Daily, weekly and monthly meal-plan generator with household size and food preference controls
- Budget summary and warning when the estimate exceeds the entered budget
- Kitchen ingredient selector with matching recipe suggestions
- Grocery list consolidated from the generated plan, editable sample unit prices, checklist and CSV export
- Interactive balanced-diet nutrient cards
- 10-question nutrition quiz with score and explanations
- Nutrition tips and myth/fact cards
- English/Telugu interface toggle
- Saves generated plan in browser localStorage

## Run locally

Install Node.js (LTS), then open a terminal in this folder and run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

To create a production build:

```bash
npm run build
npm run preview
```

## Important notes

- No backend, database or API key is required for this demo.
- Food prices are editable sample estimates, not live local market prices. Price units vary by ingredient and should be checked before real-world use.
- The meal planner uses deterministic local data. It is an educational prototype, not a medically prescribed diet.
- The language toggle translates the main site navigation and core sections; some newer planner labels and meal names remain in English and can be expanded in `src/main.jsx`.
- The build was not verified in this environment because dependency installation timed out. Run `npm install` and `npm run build` locally and fix any environment-specific dependency issues if they occur.
