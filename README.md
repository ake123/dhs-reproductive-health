# Reproductive Health Equity Analysis with DHS-Style Survey Data

A GitHub-ready **R + Quarto** portfolio project demonstrating complex survey analysis for reproductive-health research.

## What this project demonstrates

- survey weights, clusters, and strata
- weighted prevalence estimates
- subgroup analysis by residence and education
- survey-weighted logistic regression
- reproducible R workflows
- Quarto reporting
- policy-facing evidence translation

## Important data note

The repository includes `data/synthetic_dhs_like.csv` so the project runs immediately.

The synthetic dataset **does not represent any real country or respondents**. For more realistic practice, download an official **DHS model dataset** from The DHS Program and adapt the variable mapping in `analysis.qmd`.

## Run locally

1. Install R and Quarto.
2. Clone this repository.
3. Open a terminal in the project folder.
4. Run:

```bash
quarto preview
```

To render the site:

```bash
quarto render
```

The rendered website will be written to `docs/`.

## Publish with GitHub Pages

This repository is configured to render to `docs/`.

After pushing to GitHub:

1. Open **Settings → Pages** in your repository.
2. Choose **Deploy from a branch**.
3. Select your main branch and `/docs`.
4. Save.

You can also use Quarto's GitHub Pages publishing workflow.

## Suggested CV entry

**Reproductive Health Equity Analysis with DHS-Style Survey Data — R, Quarto**  
Developed a reproducible complex-survey analysis workflow using R and Quarto, including survey weighting, clustering, stratification, subgroup estimates, confidence intervals, and survey-weighted regression. Produced policy-oriented visualizations and documented a pathway for adapting the workflow to official DHS model datasets.

## Suggested website description

> A reproducible R + Quarto project demonstrating complex population-survey analysis for reproductive-health research, including weighted estimates, subgroup inequalities, survey design, regression, visualization, and evidence translation.

## License

MIT.
