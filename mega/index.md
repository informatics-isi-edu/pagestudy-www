---
layout: default
title: Multi-Ethnic Genotyping Array (MEGA)
---

PAGE II genotyped 50,000 samples using MEGA, an Illumina high density custom exomechip array, to continue emphasis on characterizing population-level disease risks in non-European-descent individuals. Cohorts in PAGE II are:  CALiCo (Causal Variants Across the Life Course, a consortium of ARIC, CARDIA, HCHS/SOL, Strong Heart Studies), ISMMS (Mount Sinai BioMe Biobank), MEC (Multiethnic Cohort), and WHI (Women’s Health Initiative).  PAGE is investigating anthropometric, cardiovascular, hypertension, kidney, inflammatory, lipid, T2D, and other traits.  

You can find information here about Illumina's MEGA:
* [Illumina Expanded Multi-Ethnic Genotyping Array MEGA-EX (from CIDR)](http://www.cidr.jhmi.edu/supported/mega-ex-data-sheet-370-2015-004.pdf)
* [Illumina Infinium Multi-Ethnic Global BeadChip](http://www.illumina.com/content/dam/illumina-marketing/documents/products/datasheets/multi-ethnic-global-data-sheet-370-2015-004.pdf)
* News article from [GenomeWeb](https://www.genomeweb.com/microarrays-multiplexing/illumina-collaborators-design-multi-ethnic-genotyping-array-empower-gwas)

You can find Illumina two strand translation files here:
* [Top to Forward Strand Translation](top_to_forward.txt)
* [Top to AB Strand Translation](top_to_AB.txt)

You can find the SNP submission file at dbSNP here:
* [View MEGA SNP submission batch at dbSNP](http://www.ncbi.nlm.nih.gov/projects/SNP/snp_viewBatch.cgi?sbid=1062317)
* [Download MEGA SNP batch data (including original IDs, ssIDs, and rsIDs)](ftp://ftp.ncbi.nlm.nih.gov/snp/organisms/human_9606/viewBatch/snpBatch_ILLUMINA_1062317.gz)

You can also find 637 SNP annotations and 575 Indel annotations for the MEGA loci from [WGSA](https://sites.google.com/site/jpopgen/wgsa), as well as the PAGEII allele frequencies for each loci and population in PAGE. The package includes [tabix](http://www.htslib.org/doc/tabix.html) formatted files for faster selection. Note that the compressed annotations file is large (2.1GB). The `PAGEII_WGSA_MEGA_QC_Filtering.tar.gz` file describes sites that were removed before annotation, and quality control workflow applied.
