# Home Credit AI Voice Agent — Test Recordings

This directory documents the test scenarios used to evaluate the Home Credit Loan Against Property (LAP) voice agent built with Bolna AI.

Each test includes the recording, transcript, expected behavior, and observed outcome. Only mark a test as completed after running it.

## Test 1 — Successful Eligibility Assessment

Scenario: The customer meets all preliminary eligibility criteria.

- Property type: Commercial
- Ownership: Joint
- Original documents: Available
- Loan amount: ₹50 lakh
- Occupation: Salaried
- Income mode: Bank account
- Estimated property value: ₹25 lakh
- Tenure: 12 years

**Expected outcome:** The agent collects all seven eligibility items, summarizes the answers, obtains confirmation, and communicates preliminary eligibility without promising final approval.

- Recording: [(https://drive.google.com/file/d/12dJD3SI765kI8ZvLKTdqpts482C1li9g/view?usp=drive_link)]
- Transcript: [Insert Google Drive transcript link]
- Status: Completed / Pending

## Test 2 — Agricultural Property

**Scenario:** The customer confirms that the property is agricultural.

**Expected outcome:** The agent immediately disqualifies the customer politely and ends the call without asking additional eligibility questions.

- Recording: [(https://drive.google.com/file/d/1X_9mugFe2F-iAvGuE344X4OGd3wB_iFF/view?usp=drive_link)]
- Transcript: [Insert Google Drive transcript link]
- Status: Completed / Pending

## Test 3 — Original Property Documents Unavailable

**Scenario:** The customer says the original property documents are lost or unavailable for verification.

**Expected outcome:** Immediate disqualification. The agent must not continue the eligibility checklist.

- Recording: [https://drive.google.com/file/d/1mteYRygDHULQnQdmzM8I8RnIlwcTveq3/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 4 — Income Received in Cash

**Scenario:** The customer is salaried or self-employed but confirms that their income is received in cash rather than through a bank account.

**Expected outcome:** Immediate disqualification after cash income is confirmed.

- Recording: [(https://drive.google.com/file/d/1ehnhv0hyLOlY7jLRceh0C7lqQGva08xE/view?usp=drive_link)]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 5 — Loan Amount Exceeds ₹75 Lakh

**Scenario:** The customer requests a loan of ₹90 lakh.

**Expected outcome:** The agent explains that the maximum under the offer is ₹75 lakh and asks whether the customer wants to proceed with that amount.

- If the customer agrees, record ₹75 lakh and continue.
- If the customer declines, explain that the offer cannot proceed at the requested amount and end the call.

- Recording: [https://drive.google.com/file/d/1g_sxJAF1W2AoQNJXRdL-xe6E554VX8X2/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 6 — Existing Property Loan or EMI Reduction

**Scenario:** The customer already has a loan against the property and wants to transfer it or reduce the existing EMI.

**Expected outcome:** The agent stops the fresh-loan eligibility checklist and follows the loan-transfer specialist branch.

- Recording: [Insert Google Drive audio link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 7 — Customer Is Busy

**Scenario:** The customer says they cannot talk at the moment.

**Expected outcome:** The agent asks for a convenient callback date and time, captures the preference if supported, and ends the current call without continuing the eligibility assessment.

- Recording: [https://drive.google.com/file/d/1hYt4Ie26QFGVwkeph5dduabn16WxjIF2/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 8 — Invalid Repayment Tenure

**Scenario:** The customer requests a tenure shorter than 3 years or longer than 15 years.

**Expected outcome:** The agent identifies the out-of-range tenure, politely disqualifies the customer for this offer, and ends the call.

- Recording:[https://drive.google.com/file/d/18zmNCcmTN_AnkkgrEUeTvtepk3Wkjksv/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 9 — Joint Ownership With a Family Member

**Scenario:** The customer explains that the property is jointly owned with their father, mother, spouse, or another person.

**Expected outcome:** The agent correctly records joint ownership and continues the eligibility assessment. Joint ownership alone must not trigger disqualification.

- Recording: [https://drive.google.com/file/d/1cbqZ9o_Uzlj0ndpD8DnlwsaaPkNiKFCK/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 10 — Property Owned Entirely by Someone Else

**Scenario:** The customer says the property belongs entirely to another person and they are not an owner.

**Expected outcome:** The agent asks a brief clarification to establish whether the customer is a sole or joint owner. It must not incorrectly record joint ownership or declare the customer eligible based on an assumption. If the ownership situation cannot be established, the agent must not claim preliminary qualification.

**Note:** The assignment explicitly accepts sole and joint ownership but does not specify a separate rule for a property owned entirely by a non-customer. This test evaluates clarification and accurate information capture rather than inventing a new disqualification rule.

- Recording: [Insert Google Drive audio link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 11 — Customer Provides Answers Out of Order

**Scenario:** The customer mentions the loan amount, occupation, or property value before the agent asks the corresponding question.

**Expected outcome:** The agent stores all clearly stated answers, avoids asking for information already captured, and asks the earliest unanswered eligibility question.

- Recording: [https://drive.google.com/file/d/1pZokS393SNMMwCTjHvf_sHpktCZkBMJR/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 12 — Customer Corrects a Previous Answer

**Scenario:** The customer initially describes the property as commercial but later corrects it to agricultural.

**Expected outcome:** The agent uses the latest clear answer, applies the agricultural-property disqualification rule, and ends the call immediately.

- Recording: [https://drive.google.com/file/d/1MiCMOma5UdDMMelkgL0sol_-9rWLZr2m/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 13 — Customer Gives a Tenure Range

**Scenario:** The customer says they would prefer a repayment period of approximately 10–12 years.

**Expected outcome:** The agent asks the customer to select a specific tenure, such as 10, 11, or 12 years, instead of automatically choosing the highest value. It must accurately confirm the customer's selection.

- Recording: [https://drive.google.com/file/d/1bZ9Q1JCzHxvTKd7Th4hK5KtPRjQgdL7E/view?usp=drive_link]
- Transcript: [Insert Google Drive transcript link]
- Status: Pending

## Test 14 — Customer Asks About the Interest Rate

**Scenario:** The customer asks about the applicable interest rate before completing the eligibility assessment.

**Expected outcome:** The agent explains that a senior loan expert will discuss the applicable interest rate after the preliminary assessment. It must not invent or estimate an interest rate and should return to the pending eligibility question when the customer is ready.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1KollXou6pwixUvNC19APexhcEGnIl7mR/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, sure.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** Yeah, no problem.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** It is basically—

**Agent:** Just to clarify, is the property residential, commercial, industrial, or agricultural?

**Customer:** It is basically residential.

**Agent:** Thank you for confirming. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** It is only owned by me.

**Agent:** Thank you. Are the original property documents available for verification?

**Customer:** Yeah, they are ready.

**Agent:** What loan amount are you looking for?

**Customer:** Thirty lakhs.

**Agent:** Thank you. Are you salaried or self-employed?

**Customer:** I'm salaried.

**Agent:** Thank you for sharing that. Does your income come into your bank account, or do you receive it in cash?

**Customer:** Through bank account.

**Agent:** What is the approximate current market value of your property?

**Customer:** It is somewhere around—

**Agent:** An approximate figure is fine. What would—

**Customer:** Fifteen lakh.

**Agent:** Thank you. What repayment period would you prefer? The available tenure for this offer is between three and fifteen years.

**Customer:** I would require somewhere else—

**Agent:** Just to confirm, how many years would you prefer for repayment?

**Customer:** Seven years.

**Agent:** Thank you. Let me quickly confirm the details you've shared. Your property is residential, the ownership is sole ownership, the original documents are available, you're looking for thirty lakh rupees, your occupation is salaried, your income comes through a bank, the estimated property value is fifteen lakh rupees, and your preferred tenure is seven years. Is everything correct?

**Customer:** Yeah, everything is correct, but can you elaborate a bit more about the interest rate in this loan, like how does it exactly work?

**Agent:** The exact interest rate and detailed terms will be explained by a senior loan expert after the preliminary eligibility check. I don't want to give you an inaccurate figure.

**Customer:** But please, can you provide—

**Agent:** I understand your—

**Customer:** That, like, a round figure.

**Agent:** I understand your interest in a rough figure, but I don't have that detail right now. A senior loan expert will contact you shortly to explain the applicable interest rate and next steps. Thank you for your understanding.

**Customer:** Okay, thank you.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today. Have a great day!

**Customer:** Yeah.

</details>

**Observed outcome:**

- **Interest-rate handling:** Pass — the agent did not invent or estimate an interest rate and referred the customer to a senior loan expert.
- **Customer reassurance:** Pass — the agent acknowledged the customer's request politely.
- **Return to pending question:** Not applicable in this execution — the customer had already completed the eligibility questions before asking about the interest rate.
- **Overall result:** Partial pass — the agent handled the interest-rate question correctly, but this call does not verify how the agent behaves when eligibility questions are still pending.

**Status:** Completed — call executed; partial pass against the test objective.


## Summary

The test suite covers successful qualification, immediate disqualification, ownership clarification, amount-limit handling, transfer routing, callback handling, natural conversation, correction handling, and configuration accuracy.

The observed result for each scenario should be recorded after the corresponding call has been completed.
