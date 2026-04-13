# AfC Pay Scales

Machine-readable NHS Agenda for Change pay scales, one YAML
file per tax year.

## Format

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

## Sources

- **Pay rates:** [NHS Employers pay scales 2025/26](https://www.nhsemployers.org/articles/pay-scales-202526)
- **Pension tiers:** [NHS BSA contribution rates 2025/26](https://www.nhsbsa.nhs.uk/nhs-pensions-contribution-rates-202526)
- **Tax and NI:** [HMRC rates and allowances 2025/26](https://www.gov.uk/government/publications/rates-and-allowances-income-tax/income-tax-rates-and-allowances-current-and-past)
- **Roles:** [NHS Health Careers AfC pay rates](https://www.healthcareers.nhs.uk/working-health/working-nhs/nhs-pay-and-benefits/agenda-change-pay-rates)
