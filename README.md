# TEX Recipe Collection — README

This repository contains a private LaTeX cookbook: a curated collection of home-tested recipes assembled over years of cooking. It is intended for personal use and archival presentation in a printable, searchable LaTeX format.

## Highlights
- Private recipe collection curated from years of home cooking.
- All recipes have been tried at least once and sourced from various places: online, cookbooks, family, friends, YouTube, etc.
- Measurements are kept in metric units wherever possible for reproducibility and accuracy.
- A mixture of cuisines and styles reflecting a varied home kitchen.
- Typeset with LaTeX for consistent layout, printable PDFs, and easy export.

## Conventions
- Use metric measurements as primary (kilograms, grams, liter, mililiter etc.). Include metric conversions in parentheses if desired.
- Each recipe should include: title, ingredients list, step-by-step directions, notes/tips.
- Prefer ingredient lists with consistent formatting for later parsing or index generation.
- Add the recipe name for later indexing (\index{})

## Building the PDF
Recommended toolchain:
- Install TeX distribution (TeX Live, MikTeX, or MacTeX) and `latexmk`.
- Build with:
    - `latexmk -pdf -xelatex main.tex` (recommended for modern font handling)
    - or `latexmk -pdf -pdflatex main.tex` for standard workflows

Clean auxiliary files:
- `latexmk -CA`

If using images, ensure they are in supported formats (PDF, PNG, JPG) and referenced from `images/`.

## Notes on privacy and distribution
- This repository is intended for private use and contains personal attributions and notes. Do not publish or redistribute without explicit permission from original sources when applicable.
- Respect copyright of sourced recipes and reproduce only as allowed.

## Acknowledgements
- Thanks to family, friends, cookbooks, blogs, and video creators whose recipes inspired these entries. Source lines will be added in the future where known for proper attribution.

## Suggestions & maintenance
- Keep formatting consistent to support automated indexing and PDF generation.

## Release Notes
### V1.0
- Created files, setup .tex and .pdf files, added initial recipes, set type convention, create README and set up  version control with git

### V1.1 (currently in progress)
- Add sources to each recipe where it was acquired
- Complete more recipes from 2025