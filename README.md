# Working_on_UKB_RAP

This GitHub repository provides tutorials and scripts used to analyze population-level genotype data on UK Biobank Research Analysis Platform. For reseachers familiar with Unix and working on UK Biobank Data this README will probably be helpful.

### List of Contents

* __Concatenate_VCF_blocks__

  Since the WGS joint genotype data (VCF) for each chromosome available on UK Biobank RAP platform is divided into blocks, it is required to merge the blocks sequentially for further analysis. This script merges the blocks of joint VCFs of each chromosome. For merging the files "BCFtools Concat" has been used.
