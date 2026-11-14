# Temporal Generalisation and Explanation Stability of Passive-Sensing Models for Depressive and Anxiety Symptoms

Analysis code for the manuscript of the same title. One notebook, `globem_pipeline.ipynb`, runs the full analysis
on the GLOBEM dataset (version 1.1) and writes every figure, table and key number reported in the manuscript.

## Data

The data are not included here and may not be redistributed. GLOBEM is available to credentialed users from
PhysioNet under the PhysioNet Credentialed Health Data License 1.5.0: https://doi.org/10.13026/r9s1-s711

After obtaining access, either place the PhysioNet zip in the folder given by `GLOBEM_DRIVE_ROOT`, or point
`GLOBEM_DATA_ROOT` at an extracted copy containing the folders `INS-W_1` to `INS-W_4`.

## Requirements

Python 3 with the packages in `requirements.txt`. A CUDA GPU with high RAM is strongly recommended; the notebook
also runs on CPU, but the full configuration is then impractically slow.

```bash
pip install -r requirements.txt
```

## Running

**Google Colab.** Upload the notebook, select a GPU runtime, put the PhysioNet zip in the root of your Google
Drive and choose *Runtime > Run all*.

**Locally.**

```bash
export GLOBEM_DATA_ROOT=/path/to/extracted/globem      # contains INS-W_1 ... INS-W_4
export GLOBEM_OUTPUT_ROOT=/path/to/outputs
jupyter nbconvert --to notebook --execute globem_pipeline.ipynb --output executed.ipynb
```

**Quick check.** `GLOBEM_SMOKE_TEST=1` runs the whole pipeline in a few minutes with tiny budgets. Its numbers are
meaningless; it only confirms that every stage executes.

The full configuration takes several hours on a GPU. Every expensive stage is checkpointed, so an interrupted run
resumes where it stopped.

## What the notebook produces

| Output | File | Notebook section |
|---|---|---|
| Figure 1, evaluation framework | `main_figures/Fig1_evaluation_framework` | 5, 15 |
| Figure 2, collection year versus depression risk | `main_figures/Fig2_year_vs_depression_auc` | 12, 15 |
| Figure 3, discrimination by protocol and model | `main_figures/Fig3_performance` | 10, 15 |
| Figure 4, calibration and predictive value | `main_figures/Fig4_calibration_ppv` | 11, 15 |
| Figure 5, explanation stability | `main_figures/Fig5_explanation_stability` | 13, 15 |
| Table 1, cohorts | `main_tables/Table1_cohorts` | 3, 16 |
| Table 2, pooled performance | `main_tables/Table2_pooled_performance` | 10, 16 |
| Supplementary tables S01 to S35 | `supplementary/tables/` | 16 |
| Supplementary figures 1 to 9 | `supplementary/figures/` | 16 |
| Numbers quoted in the text | `key_numbers.json` | 17 |
| Settings, library versions, fingerprints | `run_manifest.json` | 17 |

Evaluation splits are defined in Section 5. The selected hyperparameters for every analysis, model and split are
written to `supplementary/tables/S05_hpo_selected_parameters.csv`, and the search spaces to
`S04_model_configurations.csv`. The mapping from engineered features to behavioural constructs and sensing
modalities is the function `parse_feature` in Section 6.

## Reproducibility notes

* All seeds are fixed in the configuration cell: split seed 42, tuning seed 1000, evaluation seeds 0 to 9.
* Each Optuna study has a 2,400-second limit, so a re-tuned run can select different hyperparameters on different
  hardware. The configurations used for the manuscript are those in table S05.
* Neural-network results can differ slightly across GPU models and library versions.
* Checkpoints are keyed by a fingerprint of the code, settings and inputs they depend on. Editing a function
  invalidates the stages that depend on it, which are then recomputed.

## Data protection

Exported figures, tables and `key_numbers.json` contain aggregate results only. The `checkpoints/` folder holds
per-window predictions with participant identifiers and must not be shared. Clear all notebook outputs before
committing (`jupyter nbconvert --clear-output --inplace globem_pipeline.ipynb`).

## Citation

To be added on publication.

## Licence

To be added. The licence covers the code only, not the GLOBEM data.
