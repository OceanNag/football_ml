# football_ml

## Purpose
Predict football (soccer) match results using machine learning. This is learning
material — the focus is on building a working, understandable ML pipeline over
football data (e.g. predicting match outcome, score, or related targets).

## Stack
Not locked in yet. Python-based. Starting default when writing code: pandas for
data wrangling, scikit-learn for modeling. Gradient boosting libraries
(XGBoost/LightGBM) are a likely later addition for tabular prediction tasks.
Update this section once the actual stack is chosen.

## Workflow preference
Prefer scripts/modules (`.py` files with functions/classes) over notebook-driven
development, even though this directory lives under a Jupyter kernel path. Use
notebooks only for occasional one-off exploration, not as the primary place logic
lives.

## Suggested structure
Not enforced yet since there's no code — a reasonable starting point as the
project grows:
- `data/` — raw/processed football data (likely gitignored if large)
- `src/` (or top-level modules) — data loading, feature engineering, model
  training/evaluation
- `tests/` — unit tests for data/feature/model logic

## Coding conventions
- No unnecessary abstractions — don't build for hypothetical future requirements.
- No error handling/validation for scenarios that can't happen; only validate at
  real boundaries (external data sources, user input).
- Prefer editing existing files over creating new ones.
- Comments only when the *why* is non-obvious (a hidden constraint, a workaround,
  a subtle invariant) — not restating what the code does.

## Maintenance
This file is a starting brief for a repo with no code yet. Revisit and expand it
once data sources, model choices, and evaluation metrics become concrete.
