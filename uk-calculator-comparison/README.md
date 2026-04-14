# UK Take-Home Pay Calculator Comparison

Data behind the [UK Calculator Comparison](https://casomo.co.uk/articles/uk-calculator-comparison) article.

Six UK take-home pay calculators tested across four scenarios covering pension handling, salary sacrifice, student loans, and tax code support.

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
| [test-cases.md](test-cases.md) | The four test scenarios |
| [reference-values-2025-26.md](reference-values-2025-26.md) | Correct values — 2025/26 |
| [reference-values-2026-27.md](reference-values-2026-27.md) | Correct values — 2026/27 |
| [reference-calculations-2025-26.md](reference-calculations-2025-26.md) | Step-by-step workings — 2025/26 |
| [reference-calculations-2026-27.md](reference-calculations-2026-27.md) | Step-by-step workings — 2026/27 |

## Feature Grids

| File | Description |
|---|---|
| [features-core.md](features-core.md) | Core feature comparison |
| [features-income.md](features-income.md) | Income input support |
| [features-pension.md](features-pension.md) | Pension handling comparison |
| [features-student-loans.md](features-student-loans.md) | Student loan support |
| [features-other.md](features-other.md) | Tax code, allowances, CGT |
| [features-ux.md](features-ux.md) | Openness and UX |

## Accuracy Results — 2025/26

| File | Description |
|---|---|
| [accuracy-2025-26-case-a.md](accuracy-2025-26-case-a.md) | Case A — Baseline PAYE |
| [accuracy-2025-26-case-b.md](accuracy-2025-26-case-b.md) | Case B — Personal Allowance Taper |
| [accuracy-2025-26-case-c.md](accuracy-2025-26-case-c.md) | Case C — Salary Sacrifice Stress |

## Sources

- HMRC income tax rates: [GOV.UK](https://www.gov.uk/income-tax-rates)
- NI thresholds: [GOV.UK](https://www.gov.uk/government/publications/rates-and-allowances-national-insurance-contributions/rates-and-allowances-national-insurance-contributions)
- Student loan repayment thresholds: [GOV.UK](https://www.gov.uk/repaying-your-student-loan)
