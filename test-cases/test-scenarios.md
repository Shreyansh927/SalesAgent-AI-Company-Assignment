# Home Credit Voice Agent — Test Scenarios

## Test 1: Eligible Customer
- Property: Commercial
- Ownership: Joint
- Original documents: Available
- Loan amount: ₹50 lakh
- Occupation: Salaried
- Income mode: Bank
- Market value: ₹25 lakh
- Tenure: 10–12 years
- Expected result: Preliminary qualification after clarification of the exact tenure and customer confirmation.

## Test 2: Agricultural Property
- Input: Customer confirms agricultural property.
- Expected result: Immediate disqualification; no further eligibility questions.
- Status: Tested.

## Test 3: Original Documents Unavailable
- Input: Customer cannot produce original property documents.
- Expected result: Immediate disqualification.

## Test 4: Cash Income
- Input: Customer confirms income is received in cash.
- Expected result: Immediate disqualification.

## Test 5: Loan Amount Above Offer Limit
- Input: Customer requests ₹80 lakh.
- Expected result: Offer ₹75 lakh and ask whether the customer wants to proceed.
- If accepted: Continue with ₹75 lakh recorded.
- If declined: End the call politely.

## Test 6: Existing Property Loan or EMI Reduction
- Input: Customer wants to transfer an existing property loan or reduce its EMI.
- Expected result: Stop the fresh-loan checklist and use the loan-transfer specialist branch.

## Test 7: Busy Customer
- Input: Customer is not available to talk.
- Expected result: Ask for a callback date and time, then end the current call.

## Test 8: Invalid Tenure
- Input: Customer requests less than 3 years or more than 15 years.
- Expected result: Immediate disqualification.

## Test 9: Out-of-Order Answers and Corrections
- Input: Customer supplies multiple eligibility details in one response or corrects a previous answer.
- Expected result: Store all clear answers, use the latest correction, and ask only for missing information.

## Test 10: Company Name and Variable Rendering
- Input: Start a test call using the configured customer, agent, and company variables.
- Expected result: The spoken greeting uses the correct customer name, agent name, and Home Credit company name without literal placeholders or an incorrect company name.
