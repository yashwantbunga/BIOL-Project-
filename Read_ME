# Lung Tissue Classification Using Gene Expression

**Team:** Yashwant Bunga and Vinay Ilapuram  
**Course:** BIOL 5340 – Bioinformatics

## Research Question

Can 100 gene-expression probe sets classify lung tumor and non-tumor tissue with balanced accuracy no more than five percentage points below 500 probe sets?

## Dataset

The project uses the publicly available GSE10072 dataset from NCBI GEO.

- 107 lung tissue samples: 58 tumor and 49 non-tumor
- 74 patients
- 22,283 expression probe sets
- Affymetrix Human Genome U133A microarray platform

The notebook automatically downloads the processed expression data and probe annotations. No manual dataset upload is required.

Dataset: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10072

## Work Completed

### Phase 1
- Downloaded expression data and annotations.
- Checked sample labels, missing values, and expression ranges.
- Identified patient codes and created five validation folds.
- Kept samples from the same patient together to prevent overlap between training and evaluation.

### Initial Phase 2
- Compared logistic regression and random forest using 100 and 500 selected probe sets.
- Evaluated a dummy classifier as a baseline.
- Generated performance tables, a comparison plot, and confusion matrices.
- Compared the two feature-set sizes using paired fold scores.

Biological interpretation of selected probes and the final report are still in progress.

## Methods

Feature selection and preprocessing are fitted only on training samples within each fold. The same folds are used for every model.

Evaluation measures:
- Balanced accuracy
- Tumor-class F1 score
- ROC-AUC
- Confusion matrices




## Limitations

The analysis uses one small dataset and the original study's processed expression values. Cross-validation performance does not establish clinical usefulness or performance on an independent cohort. Probe sets do not always correspond to unique genes.

## Reference

Landi et al. (2008). Gene expression signature of cigarette smoking and its role in lung adenocarcinoma development and survival. PLoS ONE, 3(2), e1651.
https://doi.org/10.1371/journal.pone.0001651
