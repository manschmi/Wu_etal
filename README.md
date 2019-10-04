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
* analysis/clusters/cluster_genomic_annotation.Rmd
* analysis/clusters/cluster_motifs.Rmd
* analysis/clusters/clusters_in_intron1.Rmd
* analysis/clusters/clusters_in_eRNAs.Rmd
* analysis/clusters/clusters_vs_CLIPdb.Rmd
* analysis/clusters/cluster_pAstatus.Rmd


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
Aggregate 3'end signals into clusters. Add summit position within each cluster as extra info. Count sifnal in clusters in all libraries and do DESeq of clusters for classification, includes PCA plots and normalization fo cluster counts.

#### classify_clusters.Rmd
Classify clusters as NEXT, PAXT, NEXT+PAXT or not sig. 
Violin plots of normalized counts for each group and total coverage and signals in the various groups.
Save annotations as bed file, including a file for cluster summit positions.

#### cluster_3endseq_metagene.Rmd
3'end seq data metagene relative to cluster summit.

#### clusters_in_intron1.Rmd
3'end seq data metagene relative to cluster summit for subset of clusters in intron1.

#### clusters_in_eRNAs.Rmd
3'end seq data metagene relative to cluster summit for subset of clusters in eRNA regions.

#### cluster_genomic_annotation.Rmd
Intersect cluster positions with Gencode annotations.

#### cluster_motifs.Rmd
Hexamer and nucleotides at around cluster summit.

#### clusters_vs_CLIPdb.Rmd
NEXT vs PAXT cluster querying against CLIP data from CLIPdb.

#### cluster_pAstatus.Rmd
pA status of clusters.
