---
title: "PeptideCluster: Unsupervised Hierarchical Clustering of Peptide Sequences for Identification of Strong Covalent Inhibitors"
excerpt: "Software workflow developed to support a novel peptide discovery platform at the Bogyo Lab."
collection: portfolio
---

PeptideCluster is a software workflow that was developed as part of an effort to harness high-throughput sequencing data generated from 
phage display experiments to identify target-binding peptides and target-binded peptide motifs. This pipeline is composed of 5 main steps,

1. Process Raw Sequencing Data: Takes an input FASTQ file, separates reads by barcode, applies a quality filter to remove low-quality sequences, and then the remaining sequences are translated into their respective amino acid sequences and their abundances are totaled and normalized.
2. Visualization of Processed Sequences (Optional): Receives normalized peptide sequences and creates plots for the distribution of sequences by property (i.e. peptide ring size for bicyclic peptides) and allows for comparisons of processed sequences between display sequencing rounds (i.e. across datasets).
3. Select Abundant Peptides and Cluster: Select the top N most abundant peptides by normalized counts and/or specific properties. Cluster peptides
based on a bottom-up unsupervised hierarchical clustering algorithm that involves sequence similarity calculated with a BLOSUM62 matrix and a custom hydrophobicity score.
5. Identify conserved motifs: Index sequences to identify 1-D motifs for each and optionally, cluster sequences by shared 1-D motifs. 
6. Generate final report: Print out two files, one containing the peptides partitioned by cluster and one containing conserved motifs and their associated sequences across the abundant peptides.


_Workflow helped save 3-5 weeks of manual peptide screening during phage display campaigns_
