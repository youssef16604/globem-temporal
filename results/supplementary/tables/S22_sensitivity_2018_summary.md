**Do conclusions change when 2018 (PANAS-derived labels) is excluded? Includes BDI-II consistent-outcome results.**

| Quantity                                                                  | Main analysis (2018 included)     | Sensitivity (2018 excluded)   | Note                                         |
|:--------------------------------------------------------------------------|:----------------------------------|:------------------------------|:---------------------------------------------|
| Best Forward-chaining AUC (2020, 2021)                                    | Transformer: 0.577 [0.526, 0.626] | XGBoost: 0.601 [0.564, 0.638] |                                              |
| Best Leave-one-year-out AUC (2019, 2020, 2021)                            | XGBoost: 0.587 [0.555, 0.620]     | XGBoost: 0.594 [0.562, 0.624] |                                              |
| Forward: comparisons vs XGBoost significant after Holm                    | 1/7                               | 1/7                           | test years: main 2020, 2021; excl. 2018 2021 |
| Forward: comparisons DG vs ERM significant after Holm                     | 0/2                               | 0/2                           | test years: main 2020, 2021; excl. 2018 2021 |
| Forward MLP-GroupDRO - MLP-ERM (test years 2021)                          | +0.015 [-0.030, +0.066]           | +0.001 [-0.057, +0.050]       |                                              |
| Forward MLP-IRM - MLP-ERM (test years 2021)                               | +0.033 [-0.019, +0.089]           | +0.005 [-0.044, +0.051]       |                                              |
| Within-year split-half: jaccard (cluster), 2019-2021 only                 | 0.836                             | 0.866                         |                                              |
| Within-year split-half: spearman_top (cluster), 2019-2021 only            | 0.942                             | 0.964                         |                                              |
| Within-year split-half: spearman (modality), 2019-2021 only               | 0.992                             | 0.993                         |                                              |
| Cross-year (year-specific models): jaccard (cluster), 2019-2021 only      | 0.044                             | 0.036                         |                                              |
| Cross-year (year-specific models): spearman_top (cluster), 2019-2021 only | 0.158                             | 0.134                         |                                              |
| Cross-year (year-specific models): spearman (modality), 2019-2021 only    | 0.91                              | 0.88                          |                                              |
| Year-classifier macro AUC (all features)                                  | 0.996                             | 0.994                         |                                              |
| BDI-II end-term outcome, forward AUC: Dummy                               | 0.496 [0.429, 0.561]              |                               | consistent outcome in all four years         |
| BDI-II end-term outcome, forward AUC: LogReg                              | 0.587 [0.531, 0.647]              |                               | consistent outcome in all four years         |
| BDI-II end-term outcome, forward AUC: XGBoost                             | 0.589 [0.521, 0.650]              |                               | consistent outcome in all four years         |
| BDI-II end-term outcome, forward AUC: MLP-ERM                             | 0.568 [0.501, 0.629]              |                               | consistent outcome in all four years         |
