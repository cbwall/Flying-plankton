# Flying-plankton
Shurin Lab (UCSD) flying plankton collaboration


# Notes on cleaned data file

Hi all,

A few comments on the cleaned data I just uploaded.

If you haven't used .Rdata files before, use the function load() to pull in these files

This will load in 3 data frames directly to your environment: asv_table, taxonomy, and metadata

Quick description of each:

asv_table: data frame where rows are samples and columns are ASVs

taxonomy: data frame with the ASV Hash, full taxonomy, and taxonomy split by level (columns A-G)

metadata: data frame with metadata for samples, row names for asv_table align with the column "sample_name" within this data frame.
          rows should be in the same order as rows for the asv_table but please use the match() function or a similar function when linking the two data frames together.

