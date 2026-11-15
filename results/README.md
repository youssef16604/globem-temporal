# Results

Aggregate outputs of `globem_pipeline.ipynb` from the run reported in the manuscript (run `normINCL`, exported
2026-10-03). No file here contains participant-level data.

| Path | Contents |
|---|---|
| `main_figures/` | Figures 1 to 5 (PNG at 300 dpi and PDF) |
| `main_tables/` | Table 1 (cohorts) and Table 2 (pooled performance) |
| `supplementary/figures/` | Supplementary figures 1 to 9 |
| `supplementary/tables/` | Supplementary tables S01 to S35, each as CSV and Markdown |
| `artefact_index.csv` | Caption and path of every figure and table |
| `key_numbers.json` | Numbers quoted in the manuscript text |
| `run_manifest.json` | Settings, library versions, hardware and fingerprints of the run |

Tables of particular use for reproduction:

* `S03_split_composition`: every evaluation split, with training and test years and sizes.
* `S04_model_configurations`: default configurations, search spaces and trial budgets.
* `S05_hpo_selected_parameters`: the hyperparameters selected for every analysis, model and split.
* `S31_per_seed_results`: per-seed metrics for every analysis, model and split.

Inference: two-level bootstrap (2,000 replicates; participants resampled with replacement and a training seed drawn
per replicate), 10 seeds per model, Holm adjustment within comparison families, equivalence margin of 0.02 AUC.
Hyperparameters were selected by Optuna on the participant-disjoint inner validation set only.

Table and figure numbers here are the notebook's own and may differ from the numbering in the published supplement.
