# Code supplement to Chronotype_Neurobiological_Basis Study

This repository contains the code used to analysis the data presented in the "Multimodal population study reveals the neurobiological underpinnings of chronotype" paper.
Current citation: https://doi.org/10.1038/s41562-025-02182-w

Scripts are saved in `scrpit/` folder：
1. `LDA_analysis.ipynb` is an analysis scripts to investigate the multivariate brain patterns linked to chronotype.
2. `PLS_actigraphy.ipynb` is an analysis scripts to investigate the cross-associations between brain patterns and daily activity patterns.

Results are save in `results/` folder：
1. `LDA_sMRI_coef_5-95CI_all.csv` is the result of LDA analysis on strutual MRI with 5-95% confidence interval.
2. `LDA_dMRI_coef_5-95CI_all.csv` is the result of LDA analysis on diffusion MRI with 5-95% confidence interval.
3. `LDA_sexdiff_sMRI_coef_5-95CI_all.csv` is the result of sex differences analysis on strutual MRI with 5-95% confidence interval.
4. `LDA_sexdiff_dMRI_coef_5-95CI_all.csv` is the result of sex differences analysis analysis on diffusion MRI with 5-95% confidence interval. 
5. `PLS_Sig_x_loading.csv` is x loadings derived from the PLS analysis. Each column in the x loadings corresponds to a latent component, and each row corresponds to an brain feature.
6. `PLS_Sig_y_loading.csv` is the y loadings derived from the PLS analysis. Each column in the x loadings corresponds to a latent component, and each row corresponds to each hour of the day.
7. `Phewas_chronotype_hits.csv` is the results of PheWAS analysis (hits above BON correction).
8. `Phewas_corrdf_all.csv` is the full results of PheWAS analysis.
