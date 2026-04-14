# Reference Calculations — 2025/26

Step-by-step workings for each test case using HMRC rules.

## Rates

- Personal allowance: £12,570 (tapers £1 per £2 over £100k)
- Basic 20%: £0–£37,700 | Higher 40%: £37,700–£125,140
- NI: primary threshold £12,570, UEL £50,270, main 8%, upper 2%
- Student loan Plan 2 threshold: £28,470 @ 9%

## Case A — £45,000, 5% NET pay pension, Plan 2

| Step | Working | Value |
|---|---|---|
| Gross | | £45,000 |
| Pension | 45,000 × 5% | £2,250 |
| Taxable gross | 45,000 − 2,250 | £42,750 |
| PA | 42,750 < 100k | £12,570 |
| Taxable income | 42,750 − 12,570 | £30,180 |
| Tax: basic | 30,180 × 20% | £6,036 |
| **Tax total** | | **£6,036** |
| NI: main | (45,000 − 12,570) × 8% | £2,594.40 |
| **NI total** | | **£2,594.40** |
| Student loan | (45,000 − 28,470) × 9% | £1,487.70 |
| **Net** | 45,000 − 2,250 − 6,036 − 2,594.40 − 1,487.70 | **£32,631.90** |

Cross-check: Salary Calc £32,632.

## Case B — £110,000, 10% NET pay pension, no student loan

| Step | Working | Value |
|---|---|---|
| Gross | | £110,000 |
| Pension | 110,000 × 10% | £11,000 |
| Taxable gross | 110,000 − 11,000 | £99,000 |
| PA | 99,000 < 100k | £12,570 |
| Taxable income | 99,000 − 12,570 | £86,430 |
| Tax: basic | 37,700 × 20% | £7,540 |
| Tax: higher | (86,430 − 37,700) × 40% | £19,492 |
| **Tax total** | 7,540 + 19,492 | **£27,032** |
| NI: main | (50,270 − 12,570) × 8% | £3,016 |
| NI: upper | (110,000 − 50,270) × 2% | £1,194.60 |
| **NI total** | 3,016 + 1,194.60 | **£4,210.60** |
| **Net** | 110,000 − 11,000 − 27,032 − 4,210.60 | **£67,757.40** |

Cross-check: MSE £67,757, Salary Calc £67,757.

PA taper uses adjusted net income (taxable gross £99k). The 10%
NET pay pension brings adjusted income below £100k, preserving
the full personal allowance.

## Case C — £135,000, £20k salary sacrifice, Plan 2

| Step | Working | Value |
|---|---|---|
| Gross | | £135,000 |
| Salary sacrifice | | £20,000 |
| Contractual pay | 135,000 − 20,000 | £115,000 |
| PA taper | (115,000 − 100,000) ÷ 2 | −£7,500 |
| Effective PA | 12,570 − 7,500 | £5,070 |
| Taxable income | 115,000 − 5,070 | £109,930 |
| Tax: basic | 37,700 × 20% | £7,540 |
| Tax: higher | (109,930 − 37,700) × 40% | £28,892 |
| **Tax total** | 7,540 + 28,892 | **£36,432** |
| NI: main | (50,270 − 12,570) × 8% | £3,016 |
| NI: upper | (115,000 − 50,270) × 2% | £1,294.60 |
| **NI total** | 3,016 + 1,294.60 | **£4,310.60** |
| Student loan | (115,000 − 28,470) × 9% | £7,787.70 |
| **Net** | 135,000 − 20,000 − 36,432 − 4,310.60 − 7,787.70 | **£66,469.70** |

Cross-check: UK Tax Calc £66,470 (student loan £7,788).

Student loan is calculated on contractual pay (£115k), not
original gross (£135k). HMRC treats salary sacrifice the same
as NI — the sacrificed amount is not pensionable or repayable
earnings.
