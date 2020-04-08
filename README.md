# nanoporeMK
This repository contains the scripts used in our manuscript "Evaluation of Full-Length Nanopore 16S Sequencing for Detection of Pathogens in Microbial Keratitis"

## Abstract:

Microbial keratitis is a leading cause of preventable blindness worldwide. Conventional sampling and culture techniques are time-consuming, with over 40% of cases being culture-negative. Nanopore sequencing technology is portable and capable of generating long sequencing reads in real-time. The aim of this study is to evaluate the potential of nanopore sequencing directly from clinical samples for the diagnosis of bacterial microbial keratitis. 

Using full-length 16S rRNA amplicon sequences from a defined mock microbial community, we evaluated and benchmarked our bioinformatics analysis pipeline for taxonomic assignment on three different 16S rRNA databases (NCBI 16S RefSeq, RDP, and SILVA) with clustering at 97%, 99% and 100% similarities. Next, we optimised the sample collection using an ex vivo porcine model of microbial keratitis to compare DNA recovery rates of 12 different collection methods: 21­gauge needle, PTFE membrane, Isohelix™ SK2, Sugi®Eyespear, Cotton, Rayon, Dryswab™, Hydraflock®, Albumin­coated, Purflock®, Purfoam and Polyester swabs. As a proof-of-concept study, we applied the sampling technique that provided the highest DNA recovery and the optimised bioinformatics pipeline on samples from prospective patients with suspected microbial keratitis comparing the nanopore sequencing results to standard microbiology culture methods.

We found that applying alignment filtering to nanopore sequencing reads and aligning to the NCBI 16S RefSeq database at 100% similarity, provided the most accurate species level assignment. DNA concentration recovery rates were significantly different between the collection methods (p<0.001), with Sugi®Eyespear swab providing the highest mean rank DNA concentration. Then, applying the optimised collection method and bioinformatics pipeline directly on two patients presenting with microbial keratitis, sequencing results from Patient A was in agreement with culture results, whilst Patient B, with negative culture results and previous antibiotic use, showed agreement between nanopore and Illumina Miseq sequencing results.

We have optimised collection methods and demonstrate a novel workflow for identification of bacterial microbial keratitis using nanopore sequencing. 

Link to raw fastq data:

Link to publication: pending

Cite as: pending

# Getting Started

These instructions will let you build full length 16S rRNA databases from NCBI 16S RefSeq, RDP and SILVA clustered at 97%, 99% and 100% similarity using CD-HIT. 

## Prerequisites

'''
pip install 
'''
