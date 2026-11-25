# CBIO+ Tools

Planning tools for projects that use the Census-Based, Impact-Oriented approach with Care Groups (CBIO+).

## Tools

- **CBIO+ Project Budget Calculator** (`budget-calculator/index.html`). A single-file browser tool that drafts a budget for a maternal and child health / nutrition project or a cardiometabolic (hypertension) project. Inputs are the catchment population, staffing ratios, the interventions switched on, and unit costs. It shows the budget by category, by funder (implementing organization and IGHA, with in-kind support as a memo) and by year, gives unit costs and a planning-level impact estimate. "Save this page" downloads a copy that reopens with the figures already set.

  **Download Excel budget** produces a workbook with two sheets. The Budget sheet lists the main parameters at the top (population, staffing ratios, project length, contingency / FOREX rate, exchange rate; the list differs for the two project types), then the budget by cost category with a subtotal for each, a contingency / FOREX reserve row, the total, and the total in local currency. Inputs are in blue. Quantities and costs are formulas, so the budget recalculates when an input is changed in Excel. The Settings sheet records every setting chosen in the tool.

  Cardiometabolic projects use the role names Leader Neighbor, Leader Neighbor Trainer and CHO / Promoter. The Meaningful app licence row is kept in both project types and starts at zero users.

## Using the tools

Each tool is one HTML file with no installation. Open it in a browser, or use the web address once GitHub Pages is turned on for this repository (Settings, Pages, deploy from the `main` branch, root folder):

- https://tdavismph.github.io/CBIOtools/
- https://tdavismph.github.io/CBIOtools/budget-calculator/

The calculator loads its fonts from Google Fonts when online and falls back to system fonts offline. All calculation runs in the browser; nothing is sent to a server.

## Notes

The calculator's figures are planning-level approximations. Verify local wages, ratios and prices before submitting a budget.
