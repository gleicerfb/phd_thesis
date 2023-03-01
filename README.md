# phd_thesis


mageck count > output of mageck count includes a raw count table ‘count.txt’, a normalized count table
‘count_normalized.txt’ and a summary table of the mapping results ‘countsummary.txt (including total reads, mapped reads, mapped percentage, zero-count number and Gini index of each sample)’

mageck mle > output includes a ‘log’ file, a ‘gene_summary’ file (including gene beta scores of the conditions specified in the design matrix, except for the initial condition, and the associated statistics) and a ‘sgrna_summary’ file (including sgRNA efficiency probability predictions). ‘p-value’ is calculated by randomly permuting sgRNA labels. The ‘fdr’ is calculated by the Benjamini–Hochberg procedure. Similarly, the ‘wald-p-value’ and ‘wald-fdr’ are the P value and FDR, respectively, calculated by the Wald test to determine whether the corresponding ‘beta score’ differs substantially from zero in the MAGeCK MLE model.

MAGeCKFlute > FluteMLE > uses the ‘gene_summary’ file, which is the output of MAGeCK MLE, as its input. Performs QC analysis of beta scores (distribution of the beta score for different conditions, linear fitting of the beta scores of essential genes and an MA plot. 
