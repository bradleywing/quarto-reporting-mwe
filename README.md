# Reporting MWE

A minimal working example Quarto project demonstrating the core structure, layout patterns, and styling conventions used in EPICC reporting. This project serves as a practical starting point for analysts building:

- infographic‑style quarterly briefs  
- narrative‑heavy annual reports  
- hybrid reports that combine data visualization with explanatory text  

The goal is to provide a clean, reproducible template that illustrates how to:

- organize a Quarto reporting project  
- apply project‑level SCSS for consistent styling  
- use the unified icon system (Font Awesome + Bootstrap Icons)  
- incorporate reusable layout components (e.g., panel headers)  
- render to both HTML and PDF reliably  

---

## What This Project Includes

- **Project structure** showing recommended file organization  
- **Unified icon system** with size, color, and alignment utilities  
- **Dashboard‑style panel header component**  
- **Example narrative and data sections**  
- **Local copy of Font Awesome 6 icon files** for reliable rendering  
- **Bootstrap Icons** via Quarto extension  
- **Minimal SCSS theme** demonstrating how to customize typography, spacing, and layout  

---

## Who This Is For

Data team staff who want a clear, working example of how to build reports using Quarto.  
This project is intentionally simple and focused on patterns you can reuse in your own work.

---

## How to Use This MWE

1. Clone or download the repository.  
2. Render the example `.qmd` files to see the layout and components in action.  
3. Use this project as a reference when creating new reports.  
4. Copy components (icons, panel headers, SCSS utilities) into your own reporting repos as needed.  

---

## Key Files

- `index.qmd` — main example report  
- `styles/brief.scss` — project‑level theme and icon utilities  
- `styles/fontawesome/` — vendored Font Awesome 6 assets  
- `_quarto.yml` — project configuration  

---

## Questions or Improvements

If you find a pattern worth adding or refining, feel free to open an issue or propose an update. This MWE is meant to evolve as our reporting practices evolve.
