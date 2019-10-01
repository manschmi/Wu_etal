## Analysis for Wu et al.

### Contents:
* analysis/CAGE_processing.Rmd
* analysis/RNAseq_processing.Rmd
* analysis/PROMPTs/PROMPT_annotations.Rmd
* analysis/PROMPTs/PROMPT_RNAseq_metagene.Rmd
* analysis/PROMPTs/PROMPT_NETseq_metagene.Rmd
* analysis/PROMPTs/PROMPT_motifs.Rmd
* analysis/3pseq_processing.Rmd
* analysis/PROMPTs/PROMPT_3pseq_metagene.Rmd
* analysis/clusters/aggregate_3p_signals_and_DESeq.Rmd
* analysis/clusters/classify_clusters.Rmd
* analysis/clusters/cluster_3endseq_metagene.Rmd
* analysis/clusters/cluster_motifs.Rmd


### Details:

#### CAGE_processing.Rmd
Retrieval of CAGE data from SRA, cleaning of reads, mapping, track creation, normalization, merging and aggregation into CAGE clusters

####  RNAseq_processing.Rmd
Cleaning of reads, mapping, track creation, normalization and merging for genome browsing tracks.

#### PROMPT_annotations.Rmd
Definition of PROMPT annotations used. Get RNAseq sensitivities. Plots based on RNAseq sensitivities.

#### PROMPT_RNAseq_metagene.Rmd
Metagene of RNAseq data in PROMPT regions.

#### PROMPT_NETseq_metagene.Rmd
Metagene of NETseq data in PROMPT regions.

#### 3pseq_processing.Rmd
Filtering, mapping and normalization of 3p seq data.

#### PROMPT_3pseq_metagene.Rmd
Metagene of 3'end seq data around PROMPT TES.

#### PROMPT_motifs.Rmd
Hexamer and nucleotides at PROMPT TSS and in region TSS to +5kb

#### aggregate_3p_signals_and_DESeq.Rmd
Aggregate 3'end signals into clusters and DESeq of clusters for classification, includes PCA plots and normalization fo cluster counts.

#### classify_clusters.Rmd
Classify clusters as NEXT, PAXT, NEXT+PAXT or not sig. Violin plots of normalized counts for each group and total coverage and signals in the various groups.

#### cluster_3endseq_metagene.Rmd
3'end seq data metagene relative to cluster summit.

#### cluster_motifs.Rmd
Hexamer and nucleotides at around cluster summit.