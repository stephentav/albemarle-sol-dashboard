# Albemarle County school SOL trends

Interactive charts of Virginia Standards of Learning results for Albemarle County Public Schools. The dashboard lets readers choose a school and grade, then compare reading and mathematics pass rates and average scaled scores by race and economic-disadvantage status for 2021–22 through 2025–26.

## Data and interpretation

- Source: Virginia Department of Education Assessment Statistics report downloaded in November 2026.
- The dashboard displays published school-level values only. Suppressed or unavailable subgroup results appear as gaps and are not estimated.
- Grades 3–8 use the matching grade-level test. High-school grades use the available end-of-course subject aggregate.
- A pass rate and an average scaled score answer different questions; neither should be interpreted as an individual student result or a causal measure of school effectiveness.

## Reproducibility

The page is generated from `assessment_statistics-7.csv` by `analysis/scripts/build_crozet_school_sol_charts.mjs` in the associated local analysis project. Run the generator with `--all-schools --standalone` to rebuild `index.html` after updating the source data.

## Hosting

This repository is intended for GitHub Pages. The site consists of a single `index.html` file and loads Apache ECharts 5.6.0 from jsDelivr.
