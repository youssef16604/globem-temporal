**Per-view paired comparisons against XGBoost (Holm-adjusted within view).**

| Analysis   | Protocol             | View                       | Comparison             |   Delta_AUC |   CI_lo |   CI_hi |      p | Equivalent   |   p_Holm |
|:-----------|:---------------------|:---------------------------|:-----------------------|------------:|--------:|--------:|-------:|:-------------|---------:|
| main       | Forward-chaining     | Forward → 2019             | Dummy - XGBoost        |     -0.0375 | -0.0962 |  0.0236 | 0.2080 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2019             | LogReg - XGBoost       |     -0.0063 | -0.0551 |  0.0394 | 0.8220 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2019             | MLP-ERM - XGBoost      |     -0.0071 | -0.0615 |  0.0414 | 0.7800 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2019             | GRU - XGBoost          |     -0.0203 | -0.0864 |  0.0400 | 0.5360 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2019             | Transformer - XGBoost  |     -0.0088 | -0.0653 |  0.0414 | 0.7520 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | Dummy - XGBoost        |     -0.0463 | -0.1288 |  0.0301 | 0.2660 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | LogReg - XGBoost       |     -0.0231 | -0.0952 |  0.0502 | 0.5410 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | MLP-ERM - XGBoost      |     -0.0157 | -0.0937 |  0.0672 | 0.6900 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | MLP-GroupDRO - XGBoost |     -0.0085 | -0.0863 |  0.0693 | 0.8430 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | MLP-IRM - XGBoost      |     -0.0210 | -0.0942 |  0.0562 | 0.6010 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | GRU - XGBoost          |      0.0009 | -0.0771 |  0.0768 | 0.9690 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2020             | Transformer - XGBoost  |      0.0123 | -0.0701 |  0.0966 | 0.7710 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | Dummy - XGBoost        |     -0.0928 | -0.1554 | -0.0321 | 0.0005 | False        |   0.0035 |
| main       | Forward-chaining     | Forward → 2021             | LogReg - XGBoost       |      0.0017 | -0.0418 |  0.0433 | 0.9590 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | MLP-ERM - XGBoost      |     -0.0094 | -0.0624 |  0.0388 | 0.7050 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | MLP-GroupDRO - XGBoost |      0.0061 | -0.0400 |  0.0511 | 0.8200 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | MLP-IRM - XGBoost      |      0.0235 | -0.0282 |  0.0737 | 0.3610 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | GRU - XGBoost          |     -0.0055 | -0.0596 |  0.0472 | 0.8380 | False        |   1.0000 |
| main       | Forward-chaining     | Forward → 2021             | Transformer - XGBoost  |     -0.0067 | -0.0748 |  0.0574 | 0.8550 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | Dummy - XGBoost        |     -0.0553 | -0.1162 |  0.0026 | 0.0650 | False        |   0.4550 |
| main       | Leave-one-year-out   | Leave-out 2018             | LogReg - XGBoost       |     -0.0197 | -0.0673 |  0.0320 | 0.4330 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | MLP-ERM - XGBoost      |     -0.0281 | -0.0874 |  0.0308 | 0.3620 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | MLP-GroupDRO - XGBoost |     -0.0343 | -0.0895 |  0.0223 | 0.2370 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | MLP-IRM - XGBoost      |     -0.0258 | -0.0783 |  0.0239 | 0.3280 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | GRU - XGBoost          |     -0.0126 | -0.0790 |  0.0474 | 0.7180 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2018             | Transformer - XGBoost  |      0.0006 | -0.0682 |  0.0626 | 0.9280 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | Dummy - XGBoost        |     -0.0555 | -0.1157 | -0.0003 | 0.0490 | False        |   0.3430 |
| main       | Leave-one-year-out   | Leave-out 2019             | LogReg - XGBoost       |     -0.0093 | -0.0609 |  0.0402 | 0.7360 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | MLP-ERM - XGBoost      |     -0.0074 | -0.0631 |  0.0419 | 0.8000 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | MLP-GroupDRO - XGBoost |     -0.0211 | -0.0766 |  0.0282 | 0.4520 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | MLP-IRM - XGBoost      |     -0.0179 | -0.0701 |  0.0323 | 0.5140 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | GRU - XGBoost          |     -0.0166 | -0.0778 |  0.0390 | 0.5820 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2019             | Transformer - XGBoost  |     -0.0199 | -0.0786 |  0.0374 | 0.5170 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | Dummy - XGBoost        |     -0.1063 | -0.1765 | -0.0295 | 0.0040 | False        |   0.0280 |
| main       | Leave-one-year-out   | Leave-out 2020             | LogReg - XGBoost       |     -0.0069 | -0.0644 |  0.0573 | 0.8190 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | MLP-ERM - XGBoost      |     -0.0161 | -0.0846 |  0.0512 | 0.6460 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | MLP-GroupDRO - XGBoost |     -0.0218 | -0.0989 |  0.0526 | 0.6120 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | MLP-IRM - XGBoost      |     -0.0150 | -0.0732 |  0.0528 | 0.6500 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | GRU - XGBoost          |     -0.0329 | -0.1003 |  0.0394 | 0.3790 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2020             | Transformer - XGBoost  |     -0.0114 | -0.0834 |  0.0590 | 0.8050 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | Dummy - XGBoost        |     -0.0928 | -0.1554 | -0.0321 | 0.0005 | False        |   0.0035 |
| main       | Leave-one-year-out   | Leave-out 2021             | LogReg - XGBoost       |      0.0017 | -0.0418 |  0.0433 | 0.9590 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | MLP-ERM - XGBoost      |     -0.0094 | -0.0624 |  0.0388 | 0.7050 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | MLP-GroupDRO - XGBoost |      0.0061 | -0.0400 |  0.0511 | 0.8200 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | MLP-IRM - XGBoost      |      0.0235 | -0.0282 |  0.0737 | 0.3610 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | GRU - XGBoost          |     -0.0055 | -0.0596 |  0.0472 | 0.8380 | False        |   1.0000 |
| main       | Leave-one-year-out   | Leave-out 2021             | Transformer - XGBoost  |     -0.0067 | -0.0748 |  0.0574 | 0.8550 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | Dummy - XGBoost        |     -0.0768 | -0.1455 | -0.0049 | 0.0360 | False        |   0.2520 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | LogReg - XGBoost       |      0.0221 | -0.0310 |  0.0828 | 0.4360 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | MLP-ERM - XGBoost      |      0.0195 | -0.0327 |  0.0749 | 0.4570 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | MLP-GroupDRO - XGBoost |      0.0100 | -0.0473 |  0.0687 | 0.7520 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | MLP-IRM - XGBoost      |      0.0164 | -0.0370 |  0.0708 | 0.5420 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | GRU - XGBoost          |     -0.0183 | -0.0827 |  0.0487 | 0.5910 | False        |   1.0000 |
| main       | Participant-disjoint | Participant-disjoint 80/20 | Transformer - XGBoost  |     -0.0022 | -0.0694 |  0.0689 | 0.9490 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2020             | Dummy - XGBoost        |     -0.0882 | -0.1594 | -0.0187 | 0.0160 | False        |   0.0800 |
| ex2018     | Forward-chaining     | Forward → 2020             | LogReg - XGBoost       |     -0.0177 | -0.0799 |  0.0426 | 0.5490 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2020             | MLP-ERM - XGBoost      |     -0.0289 | -0.0955 |  0.0461 | 0.4540 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2020             | GRU - XGBoost          |     -0.0385 | -0.1098 |  0.0305 | 0.2640 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2020             | Transformer - XGBoost  |     -0.0337 | -0.1346 |  0.0497 | 0.4610 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2021             | Dummy - XGBoost        |     -0.1139 | -0.1773 | -0.0517 | 0.0020 | False        |   0.0140 |
| ex2018     | Forward-chaining     | Forward → 2021             | LogReg - XGBoost       |      0.0001 | -0.0420 |  0.0404 | 0.9890 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2021             | MLP-ERM - XGBoost      |     -0.0171 | -0.0641 |  0.0294 | 0.5020 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2021             | MLP-GroupDRO - XGBoost |     -0.0162 | -0.0715 |  0.0338 | 0.5130 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2021             | MLP-IRM - XGBoost      |     -0.0124 | -0.0624 |  0.0326 | 0.6260 | False        |   1.0000 |
| ex2018     | Forward-chaining     | Forward → 2021             | GRU - XGBoost          |     -0.0444 | -0.1020 |  0.0154 | 0.1560 | False        |   0.9360 |
| ex2018     | Forward-chaining     | Forward → 2021             | Transformer - XGBoost  |     -0.0258 | -0.0940 |  0.0405 | 0.4880 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | Dummy - XGBoost        |     -0.0518 | -0.1108 |  0.0045 | 0.0790 | False        |   0.5530 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | LogReg - XGBoost       |      0.0008 | -0.0457 |  0.0519 | 0.9910 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | MLP-ERM - XGBoost      |      0.0021 | -0.0508 |  0.0568 | 0.9600 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | MLP-GroupDRO - XGBoost |     -0.0061 | -0.0632 |  0.0533 | 0.7960 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | MLP-IRM - XGBoost      |     -0.0153 | -0.0683 |  0.0437 | 0.5940 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | GRU - XGBoost          |     -0.0193 | -0.0749 |  0.0387 | 0.5310 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2019             | Transformer - XGBoost  |     -0.0205 | -0.0778 |  0.0361 | 0.4970 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | Dummy - XGBoost        |     -0.1073 | -0.1747 | -0.0337 | 0.0120 | False        |   0.0840 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | LogReg - XGBoost       |     -0.0017 | -0.0558 |  0.0548 | 0.9790 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | MLP-ERM - XGBoost      |     -0.0051 | -0.0620 |  0.0568 | 0.9040 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | MLP-GroupDRO - XGBoost |     -0.0153 | -0.0714 |  0.0405 | 0.6090 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | MLP-IRM - XGBoost      |     -0.0128 | -0.0700 |  0.0493 | 0.6950 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | GRU - XGBoost          |     -0.0167 | -0.0778 |  0.0493 | 0.6510 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2020             | Transformer - XGBoost  |     -0.0287 | -0.1039 |  0.0443 | 0.4760 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | Dummy - XGBoost        |     -0.1139 | -0.1773 | -0.0517 | 0.0020 | False        |   0.0140 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | LogReg - XGBoost       |      0.0001 | -0.0420 |  0.0404 | 0.9890 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | MLP-ERM - XGBoost      |     -0.0171 | -0.0641 |  0.0294 | 0.5020 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | MLP-GroupDRO - XGBoost |     -0.0162 | -0.0715 |  0.0338 | 0.5130 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | MLP-IRM - XGBoost      |     -0.0124 | -0.0624 |  0.0326 | 0.6260 | False        |   1.0000 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | GRU - XGBoost          |     -0.0444 | -0.1020 |  0.0154 | 0.1560 | False        |   0.9360 |
| ex2018     | Leave-one-year-out   | Leave-out 2021             | Transformer - XGBoost  |     -0.0258 | -0.0940 |  0.0405 | 0.4880 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | Dummy - XGBoost        |     -0.1025 | -0.1853 | -0.0252 | 0.0100 | False        |   0.0700 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | LogReg - XGBoost       |      0.0270 | -0.0401 |  0.0941 | 0.4420 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | MLP-ERM - XGBoost      |      0.0196 | -0.0509 |  0.0849 | 0.5740 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | MLP-GroupDRO - XGBoost |      0.0100 | -0.0613 |  0.0807 | 0.8350 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | MLP-IRM - XGBoost      |      0.0180 | -0.0588 |  0.0870 | 0.6130 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | GRU - XGBoost          |     -0.0146 | -0.1052 |  0.0705 | 0.7550 | False        |   1.0000 |
| ex2018     | Participant-disjoint | Participant-disjoint 80/20 | Transformer - XGBoost  |      0.0093 | -0.0708 |  0.0846 | 0.8110 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2019             | Dummy - XGBoost        |     -0.0435 | -0.2121 |  0.1137 | 0.6180 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2019             | LogReg - XGBoost       |     -0.0180 | -0.1370 |  0.1157 | 0.7860 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2019             | MLP-ERM - XGBoost      |     -0.0239 | -0.1691 |  0.1248 | 0.7300 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2020             | Dummy - XGBoost        |     -0.1025 | -0.2770 |  0.0901 | 0.2780 | False        |   0.8340 |
| bdi        | Forward-chaining     | Forward → 2020             | LogReg - XGBoost       |      0.0348 | -0.1033 |  0.1818 | 0.6660 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2020             | MLP-ERM - XGBoost      |      0.0090 | -0.1406 |  0.1653 | 0.9060 | False        |   1.0000 |
| bdi        | Forward-chaining     | Forward → 2021             | Dummy - XGBoost        |     -0.1330 | -0.2771 |  0.0027 | 0.0580 | False        |   0.1740 |
| bdi        | Forward-chaining     | Forward → 2021             | LogReg - XGBoost       |     -0.0219 | -0.1244 |  0.0756 | 0.6620 | False        |   0.7760 |
| bdi        | Forward-chaining     | Forward → 2021             | MLP-ERM - XGBoost      |     -0.0491 | -0.1639 |  0.0562 | 0.3880 | False        |   0.7760 |
| bdi        | Leave-one-year-out   | Leave-out 2018             | Dummy - XGBoost        |     -0.0889 | -0.2315 |  0.0623 | 0.2620 | False        |   0.7860 |
| bdi        | Leave-one-year-out   | Leave-out 2018             | LogReg - XGBoost       |      0.0381 | -0.0827 |  0.1595 | 0.4900 | False        |   0.9800 |
| bdi        | Leave-one-year-out   | Leave-out 2018             | MLP-ERM - XGBoost      |      0.0308 | -0.1086 |  0.1678 | 0.6600 | False        |   0.9800 |
| bdi        | Leave-one-year-out   | Leave-out 2019             | Dummy - XGBoost        |     -0.0872 | -0.2382 |  0.0633 | 0.2660 | False        |   0.7980 |
| bdi        | Leave-one-year-out   | Leave-out 2019             | LogReg - XGBoost       |     -0.0204 | -0.1242 |  0.0826 | 0.7040 | False        |   1.0000 |
| bdi        | Leave-one-year-out   | Leave-out 2019             | MLP-ERM - XGBoost      |     -0.0294 | -0.1341 |  0.0840 | 0.6070 | False        |   1.0000 |
| bdi        | Leave-one-year-out   | Leave-out 2020             | Dummy - XGBoost        |     -0.0871 | -0.2615 |  0.0843 | 0.3180 | False        |   0.9540 |
| bdi        | Leave-one-year-out   | Leave-out 2020             | LogReg - XGBoost       |      0.0599 | -0.0706 |  0.1957 | 0.3880 | False        |   0.9540 |
| bdi        | Leave-one-year-out   | Leave-out 2020             | MLP-ERM - XGBoost      |      0.0413 | -0.0963 |  0.1708 | 0.5310 | False        |   0.9540 |
| bdi        | Leave-one-year-out   | Leave-out 2021             | Dummy - XGBoost        |     -0.1330 | -0.2771 |  0.0027 | 0.0580 | False        |   0.1740 |
| bdi        | Leave-one-year-out   | Leave-out 2021             | LogReg - XGBoost       |     -0.0219 | -0.1244 |  0.0756 | 0.6620 | False        |   0.7760 |
| bdi        | Leave-one-year-out   | Leave-out 2021             | MLP-ERM - XGBoost      |     -0.0491 | -0.1639 |  0.0562 | 0.3880 | False        |   0.7760 |
| bdi        | Participant-disjoint | Participant-disjoint 80/20 | Dummy - XGBoost        |     -0.1050 | -0.2634 |  0.0604 | 0.2190 | False        |   0.6570 |
| bdi        | Participant-disjoint | Participant-disjoint 80/20 | LogReg - XGBoost       |     -0.0090 | -0.1158 |  0.1116 | 0.8770 | False        |   0.8770 |
| bdi        | Participant-disjoint | Participant-disjoint 80/20 | MLP-ERM - XGBoost      |     -0.0551 | -0.1920 |  0.0840 | 0.4370 | False        |   0.8740 |
