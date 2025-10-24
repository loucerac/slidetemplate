# Slide Template

This repository contains a Beamer presentation based on the Moloch theme with custom styling for the title page, frametitles, and branding elements.

## Getting Started

1. Ensure a LaTeX distribution with `pdflatex`, `latexmk`, and the Moloch theme is installed.
2. Compile the slides:
   ```bash
   latexmk -pdf main.tex
   ```
3. The resulting PDF (`main.pdf`) will be generated in the project root.

## Project Structure

- `main.tex`: Entry point for the presentation.
- `beamerthemecustommoloch.sty`: Custom theme extending Moloch.
- `fig/`: Directory for figures and assets (e.g., logos).

## Notes

- The `.gitignore` excludes common LaTeX auxiliary files and generated PDFs.
- Adjust metadata (title, author, institute, email) directly inside `main.tex`.
