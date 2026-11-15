**Runtime per pipeline stage (this session).**

| stage                                                           |   seconds |
|:----------------------------------------------------------------|----------:|
| Load raw data                                                   |  107.6000 |
| Clean features                                                  |   13.7000 |
| Build windows                                                   |   12.7000 |
| Self-deviation features                                         |    1.0000 |
| Build BDI-II end-term windows                                   |    1.8000 |
| Fingerprint data and preprocessing                              |    0.5000 |
| Pooled attribution cluster map                                  |    0.8000 |
| Train analysis: main                                            |   96.1000 |
| Train analysis: ex2018                                          |   70.8000 |
| Train analysis: bdi                                             |   42.8000 |
| Train analysis: normabl                                         |   16.5000 |
| Two-level bootstrap and comparisons                             |  155.0000 |
| Paired leave-one-year-out vs forward-chaining (same test years) |    0.0000 |
| Calibration                                                     |    4.8000 |
| Permutation negative control                                    | 1186.0000 |
| Domain shift: year classifiers (out-of-fold AUC and SHAP)       |    1.4000 |
| Domain shift: depression AUC on the same feature subsets        |    0.8000 |
| Domain shift: era transfer                                      |    0.8000 |
| Explanation stability                                           |    0.9000 |
