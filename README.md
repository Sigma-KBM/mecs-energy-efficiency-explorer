# U.S. Manufacturing Energy-Efficiency Opportunity Explorer

**[Open the interactive Tableau dashboard →](https://public.tableau.com/views/MECSAEnergyEfficiencyDashboard/SectorOpportunityBenchmark?:showVizHome=no)**

[![Dashboard preview](https://public.tableau.com/views/MECSAEnergyEfficiencyDashboard/SectorOpportunityBenchmark.png?:showVizHome=no)](https://public.tableau.com/views/MECSAEnergyEfficiencyDashboard/SectorOpportunityBenchmark?:showVizHome=no)
Interactive portfolio analysis of U.S. manufacturing energy consumption, expenditure, and energy intensity using the U.S. Energy Information Administration’s Manufacturing Energy Consumption Survey (MECS) 2022.

## Business question

Which manufacturing sectors combine high energy cost exposure, high energy intensity, and the largest modeled opportunity for energy-expenditure reduction?

## Dashboard highlights

### Energy Cost Exposure — Top 15 U.S. Manufacturing Sectors

A scatter plot compares observed 2022 energy consumption and annual energy expenditure by sector.

- **X-axis:** Energy consumption (Trillion Btu)
- **Y-axis:** Energy expenditure ($M USD)
- **Bubble size:** Modeled annual energy-expenditure reduction under the selected scenario

### Energy Intensity Benchmark — Top 10 U.S. Manufacturing Sectors

A ranked bar chart compares energy intensity across sectors.

- **Metric:** Energy consumption per USD of shipments
- **Reference line:** Average of the displayed sectors
- **Purpose:** Identify sectors with comparatively high energy use relative to output

## Scenario modeling

Use the dashboard selector to explore modeled proportional energy-reduction scenarios of **5%, 10%, and 15%**.

Modeled annual reduction is calculated as a proportional reduction applied to observed sector-level energy expenditure. These values support prioritization and investigation; they are **not observed or realized savings**.

## How to use the dashboard

1. Select a 5%, 10%, or 15% reduction scenario.
2. Compare sectors in the cost-exposure map.
3. Use bubble size to identify larger modeled opportunities.
4. Review the energy-intensity benchmark for additional context.
5. Hover over marks for sector-level details.

## Data source and scope

- **Source:** U.S. Energy Information Administration (EIA), Manufacturing Energy Consumption Survey (MECS), 2022.
- **Population:** U.S. manufacturing sectors.
- **Observed measures:** Energy consumption, energy expenditure, and energy-intensity ratios.
- **Modeled measure:** Proportional reduction in annual energy expenditure.

The MECS is EIA’s national survey of energy use and expenditures in U.S. manufacturing establishments.

- [MECS 2022 data tables](https://www.eia.gov/consumption/manufacturing/data/2022/)
- [MECS methodology and data quality](https://www.eia.gov/consumption/manufacturing/data/2022/index.php?view=methodology)

## Tools and techniques

- Tableau Public
- Interactive parameters and calculated fields
- Scenario modeling
- Sector benchmarking
- Data visualization and portfolio storytelling

## Portfolio links

- [Interactive Tableau dashboard](https://public.tableau.com/views/MECSAEnergyEfficiencyDashboard/SectorOpportunityBenchmark?:showVizHome=no)
- [Tableau Public profile](https://public.tableau.com/app/profile/angel.manuel.marin)

## License

This project is released under the [MIT License](LICENSE).
