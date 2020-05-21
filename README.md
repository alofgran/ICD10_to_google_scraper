#

This tool utilizes the `icd10-cm` package, and a pre-generated collection of [ICD10 codes](https://en.wikipedia.org/wiki/ICD-10) in CSV format.  It ingests the CSV, uses the `icd10-cm` package to identify the code's description and billability, runs a Google search for each description, and scrapes data pertaining to each diagnosis.
