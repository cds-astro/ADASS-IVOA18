# Notebook example illustrating the state of the art of the CDS Python tools.

This notebook script combines different Python packages, most of them being developed by the CDS team through the past years. It is available here
as an example for amateurs and astronomers.
This script:
1. Retrieves two MOCs from the MOCServer (`astroquery.cds`).
2. Computes their intersection (MOCPy) and shows the resulting MOC in an aladin-lite view (`ipyal-
adin`).
3. Searches for a vizier table in optical regime having some observations in this MOC region (`astroquery.cds`).
4. Retrieves this table using `astroquery.vizier`.
5. Filters the table by the MOC (MOCPy) and adds the filtered table to the aladin view (`ipyaladin`) to see which observations from this table are really contained in the MOC.

# Launch ADASS 2018 tutorial notebook with binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cds-astro/ADASS-IVOA18/master?filepath=adass2018.ipynb)
