# Oxygen Calculator

Static HTML app for GitHub Pages.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `manifest.json`, `sw.js`, and this `README.md` to the repo root.
3. In GitHub, open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select the `main` branch and `/root` folder.
6. Save.

(url=https://alinpacurar.github.io/Oxygen-Calculator/)Oxygen Calculator(/url)

## Validation note
The current build reproduces the visible workbook default outputs:
- Ventilated: 2760 L
- Spontaneous: 1800 L
- CPAP: 3840 L
- High flow: 10800 L

The CPAP `+7 L/min` adjustment is inferred from the visible spreadsheet output and should be formally checked against the source workbook formulas before live use.
