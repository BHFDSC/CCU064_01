Phenotype code lists related to the analysis conducted for this project:
- **preg_DB_codes.txt:** simple list of ICD and OPCS codes used to define a pregnancy / delivery event and diabetes through the HES APC data. Not a table to import, used for reference. The actual code in "2_HES_DB_diagnoses.Rmd" contains the codelist in a grep() call.
- **SDE_ethnicity_codes.txt:** table with codes used to define ethnicity in HES and GDPPR. A table to import.

The ICD10, OPCS and SNOMED codes used in the project can also be found in the submitted manuscript:
| Episode or Observation | Dataset | Code List |
| -- | -- | -- |
| Birth | HES APC Main | ICD10: O60 – O75, O80 – O84, Z37, Z38
| Birth | HES APC Main | OPCS4: P141 – P143, R14 – R19, R2, R30 – R32 |
| Loss | HES APC Main |	ICD10: O00 – O08 |
| Loss | HES APC Main |	OPCS4: Q101, Q102, Q111 – Q113, Q115 – Q116, Q14, R03 |
| Gestational Diabetes |HES APC Main | ICD10: O244 |
| Type 1 Diabetes | HES APC Main | ICD10: E10, O240 |
| Type 2 Diabetes | HES APC Main | ICD10: E11, O241 |
| Other Diabetes | HES APC Main | ICD10: E13, E14, G590, G632, H280, H360, M142, O243 |
| Height | MSDS Care Activities + Observations | SNOMED: 50373000, 248333004, 248327008 |
| Weight | MSDS Care Activities + Observations | SNOMED: 27113001, 363808001, 107647005 |
| Body Mass Index | MSDS Care Activities + Observations | SNOMED: 60621009 |
| Birth Weight | MSDS Baby Activities | SNOMED: 364589006, 27113001, 363808001 |


