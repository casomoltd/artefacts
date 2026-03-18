# NHS Take-Home Pay Calculator Comparison

Data behind the [NHS Calculator Comparison](https://casomo.co.uk/finance/nhs-calculator-comparison) article.

Seven NHS take-home pay calculators tested against five real scenarios using official NHSBSA salary figures and HMRC tax rates.

## Status Labels

Feature grids use five status labels:

| Symbol | Meaning |
|---|---|
| ✓ | Supported — feature is present and working |
| ✗ | Not available — feature is missing |
| ⚠ | Bugged — feature exists but has a defect |
| 🏷 | Mislabelled — feature is claimed but does not match what is shown |
| ? | Unknown — could not confirm |

Numbered footnotes below each table describe specific issues.

## Reference Data

| File | Description |
|---|---|
| [test-cases.md](test-cases.md) | The five test scenarios |
| [pension-tiers-2025-26.md](pension-tiers-2025-26.md) | NHS pension contribution tiers |
| [reference-values-2025-26.md](reference-values-2025-26.md) | Expected results for 2025/26 |
| [reference-values-2026-27.md](reference-values-2026-27.md) | Expected results for 2026/27 |

## Feature Grids

| File | Description |
|---|---|
| [features-core.md](features-core.md) | Core feature comparison |
| [features-nhs-inputs.md](features-nhs-inputs.md) | NHS-specific input support |
| [features-pension.md](features-pension.md) | Pension handling comparison |
| [features-student-loans.md](features-student-loans.md) | Student loan support |
| [features-additional.md](features-additional.md) | Additional features |
| [features-ux.md](features-ux.md) | Transparency and UX |
| [tracking-summary.md](tracking-summary.md) | Third-party tracking scripts |

## Accuracy Results — 2025/26

| File | Description |
|---|---|
| [accuracy-2025-26-case-a.md](accuracy-2025-26-case-a.md) | Case A — Band 5, FT, Baseline |
| [accuracy-2025-26-case-b.md](accuracy-2025-26-case-b.md) | Case B — Band 7, FT, Higher Tier |
| [accuracy-2025-26-case-c.md](accuracy-2025-26-case-c.md) | Case C — Band 8a, FT, Crosses UEL |
| [accuracy-2025-26-case-d.md](accuracy-2025-26-case-d.md) | Case D — Band 5, 0.6 FTE |
| [accuracy-2025-26-case-e.md](accuracy-2025-26-case-e.md) | Case E — Band 7, FT, Plan 2 |

## Accuracy Results — 2026/27

| File | Description |
|---|---|
| [accuracy-2026-27-case-a.md](accuracy-2026-27-case-a.md) | Case A — Band 5, FT, Baseline |
| [accuracy-2026-27-case-b.md](accuracy-2026-27-case-b.md) | Case B — Band 7, FT, Higher Tier |
| [accuracy-2026-27-case-c.md](accuracy-2026-27-case-c.md) | Case C — Band 8a, FT, Crosses UEL |
| [accuracy-2026-27-case-d.md](accuracy-2026-27-case-d.md) | Case D — Band 5, 0.6 FTE |
| [accuracy-2026-27-case-e.md](accuracy-2026-27-case-e.md) | Case E — Band 7, FT, Plan 2 |

## Sources

- AfC pay rates 2025/26: [NHSBSA KA-23570](https://faq-hrss.nhsbsa.nhs.uk/knowledgebase/article/KA-23570)
- AfC pay rates 2026/27: [NHS Health Careers](https://www.healthcareers.nhs.uk/working-health/working-nhs/nhs-pay-and-benefits/agenda-change-pay-rates)
- NHS pension tiers: [NHSBSA](https://www.nhsbsa.nhs.uk/member-hub/contribution-rates)
- HMRC tax and NI rates: [GOV.UK](https://www.gov.uk/income-tax-rates)
