# PT-BR Localization Release Checks

A five-case preview for product teams testing Brazilian Portuguese releases.

The sample focuses on failures that often pass ordinary translation review but remain visible to Brazilian users: Portuguese-variant leakage, BRL formatting, Pix terminology, support tone and mobile UI expansion.

## Included cases

| Case | Risk | Severity |
| --- | --- | --- |
| BR-LOC-001 | European Portuguese language in a Brazilian account flow | Critical |
| BR-LOC-003 | Incorrect BRL separators and spacing | High |
| BR-LOC-005 | Unnatural Pix terminology and missing recovery guidance | High |
| BR-LOC-008 | Literal support language that sounds foreign or evasive | High |
| BR-LOC-013 | Expanded CTA text that can break a narrow interface | Medium |

## Files

- `data/ptbr_localization_release_checks.csv` — spreadsheet-friendly format
- `data/ptbr_localization_release_checks.jsonl` — automation and evaluation format
- `LICENSE.md` — preview-use terms

## How to use the sample

1. Run the source prompt or comparable product scenario.
2. Compare the observed output with the expected behavior.
3. Apply the acceptance criteria without rewriting them during review.
4. Treat any failed Critical or High case as a release blocker until corrected and retested.

## Full Starter Pack

The complete editable workbook contains 15 checks covering language, dates, currency, Pix, installments, CPF, phone numbers, addresses, variables, error recovery and interface behavior.

[Get the 15-check Starter Pack for US$9](https://payhip.com/b/CSdH7)

[Download the editable five-check preview](https://payhip.com/b/4fUHo) · [Brazil Ready QA store](https://payhip.com/BrazilReadyQA)

## Scope

This is a targeted release-risk sample, not a complete localization certification. It is designed for SaaS, apps, checkout flows, support systems and AI products shipping to Brazil.
