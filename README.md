# Mobile elements expression along the trematode *Fasciola hepatica* life cycle

## Introduction
Transposable elements (TEs) are highly repetitive mobile sequences, which play diverse roles in genome regulation. As well, it is expected that TEs participate in lncRNAs function. In trematodes, lncRNA might be involved in development processes and life cycle regulation. For future studies it is significant to explore connection between TEs expression and developmental stages.

## Mission
Our study is devoted to detecting transposons in transcriptomes of different life-cycle stages of *F. hepatica* and analyzing their differential expression across stages.

## Goals:
1. Create mapping of RNA-seq data onto a list of transposons sequences
2. Quantify expression from mappings for each transposon
3. Normalize TE data using statistical approach
4. Discover differentially expressed TEs on each stage of *F. hepatica* life cycle

## Methods
### *F. hepatica* RNA-seq data
For our purposes we used public data which can be found in SRA NCBI archive.

*Accessions:* [Table S1](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/Table_s1.csv)
### List of *F. hepatica* TEs
As well we applied fasta file with repeatitive elements of *F.hepatica* genome (GCA_948099385.1), created earlier with the help of RepeatModeler tool: [Repeat database](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/f_hepatica_repeatbase.fasta)

### Workflow
![workflow](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/scheme.jpg)

## Results
[Kallisto and sleuth results](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/tree/main/f_kallisto)

[Venn diagram, illustrating stage-specific and common expressed repeats](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/venn1.jpg)

[Jensen-Shannon divergence heatmap and PCA plot](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/sample_pca.jpg)

[Heatmap of top 20 differently expressed transposable elements among various TE classes](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/heatmaps_classes3.jpg)

[Volcano plots for each stage vs. adult](https://github.com/LisaSkalon/Mobile_elements_of_F.hepatica/blob/main/volcanoplots_new1.jpg)

