**Pooled paired comparisons (Holm-adjusted within family; equivalence margin ±0.02 AUC).**

| Analysis   | Protocol             | Family     | Comparison             | Years                  |   Delta_AUC |   CI_lo |   CI_hi |      p | Equivalent   |   p_Holm | Significant (Holm)   |
|:-----------|:---------------------|:-----------|:-----------------------|:-----------------------|------------:|--------:|--------:|-------:|:-------------|---------:|:---------------------|
| main       | Forward-chaining     | vs XGBoost | Dummy - XGBoost        | 2020, 2021             |     -0.0695 | -0.1201 | -0.0208 | 0.0040 | False        |   0.0280 | True                 |
| main       | Forward-chaining     | vs XGBoost | LogReg - XGBoost       | 2020, 2021             |     -0.0107 | -0.0535 |  0.0338 | 0.6340 | False        |   1.0000 | False                |
| main       | Forward-chaining     | vs XGBoost | MLP-ERM - XGBoost      | 2020, 2021             |     -0.0125 | -0.0601 |  0.0341 | 0.6030 | False        |   1.0000 | False                |
| main       | Forward-chaining     | vs XGBoost | MLP-GroupDRO - XGBoost | 2020, 2021             |     -0.0012 | -0.0457 |  0.0433 | 0.9370 | False        |   1.0000 | False                |
| main       | Forward-chaining     | vs XGBoost | MLP-IRM - XGBoost      | 2020, 2021             |      0.0013 | -0.0429 |  0.0485 | 0.9730 | False        |   1.0000 | False                |
| main       | Forward-chaining     | vs XGBoost | GRU - XGBoost          | 2020, 2021             |     -0.0023 | -0.0510 |  0.0447 | 0.9230 | False        |   1.0000 | False                |
| main       | Forward-chaining     | vs XGBoost | Transformer - XGBoost  | 2020, 2021             |      0.0028 | -0.0514 |  0.0517 | 0.9230 | False        |   1.0000 | False                |
| main       | Forward-chaining     | DG vs ERM  | MLP-GroupDRO - MLP-ERM | 2020, 2021             |      0.0113 | -0.0310 |  0.0516 | 0.5950 | False        |   1.0000 | False                |
| main       | Forward-chaining     | DG vs ERM  | MLP-IRM - MLP-ERM      | 2020, 2021             |      0.0138 | -0.0297 |  0.0576 | 0.5300 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | Dummy - XGBoost        | 2018, 2019, 2020, 2021 |     -0.0774 | -0.1094 | -0.0453 | 0.0005 | False        |   0.0035 | True                 |
| main       | Leave-one-year-out   | vs XGBoost | LogReg - XGBoost       | 2018, 2019, 2020, 2021 |     -0.0085 | -0.0350 |  0.0179 | 0.5210 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | MLP-ERM - XGBoost      | 2018, 2019, 2020, 2021 |     -0.0153 | -0.0456 |  0.0136 | 0.2770 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | MLP-GroupDRO - XGBoost | 2018, 2019, 2020, 2021 |     -0.0178 | -0.0483 |  0.0117 | 0.2540 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | MLP-IRM - XGBoost      | 2018, 2019, 2020, 2021 |     -0.0088 | -0.0355 |  0.0193 | 0.5220 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | GRU - XGBoost          | 2018, 2019, 2020, 2021 |     -0.0169 | -0.0477 |  0.0146 | 0.2890 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | vs XGBoost | Transformer - XGBoost  | 2018, 2019, 2020, 2021 |     -0.0094 | -0.0427 |  0.0240 | 0.5740 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | DG vs ERM  | MLP-GroupDRO - MLP-ERM | 2018, 2019, 2020, 2021 |     -0.0025 | -0.0319 |  0.0276 | 0.8780 | False        |   1.0000 | False                |
| main       | Leave-one-year-out   | DG vs ERM  | MLP-IRM - MLP-ERM      | 2018, 2019, 2020, 2021 |      0.0065 | -0.0207 |  0.0349 | 0.6350 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | Dummy - XGBoost        |                        |     -0.0768 | -0.1455 | -0.0049 | 0.0360 | False        |   0.2520 | False                |
| main       | Participant-disjoint | vs XGBoost | LogReg - XGBoost       |                        |      0.0221 | -0.0310 |  0.0828 | 0.4360 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | MLP-ERM - XGBoost      |                        |      0.0195 | -0.0327 |  0.0749 | 0.4570 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | MLP-GroupDRO - XGBoost |                        |      0.0100 | -0.0473 |  0.0687 | 0.7520 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | MLP-IRM - XGBoost      |                        |      0.0164 | -0.0370 |  0.0708 | 0.5420 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | GRU - XGBoost          |                        |     -0.0183 | -0.0827 |  0.0487 | 0.5910 | False        |   1.0000 | False                |
| main       | Participant-disjoint | vs XGBoost | Transformer - XGBoost  |                        |     -0.0022 | -0.0694 |  0.0689 | 0.9490 | False        |   1.0000 | False                |
| main       | Participant-disjoint | DG vs ERM  | MLP-GroupDRO - MLP-ERM |                        |     -0.0095 | -0.0660 |  0.0416 | 0.6930 | False        |   1.0000 | False                |
| main       | Participant-disjoint | DG vs ERM  | MLP-IRM - MLP-ERM      |                        |     -0.0031 | -0.0502 |  0.0444 | 0.9070 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | Dummy - XGBoost        | 2021                   |     -0.1139 | -0.1773 | -0.0517 | 0.0020 | False        |   0.0140 | True                 |
| ex2018     | Forward-chaining     | vs XGBoost | LogReg - XGBoost       | 2021                   |      0.0001 | -0.0420 |  0.0404 | 0.9890 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | MLP-ERM - XGBoost      | 2021                   |     -0.0171 | -0.0641 |  0.0294 | 0.5020 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | MLP-GroupDRO - XGBoost | 2021                   |     -0.0162 | -0.0715 |  0.0338 | 0.5130 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | MLP-IRM - XGBoost      | 2021                   |     -0.0124 | -0.0624 |  0.0326 | 0.6260 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | GRU - XGBoost          | 2021                   |     -0.0444 | -0.1020 |  0.0154 | 0.1560 | False        |   0.9360 | False                |
| ex2018     | Forward-chaining     | vs XGBoost | Transformer - XGBoost  | 2021                   |     -0.0258 | -0.0940 |  0.0405 | 0.4880 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | DG vs ERM  | MLP-GroupDRO - MLP-ERM | 2021                   |      0.0009 | -0.0565 |  0.0500 | 0.9790 | False        |   1.0000 | False                |
| ex2018     | Forward-chaining     | DG vs ERM  | MLP-IRM - MLP-ERM      | 2021                   |      0.0047 | -0.0439 |  0.0514 | 0.8300 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | Dummy - XGBoost        | 2019, 2020, 2021       |     -0.0910 | -0.1266 | -0.0509 | 0.0005 | False        |   0.0035 | True                 |
| ex2018     | Leave-one-year-out   | vs XGBoost | LogReg - XGBoost       | 2019, 2020, 2021       |     -0.0002 | -0.0288 |  0.0271 | 0.9880 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | MLP-ERM - XGBoost      | 2019, 2020, 2021       |     -0.0067 | -0.0364 |  0.0258 | 0.6810 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | MLP-GroupDRO - XGBoost | 2019, 2020, 2021       |     -0.0126 | -0.0457 |  0.0198 | 0.4550 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | MLP-IRM - XGBoost      | 2019, 2020, 2021       |     -0.0135 | -0.0436 |  0.0196 | 0.4010 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | GRU - XGBoost          | 2019, 2020, 2021       |     -0.0268 | -0.0613 |  0.0087 | 0.1310 | False        |   0.7860 | False                |
| ex2018     | Leave-one-year-out   | vs XGBoost | Transformer - XGBoost  | 2019, 2020, 2021       |     -0.0250 | -0.0658 |  0.0140 | 0.2070 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | DG vs ERM  | MLP-GroupDRO - MLP-ERM | 2019, 2020, 2021       |     -0.0059 | -0.0396 |  0.0253 | 0.6890 | False        |   1.0000 | False                |
| ex2018     | Leave-one-year-out   | DG vs ERM  | MLP-IRM - MLP-ERM      | 2019, 2020, 2021       |     -0.0068 | -0.0391 |  0.0235 | 0.6630 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | Dummy - XGBoost        |                        |     -0.1025 | -0.1853 | -0.0252 | 0.0100 | False        |   0.0700 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | LogReg - XGBoost       |                        |      0.0270 | -0.0401 |  0.0941 | 0.4420 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | MLP-ERM - XGBoost      |                        |      0.0196 | -0.0509 |  0.0849 | 0.5740 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | MLP-GroupDRO - XGBoost |                        |      0.0100 | -0.0613 |  0.0807 | 0.8350 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | MLP-IRM - XGBoost      |                        |      0.0180 | -0.0588 |  0.0870 | 0.6130 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | GRU - XGBoost          |                        |     -0.0146 | -0.1052 |  0.0705 | 0.7550 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | vs XGBoost | Transformer - XGBoost  |                        |      0.0093 | -0.0708 |  0.0846 | 0.8110 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | DG vs ERM  | MLP-GroupDRO - MLP-ERM |                        |     -0.0095 | -0.0775 |  0.0628 | 0.7720 | False        |   1.0000 | False                |
| ex2018     | Participant-disjoint | DG vs ERM  | MLP-IRM - MLP-ERM      |                        |     -0.0016 | -0.0797 |  0.0662 | 0.9980 | False        |   1.0000 | False                |
| bdi        | Forward-chaining     | vs XGBoost | Dummy - XGBoost        | 2019, 2020, 2021       |     -0.0930 | -0.1856 |  0.0006 | 0.0540 | False        |   0.1620 | False                |
| bdi        | Forward-chaining     | vs XGBoost | LogReg - XGBoost       | 2019, 2020, 2021       |     -0.0017 | -0.0747 |  0.0727 | 0.9490 | False        |   1.0000 | False                |
| bdi        | Forward-chaining     | vs XGBoost | MLP-ERM - XGBoost      | 2019, 2020, 2021       |     -0.0213 | -0.1003 |  0.0630 | 0.5820 | False        |   1.0000 | False                |
| bdi        | Leave-one-year-out   | vs XGBoost | Dummy - XGBoost        | 2018, 2019, 2020, 2021 |     -0.0991 | -0.1740 | -0.0215 | 0.0120 | False        |   0.0360 | True                 |
| bdi        | Leave-one-year-out   | vs XGBoost | LogReg - XGBoost       | 2018, 2019, 2020, 2021 |      0.0139 | -0.0415 |  0.0722 | 0.6240 | False        |   1.0000 | False                |
| bdi        | Leave-one-year-out   | vs XGBoost | MLP-ERM - XGBoost      | 2018, 2019, 2020, 2021 |     -0.0016 | -0.0632 |  0.0615 | 0.9810 | False        |   1.0000 | False                |
| bdi        | Participant-disjoint | vs XGBoost | Dummy - XGBoost        |                        |     -0.1050 | -0.2634 |  0.0604 | 0.2190 | False        |   0.6570 | False                |
| bdi        | Participant-disjoint | vs XGBoost | LogReg - XGBoost       |                        |     -0.0090 | -0.1158 |  0.1116 | 0.8770 | False        |   0.8770 | False                |
| bdi        | Participant-disjoint | vs XGBoost | MLP-ERM - XGBoost      |                        |     -0.0551 | -0.1920 |  0.0840 | 0.4370 | False        |   0.8740 | False                |
