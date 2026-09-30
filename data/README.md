# Data

`synthetic_dhs_like.csv` is a synthetic practice dataset created only so the repository can run without restricted or registered data access.

It mimics common complex-survey fields:

- `cluster`: primary sampling unit
- `strata`: sampling stratum
- `weight_raw`: integer sample weight scaled like DHS weights
- `age`: respondent age
- `residence`: urban/rural
- `education`: education category
- `wealth`: wealth quintile
- `married_or_union`: practice indicator
- `modern_contraceptive_use`: synthetic binary outcome

## Using official DHS model data

The DHS Program provides model datasets specifically for practice and teaching. These are imaginary data and do not represent a real country.

Download the Individual Recode model dataset and place it here. Then update the import and variable mapping in `analysis.qmd`.

Always verify recode variables against the official DHS documentation before analysis.
