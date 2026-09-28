# PCR Gene Expression Report

The Day 90 PCR analysis compared the 50% DS, 21 Pa NorHA group with Matrigel. It included three biological replicates per group for each gene. Expression was normalized to GAPDH and calculated using the 2^(-ΔΔCt) method. Matrigel served as the calibrator. The saved analysis used Wilcoxon rank-sum tests on ΔΔCt values. The reported p-values were not adjusted for multiple comparisons.

No statistically significant differences were detected for SOX2, ASCL1, MAP2, NeuN, or SYNP. All reported p-values exceeded 0.05.

| Gene | 50% DS, 21 Pa | Matrigel | p-value |
|---|---:|---:|---:|
| SOX2 | 0.92 ± 0.36 | 1.06 ± 0.40 | 0.40 |
| ASCL1 | 1.28 ± 0.79 | 1.06 ± 0.42 | 1.00 |
| MAP2 | 2.59 ± 0.71 | 1.01 ± 0.18 | 0.10 |
| NeuN | 2.86 ± 0.04 | 1.02 ± 0.22 | 0.10 |
| SYNP | 3.79 ± 0.17 | 1.05 ± 0.40 | 0.10 |

Values are mean relative expression ± standard deviation, rounded to two decimal places. They are the reported 2^(-ΔΔCt) values, not ratios of the two group means.

SOX2 had a lower mean expression in the 50% DS, 21 Pa group than in Matrigel. ASCL1 had a slightly higher mean expression. Neither difference was statistically significant.

MAP2, NeuN, and SYNP had higher mean expression in the 50% DS, 21 Pa group. SYNP had the highest mean relative expression among the five genes in this group. Each of these three comparisons had a p-value of 0.10. The observed increases were not statistically significant.

These results show numerical differences in expression between the groups. They do not establish a statistically significant expression change for any of the five genes.

## Sources

- [Combined expression summary](qPCR_summary_allruns_combined.csv): group means, standard deviations, and sample counts.
- [Summary by run](qPCR_summary_by_run.csv): biological replicate counts and run identity.
- [Saved analysis report](Wilcox_Whitney_QuantStudio_XLSX.html): reported p-values and analysis output.
- [Analysis source](Wilcox_Whitney_QuantStudio_XLSX.qmd): normalization, calibration, and statistical test settings.
