# Customer and Retail Geographic Analysis

**Author:** Cameron Batts

**Tools:** SAS Visual Analytics / SAS Viya

## Validation update - October 22, 2026

The 3-page PDF parsed successfully, a sampled dashboard page was rendered and reviewed, and repository file links were checked. The original export bytes are preserved. Native SAS interactions, report calculations, filters and forecasts were not rerun. Editable SAS report definitions are absent; projects without source tables remain static case studies. This is an asset/evidence audit, not certification of a functioning native dashboard.

[Aggregate validation record](Reports/validation_results.json). 
## Problem
Explore customer distribution and retail activity in a Europe-filtered SAS dashboard.

## Approach
Review the customer bubble map, retail KPI and PDF filter appendix. The appendix explicitly applies Continent Name = Europe to the customer map and order object.

## Findings
The export shows a Retail Sale KPI of 396K. No currency, period or aggregation definition is supplied. The 4 to 8.3K values belong to the customer-map size legend; 8.3K is not a verified total customer count. The Number of Orders object has no readable value in the PDF.

## Limitations
Source tables and the editable SAS report are absent. Country totals, sales units and filter propagation to the retail KPI cannot be recomputed. The map supports a Europe-filtered view, not a conclusion that Europe dominates worldwide customers. Interactive controls are visible but untested.

## Data and provenance
The earlier documentation called this real operational data, but no source table, license or provenance evidence is included. Treat it as an illustrative SAS dashboard with unverified provenance.

## Verification
PDF pages and repository assets reviewed; source data and native SAS interactions are unavailable.

## View the project
- [Analysis report](Reports/sas_customer_retail.html)
- [Portfolio analysis](https://cameron-batts.github.io/sas_customer_retail.html)
- [Original PDF export](Reports/Report%20Links%20on%20Apr%2025%2C%202026.pdf)

## Dashboard previews
![Customer Analysis](Images/Customer%20Analysis.png)

## Reproduce and inspect
Open the HTML report and original PDF. Rebuilding the dashboard requires the original SAS report definition, source tables and measure definitions; those files are not included.

The static exports are preserved as historical evidence. Their source captions and map attribution remain intact.
