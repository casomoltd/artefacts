# AfC Pay Data

Machine-readable NHS Agenda for Change pay scales and pension
contribution tiers, one file per tax year.

## Pay Scales

Each `scales-YYYY-YY.yaml` contains:

- `source` — data attribution
- `uplift` — percentage increase from the previous year
- `hcas` — High Cost Area Supplement zones
  - `innerLondon`, `outerLondon`, `fringe`
    - `rate` — percentage supplement
    - `min` — minimum annual supplement in £
    - `max` — maximum annual supplement in £
- `bands[]` — array of pay bands (Band 2 through Band 9)
  - `band` — identifier ("2", "5", "8a", etc.)
  - `label` — display name
  - `slug` — URL slug for the band page
  - `roles` — short role summary
  - `roleContext` — career context for prose sections
  - `points[]` — pay points within the band
    - `label` — progression label (e.g. "Year 1")
    - `salary` — annual gross salary in £

Band 1 closed to new entrants in December 2018.

## Pension Tiers

Each `pension-tiers-YYYY-YY.csv` contains NHS Pension Scheme
contribution tiers for England and Wales. Scotland has a
separate pension scheme and is not covered.

Columns:

- `tier` — 1-based tier number
- `min` — lower salary boundary in £
- `max` — upper salary boundary in £ (empty for the top tier,
  meaning no upper limit)
- `rate` — contribution rate as a decimal (e.g. 0.052 = 5.2%)

The rate applies to the entire salary (not just the portion
within the band). 2023-24 used 11 pre-reform tiers; 2024-25
onward uses 6 post-reform tiers.

## Sources

- **Pay rates:** [NHS Employers pay scales 2025/26](https://www.nhsemployers.org/articles/pay-scales-202526)
- **Pension tiers:** [NHS BSA contribution rates 2025/26](https://www.nhsbsa.nhs.uk/nhs-pensions-contribution-rates-202526)
- **Tax and NI:** [HMRC rates and allowances 2025/26](https://www.gov.uk/government/publications/rates-and-allowances-income-tax/income-tax-rates-and-allowances-current-and-past)
- **Roles:** [NHS Health Careers AfC pay rates](https://www.healthcareers.nhs.uk/working-health/working-nhs/nhs-pay-and-benefits/agenda-change-pay-rates)
