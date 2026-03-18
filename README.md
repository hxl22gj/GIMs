# GIMs
Gut immune modules files for manuscript "Target functional profiling reveals bacterial DL-endopeptidase promoting immune checkpoint blockade therapy efficacy".

GIM coverage and abundances in bacterial genomes and metagenomics datasets were derived from UniRef90 gene abundance (copy number) using customized script adapted from HUMAnN. Specifically, “humann_ regroup_table -c GIM3_reaction.tsv” were used to calculate reaction abundance from UniRef90 gene abundance (copy number), and then “humann --pathways-database GIM3_pathways.tsv” were used to calculate pathway abundance and coverage from reaction abundance.
