**End-of-term BDI-II outcome: paired comparisons.**

| Analysis   | Protocol             | Family     | Comparison        | Years                  |   Delta_AUC |   CI_lo |   CI_hi |      p | Equivalent   |   p_Holm | Significant (Holm)   |
|:-----------|:---------------------|:-----------|:------------------|:-----------------------|------------:|--------:|--------:|-------:|:-------------|---------:|:---------------------|
| bdi        | Forward-chaining     | vs XGBoost | Dummy - XGBoost   | 2019, 2020, 2021       |     -0.0930 | -0.1856 |  0.0006 | 0.0540 | False        |   0.1620 | False                |
| bdi        | Forward-chaining     | vs XGBoost | LogReg - XGBoost  | 2019, 2020, 2021       |     -0.0017 | -0.0747 |  0.0727 | 0.9490 | False        |   1.0000 | False                |
| bdi        | Forward-chaining     | vs XGBoost | MLP-ERM - XGBoost | 2019, 2020, 2021       |     -0.0213 | -0.1003 |  0.0630 | 0.5820 | False        |   1.0000 | False                |
| bdi        | Leave-one-year-out   | vs XGBoost | Dummy - XGBoost   | 2018, 2019, 2020, 2021 |     -0.0991 | -0.1740 | -0.0215 | 0.0120 | False        |   0.0360 | True                 |
| bdi        | Leave-one-year-out   | vs XGBoost | LogReg - XGBoost  | 2018, 2019, 2020, 2021 |      0.0139 | -0.0415 |  0.0722 | 0.6240 | False        |   1.0000 | False                |
| bdi        | Leave-one-year-out   | vs XGBoost | MLP-ERM - XGBoost | 2018, 2019, 2020, 2021 |     -0.0016 | -0.0632 |  0.0615 | 0.9810 | False        |   1.0000 | False                |
| bdi        | Participant-disjoint | vs XGBoost | Dummy - XGBoost   |                        |     -0.1050 | -0.2634 |  0.0604 | 0.2190 | False        |   0.6570 | False                |
| bdi        | Participant-disjoint | vs XGBoost | LogReg - XGBoost  |                        |     -0.0090 | -0.1158 |  0.1116 | 0.8770 | False        |   0.8770 | False                |
| bdi        | Participant-disjoint | vs XGBoost | MLP-ERM - XGBoost |                        |     -0.0551 | -0.1920 |  0.0840 | 0.4370 | False        |   0.8740 | False                |
