Analysis and curation code related to the analysis conducted for this project. All the code is also accessible within the CCU64 folder in RStudio Server in the NHS Data Access Environment.

Markdown Files:
1_cohort_selection.Rmd: Code to read HES data, clean and merge and define the cohort for the project. Produces:
  * merged_hes.Rds: preliminary dataset, after merging HES APC with HES Maternity.
  * clean_hes.Rds: final dataset with the base cohort information.

2_HES_DB_diagnoses.Rmd: Code to read HES data, select relevant entries and obtain diagnosis information. Produces:
  * hes_diags.Rds: preliminary dataset with HES APC diagnosis information (all diagnoses) for all individuals in the cohort.
  * diabetes_hes.Rds: final dataset with HES APC diagnosis of diabetes mellitus for the cohort. Reshaped to long format.
  * cohort_DB2: final clean cohort dataset including previous HES diabetes diagnosis per pregnancy.

3_GDPPR_ethno.Rmd: Code to read GDPPR data and select ethnicity from latest entries. Produces:
  * gdppr_ethno.Rds: dataset with latest ethnic identification from GDPPR.

4_MSDS_data.Rmd: Code to read MSDS mother and baby data, clean and merge to obtain additional variables. Produces:
  * BMI_MSDS.Rds: dataset containing BMI, height and weight information from MSDS.
  * baby_MSDS.Rds: dataset containing BW and birth order from MSDS.
  
5_data_prep.Rmd: Code to merge cohort and additional data together. Produces:
  * del_cohort.Rds: dataset merged, filtered and prepared for the analyses.

6_manuscript_output.Rmd: Code to produce the tables and figures accompanying the manuscript for publication.
