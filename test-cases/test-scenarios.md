# Home Credit Voice Agent — Test Scenarios

This document provides a concise index of the test cases for the Home Credit Loan Against Property (LAP) voice agent built with Bolna AI.

Detailed recordings, transcripts, observed outcomes, and test statuses are documented in [`recordings/README.md`](../recordings/README.md).

## Recorded test cases

| Test | Scenario                                                               | Expected behavior                                                                                                                                                      | Recorded result                                                                                                                 |
| ---- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Successful eligibility assessment                                      | Collect all seven eligibility items, summarize the details, obtain customer confirmation, and communicate preliminary eligibility without guaranteeing final approval. | Pass for conversation flow; eligibility decision requires validation against assignment rules.                                  |
| 2    | Agricultural property                                                  | Identify agricultural property, disqualify immediately, and stop the checklist.                                                                                        | Pass                                                                                                                            |
| 3    | Original property documents unavailable                                | Clarify document availability; disqualify if the originals cannot be produced for verification.                                                                        | Pass                                                                                                                            |
| 4    | Loan amount exceeds ₹75 lakh; customer accepts cap but has cash income | Offer the ₹75 lakh maximum, continue if accepted, and disqualify when cash-based income is confirmed.                                                                  | Pass                                                                                                                            |
| 5    | Customer declines the ₹75 lakh alternative                             | Explain the offer limit and end the call if the customer insists on a higher amount.                                                                                   | Pass                                                                                                                            |
| 6    | Customer is busy                                                       | Ask for a preferred callback date/time and end the current call without continuing eligibility questions.                                                              | Pass                                                                                                                            |
| 7    | Invalid repayment tenure                                               | Disqualify tenure outside the permitted 3–15-year range and end the assessment.                                                                                        | Pass                                                                                                                            |
| 8    | Joint ownership with a family member                                   | Capture joint ownership, continue the checklist, and use corrected loan amount/tenure values when confirmed.                                                           | Pass for ownership and correction handling; eligibility decision requires review.                                               |
| 9    | Property owned entirely by someone else                                | Clarify whether the customer is a legal owner; do not assume sole or joint ownership or claim eligibility without sufficient information.                              | Pending — recording and transcript not yet added.                                                                               |
| 10   | Answers provided out of order                                          | Capture volunteered details, avoid duplicate questions, and ask only for missing information.                                                                          | Partial pass — the tenure range was not narrowed to one specific duration; eligibility decision requires review.                |
| 11   | Customer corrects a previous answer                                    | Update the loan amount and tenure to the latest confirmed values and reflect them in the final summary.                                                                | Pass for correction handling; eligibility decision requires review.                                                             |
| 12   | Customer gives a tenure range                                          | Ask the customer to choose one specific tenure and confirm it before completing the assessment.                                                                        | Partial pass — the agent accepted the 8–9-year range without selecting one exact duration.                                      |
| 13   | Customer asks about the interest rate                                  | Do not invent or estimate a rate; refer the customer to a senior loan expert. Return to a pending eligibility question if one remains.                                 | Partial pass — rate handling passed; returning to a pending question was not tested because the checklist was already complete. |

## Additional scenarios to test

These scenarios are part of the intended coverage but are not documented as completed recordings in `recordings/README.md`.

| Scenario                               | Expected behavior                                                                                                                                                           | Status                 |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| Existing property loan / EMI reduction | Stop the fresh-loan checklist and follow the appropriate specialist-routing flow. Do not claim a transfer or notification occurred unless the platform performs it.         | Pending recording      |
| Company name and variable rendering    | Verify that the configured customer, agent, and company names render correctly and that the agent does not say an incorrect company name or expose unresolved placeholders. | Pending dedicated test |

## Evaluation policy

- Mark a scenario as completed only after the corresponding call has been executed and its observed behavior documented.
- Distinguish successful conversation handling from successful business-rule validation.
- Do not mark preliminary eligibility as a business-rule pass until all applicable assignment rules have been verified.
