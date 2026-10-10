# Home Credit AI Voice Agent — Test Recordings

This directory documents the test scenarios used to evaluate the Home Credit Loan Against Property (LAP) voice agent built with Bolna AI.

Each test includes the recording, transcript, expected behavior, and observed outcome. Only mark a test as completed after running it.

## Test 1 — Successful Eligibility Assessment

**Scenario:** The customer meets the preliminary eligibility criteria and completes the Loan Against Property assessment.

**Test inputs:**

- Property type: Industrial
- Ownership: Sole ownership
- Original documents: Available
- Loan amount: ₹50 lakh
- Occupation: Self-employed
- Income mode: Bank account
- Estimated property value: ₹70 lakh
- Tenure: 10 years

**Expected outcome:** The agent collects all seven eligibility items, summarizes the answers, obtains customer confirmation, and communicates preliminary eligibility without promising final loan approval.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/12dJD3SI765kI8ZvLKTdqpts482C1li9g/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yes.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** Yes, sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** So basically, it is industrial.

**Agent:** Thank you for confirming the property is industrial. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** Yes, it is solely owned by me.

**Agent:** Got it, the property is solely owned by you. Are the original property documents available for verification?

**Customer:** Yes.

**Agent:** Thank you. What loan amount are you looking for? The maximum available under this offer is seventy-five lakh rupees.

**Customer:** I require a loan of somewhere around fifty lakhs.

**Agent:** Thank you for sharing that you are looking for a loan of around fifty lakh rupees. Are you salaried or self-employed?

**Customer:** Actually, I'm self-employed.

**Agent:** Thank you for letting me know you are self-employed. Does your income come into your bank account, or do you receive it in cash?

**Customer:** Through bank.

**Agent:** Thank you for confirming your income comes through your bank account. What is the approximate current market value of your property?

**Customer:** Somewhere around seventy lakhs.

**Agent:** Thank you for sharing the estimated property market value as seventy lakh rupees. What repayment period would you prefer? The available tenure for this offer is between three and fifteen years.

**Customer:** I would require ten years.

**Agent:** Thank you for confirming a preferred repayment period of ten years. Let me quickly confirm the details you've shared. Your property is industrial, the ownership is sole ownership, the original documents are available, you're looking for fifty lakh rupees, your occupation is self-employed, your income comes through a bank, the estimated property value is seventy lakh rupees, and your preferred tenure is ten years. Is everything correct?

**Customer:** Yes, everything is right.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today.

</details>

**Observed outcome:**

- **Information collection:** Pass — all seven eligibility items were collected.
- **Ownership clarification:** Pass — the agent recorded sole ownership.
- **Customer confirmation:** Pass — the agent summarized all the details and obtained confirmation.
- **Conversation flow:** Pass — the agent asked the eligibility questions in sequence without unnecessary repetition.
- **Preliminary eligibility communication:** Pass for the observed conversation, subject to verification against the assignment's eligibility rules.

**Overall result:** Pass for the conversation flow. Confirm that industrial properties are eligible under the assignment's rules before treating the eligibility decision itself as validated.

**Status:** Completed — call executed and observed behavior documented.

## Test 2 — Agricultural Property

**Scenario:** The customer confirms that the property is related to agriculture.

**Expected outcome:** The agent identifies the property as agricultural, politely disqualifies the customer, and ends the call immediately without continuing the eligibility checklist.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1X_9mugFe2F-iAvGuE344X4OGd3wB_iFF/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, sure.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** Sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** Actually, it is none of the ones that you just listed because it is related to agriculture.

**Agent:** Thank you for sharing that. Unfortunately, agricultural property does not meet the eligibility criteria for this specific Loan Against Property offer. We appreciate your time and understanding. Thank you for being a valued Home Credit customer. I'll end the call here.

</details>

**Observed outcome:**

- **Property classification:** Pass — the agent recognized that the customer's property was agricultural, even though the customer initially described it indirectly.
- **Disqualification handling:** Pass — the agent communicated the ineligibility decision politely.
- **Checklist termination:** Pass — the agent did not ask any additional eligibility questions after identifying the agricultural property.
- **Professional communication:** Pass — the agent ended the call respectfully.

**Overall result:** Pass — the agent followed the expected agricultural-property disqualification flow.

**Status:** Completed — call executed and expected behavior observed.

## Test 3 — Original Property Documents Unavailable

**Scenario:** The customer confirms that some original property documents are unavailable for verification.

**Expected outcome:** The agent clarifies whether the original property documents are fully available. If they are not, the agent politely disqualifies the customer and ends the call without continuing the eligibility checklist.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1mteYRygDHULQnQdmzM8I8RnIlwcTveq3/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yes.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** Yes.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** It is industrial.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** It is jointly owned with my father.

**Agent:** Understood. Are the original property documents available for verification?

**Customer:** Actually, not all the documents are available right now. I have more than ninety percent, but not all of them.

**Agent:** Just to confirm, are the original property documents available for verification?

**Customer:** Not all. Some of them are available, but not all.

**Agent:** Thank you for clarifying. Since the original property documents are not fully available for verification, unfortunately, this does not meet the eligibility criteria for this specific Loan Against Property offer. We appreciate your time and understanding. Thank you for being a valued Home Credit customer. I'll end the call here.

</details>

**Observed outcome:**

- **Document availability clarification:** Pass — the agent clarified the customer's ambiguous initial response.
- **Disqualification handling:** Pass — the agent disqualified the customer after confirming that some original documents were unavailable.
- **Checklist termination:** Pass — the agent did not proceed to ask about loan amount, occupation, income mode, property value, or tenure.
- **Professional communication:** Pass — the agent communicated the decision politely and ended the call appropriately.

**Overall result:** Pass — the agent followed the expected disqualification flow.

**Status:** Completed — call executed and expected behavior observed.

## Test 4 — Income Received in Cash

**Scenario:** The customer requests a loan exceeding the offer limit, agrees to proceed with the maximum permitted amount, and subsequently confirms that their income is received in cash.

**Expected outcome:** The agent explains the ₹75 lakh maximum, asks whether the customer wishes to proceed with that amount, records the customer's acceptance, and immediately disqualifies the customer once cash-based income is confirmed.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1ehnhv0hyLOlY7jLRceh0C7lqQGva08xE/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yes.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** For sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** It is industrial.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** It is completely owned by me.

**Agent:** Thank you. Are the original property documents available for verification?

**Customer:** Yeah, all documents are ready.

**Agent:** What loan amount are you looking for?

**Customer:** It is somewhere around eighty lakhs.

**Agent:** The maximum available under this offer is seventy-five lakh rupees. Would you like to proceed with that amount instead?

**Customer:** Can you please increase the loan amount for me beyond seventy-five lakh?

**Agent:** I understand your request for a loan amount beyond seventy-five lakh rupees. However, the maximum available under this specific offer is seventy-five lakh rupees. Would you like to proceed with that amount instead?

**Customer:** Okay, let's go with seventy-five lakh.

**Agent:** Thank you. Are you salaried or self-employed?

**Customer:** Salaried.

**Agent:** Thank you. Does your income come into your bank account, or do you receive it in cash?

**Customer:** In cash.

**Agent:** Thank you for sharing that. Unfortunately, income received in cash does not meet the eligibility criteria for this specific Loan Against Property offer. We appreciate your time and understanding. Thank you for being a valued Home Credit customer. I'll end the call here.

</details>

**Observed outcome:**

- **Loan amount limit handling:** Pass — the agent explained the ₹75 lakh maximum and offered the customer the option to proceed with that amount.
- **Customer acceptance:** Pass — the agent continued after the customer accepted the maximum permitted amount.
- **Income-mode validation:** Pass — the agent identified cash-based income as ineligible under the specified rules.
- **Immediate disqualification:** Pass — the agent ended the assessment without asking further eligibility questions.
- **Professional communication:** Pass — the decision was communicated politely.

**Overall result:** Pass — the agent handled the loan-limit negotiation and cash-income disqualification as expected.

**Status:** Completed — call executed and expected behavior observed.

## Test 5 — Loan Amount Exceeds ₹75 Lakh

**Scenario:** The customer requests a loan of ₹1 crore and a repayment tenure exceeding 20 years, both outside the limits of the specified offer.

**Expected outcome:** The agent explains that the maximum loan amount under this offer is ₹75 lakh and asks whether the customer wishes to proceed with that amount. If the customer declines and insists on a higher amount, the agent politely explains that the offer cannot proceed under the requested conditions and ends the call.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1g_sxJAF1W2AoQNJXRdL-xe6E554VX8X2/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, sure.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to—

**Customer:** But the problem is that I want to take a loan of more than seventy-five lakh, nearly up to one crore. Is it possible?

**Agent:** The maximum available under this offer is seventy-five lakh rupees. Would you like to proceed with that amount instead?

**Customer:** No, actually, I want a loan of one crore rupees with a tenure of more than twenty years.

**Agent:** Understood. Since you would prefer a higher loan amount and a longer tenure than this offer allows, we will not be able to proceed with this offer right now. Thank you for your time.

</details>

**Observed outcome:**

- **Loan amount limit handling:** Pass — the agent clearly stated the maximum offer amount of ₹75 lakh.
- **Alternative offered:** Pass — the agent asked whether the customer wanted to proceed with the permitted amount.
- **Customer refusal handling:** Pass — the customer declined the capped amount and requested ₹1 crore instead.
- **Call termination:** Pass — the agent politely ended the conversation without continuing the eligibility assessment.

**Overall result:** Pass — the agent followed the expected flow for a customer who declines the maximum permitted loan amount.

**Status:** Completed — call executed and expected behavior observed.


## Test 6 — Customer Is Busy

**Scenario:** The customer is unavailable to continue the conversation and requests a callback the following day.

**Expected outcome:** The agent politely asks for a convenient callback time, acknowledges the customer's preference, and ends the current call without proceeding with the eligibility assessment.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1hYt4Ie26QFGVwkeph5dduabn16WxjIF2/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Actually, I'm currently busy, so can we reschedule this call for tomorrow?

**Agent:** Of course, I understand. What date and time tomorrow would be convenient for us to call you back?

**Customer:** Somewhere around eleven AM tomorrow.

**Agent:** Thank you for letting me know. We will aim to call you back tomorrow around eleven AM. Have a good day! [Ending the call now.]

</details>

**Observed outcome:**

- **Callback handling:** Pass — the agent asked for a convenient callback time.
- **Preference capture:** Pass — the agent acknowledged the requested time of approximately 11:00 AM the following day.
- **Eligibility checklist termination:** Pass — the agent did not continue asking eligibility questions.
- **Call termination:** Pass — the agent politely ended the current conversation.

**Overall result:** Pass — the agent followed the expected callback-handling flow.

**Status:** Completed — call executed and expected behavior observed.

## Test 7 — Invalid Repayment Tenure

**Scenario:** The customer requests a repayment tenure longer than the maximum permitted period of 15 years.

**Expected outcome:** The agent identifies the out-of-range tenure, politely disqualifies the customer for this offer, and ends the call without continuing the eligibility assessment.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/18zmNCcmTN_AnkkgrEUeTvtepk3Wkjksv/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yes.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** For sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** It is commercial property.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** Yeah, it is solely owned by me.

**Agent:** Thank you for confirming. Are the original property documents available for verification?

**Customer:** Yes, they are ready.

**Agent:** What loan amount are you looking for?

**Customer:** Actually, I'm looking for a loan of nearly sixty lakh rupees.

**Agent:** Thank you for sharing that. Are you salaried or self-employed?

**Customer:** I'm self-employed.

**Agent:** Does your income come into your bank account, or do you receive it in cash?

**Customer:** Through bank.

**Agent:** What is the approximate current market value of your property?

**Customer:** It is somewhere around thirty to forty lakh.

**Agent:** An approximate figure is fine. What would you estimate the property could be worth today?

**Customer:** Thirty-five lakh.

**Agent:** Thank you. What repayment period would you prefer? The available tenure for this offer is between three and fifteen years.

**Customer:** Actually, I would require somewhere around seventeen or eighteen years, but not less than that.

**Agent:** Thank you for sharing that. However, the available repayment period for this offer is between three and fifteen years only. Since your preferred tenure is more than fifteen years, unfortunately, this does not meet the eligibility criteria for this specific Loan Against Property offer. We appreciate your time and understanding. Thank you for being a valued Home Credit customer. I'll end the call here.

</details>

**Observed outcome:**

- **Tenure validation:** Pass — the agent correctly identified that the requested tenure of 17–18 years exceeds the 15-year maximum.
- **Disqualification handling:** Pass — the agent politely explained that the requested tenure does not meet the offer's criteria.
- **Checklist termination:** Pass — the agent ended the call without asking further eligibility questions.
- **Professional communication:** Pass — the agent communicated the decision clearly and respectfully.

**Overall result:** Pass — the agent followed the expected invalid-tenure disqualification flow.

**Status:** Completed — call executed and expected behavior observed.

## Test 8 — Joint Ownership With a Family Member

**Scenario:** The customer confirms that the property is jointly owned with their brother.

**Expected outcome:** The agent correctly records joint ownership, identifies the co-owner when clarification is needed, and continues the eligibility assessment. Joint ownership alone must not trigger disqualification.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1cbqZ9o_Uzlj0ndpD8DnlwsaaPkNiKFCK/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, sure.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** For sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** Basically, it is a commercial property.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** It is basically jointly owned.

**Agent:** Are the original—

**Customer:** With my brother.

**Agent:** Thank you for sharing that. Are the original property documents available for verification?

**Customer:** Yeah, all the documents are ready.

**Agent:** What loan amount are you looking for?

**Customer:** Forty lakh rupees.

**Agent:** Thank you. Are you salaried or self-employed?

**Customer:** I am self-employed.

**Agent:** Does your income come into your bank account, or do you receive it in cash?

**Customer:** Through a bank account.

**Agent:** Thank you. What is the approximate current market value of your property?

**Customer:** It is—

**Agent:** I didn't quite catch the estimated—

**Customer:** Twenty-five lakh rupees.

**Agent:** Thank you. What repayment period would you prefer? The available tenure for this offer is between three and fifteen years.

**Customer:** I would require somewhere around eleven years.

**Agent:** Thank you.

**Customer:** Sorry, I made a mistake.

**Agent:** No problem.

**Customer:** Actually, I want a loan of not forty but fifty lakh, and I want to increase my tenure from eleven years to thirteen years.

**Agent:** Thank you for the update. You want a loan amount of fifty lakh rupees and a tenure of thirteen years. Is that correct?

**Customer:** Yeah, sure. This is right.

**Agent:** Thank you. Let me quickly confirm the details you've shared. Your property is commercial, the ownership is joint, the original documents are available, you're looking for fifty lakh rupees, your occupation is self-employed, your income comes through a bank, the estimated property value is twenty-five lakh rupees, and your preferred tenure is thirteen years. Is everything correct?

**Customer:** Yes, everything's right.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today.

</details>

**Observed outcome:**

- **Joint-ownership recognition:** Pass — the agent captured joint ownership and identified the co-owner as the customer's brother.
- **Eligibility checklist continuation:** Pass — the agent continued collecting the remaining eligibility information instead of disqualifying the customer solely because of joint ownership.
- **Answer correction:** Pass — the agent updated the loan amount from ₹40 lakh to ₹50 lakh and the tenure from 11 to 13 years after obtaining confirmation.
- **Final summary:** Pass — the agent included the joint ownership and corrected values in the final summary.
- **Eligibility decision:** Needs review — the agent declared preliminary eligibility despite a requested loan of ₹50 lakh against an estimated property value of ₹25 lakh. Validate this against the assignment's eligibility rules.

**Overall result:** Pass for joint-ownership handling; eligibility-rule validation requires further review.

**Status:** Completed — call executed and joint-ownership behavior observed.

## Test 9 — Property Owned Entirely by Someone Else

**Scenario:** The customer confirms that the industrial property belongs entirely to another person and that they are not an owner.

**Expected outcome:** The agent clarifies whether the customer is a sole or joint owner. If the customer confirms that the property belongs entirely to someone else, the agent explains that the offer requires sole or joint ownership and does not declare the customer eligible.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1CAnLs9gDa7NYif3y42p_RjL4GdidtzVV/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yes.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** For sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** It is an industrial property.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** Actually, it is neither owned by me nor directly owned by someone else. The industrial property is in the name of someone else whom I know, but he is not connected to me.

**Agent:** Just to clarify, is the property in your name alone, jointly owned with someone else, or—

**Customer:** It is owned by someone else entirely.

**Agent:** Thank you for clarifying. Since the property is not owned by you, unfortunately, you do not meet the ownership criteria for this offer.

**Customer:** Is there any other possible way?

**Agent:** I understand your question. However, for this Loan Against Property offer, the property must be owned by you either solely or jointly. Since the property is owned entirely by someone else, this offer would not be applicable. If you have any other property in your name, we could explore options based on that. Would you like to check that?

**Customer:** No, actually, I don't have a property that is solely owned by me or—

**Agent:** Thank you for sharing that. Based on the information provided, you do not meet the eligibility criteria for this specific offer at this time. Thank you for your time.

</details>

**Observed outcome:**

- **Ownership clarification:** Pass — the agent asked whether the property was solely or jointly owned and clarified the customer's response.
- **Third-party ownership handling:** Pass — the agent correctly identified that the customer was not an owner.
- **Disqualification handling:** Pass — the agent explained the ownership requirement and did not continue the eligibility checklist.
- **Alternative exploration:** Pass — the agent asked whether the customer had another property that could be considered.
- **Final eligibility communication:** Pass — after the customer indicated they had no qualifying property, the agent stated that they did not meet the criteria for this offer.

**Overall result:** Pass — the agent followed the expected clarification and disqualification flow.

**Status:** Completed — call executed and observed behavior documented.

## Test 10 — Customer Provides Answers Out of Order

**Scenario:** The customer provides multiple eligibility details before the agent asks the corresponding questions, including property type, occupation, income mode, and ownership.

**Expected outcome:** The agent captures all clearly stated answers, avoids repeating questions for information already provided, clarifies ambiguous details, and asks only for the earliest unanswered eligibility item.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1pZokS393SNMMwCTjHvf_sHpktCZkBMJR/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, for sure. But one thing to convey: I own an industrial property, basically a factory. I'm self-employed, and my income comes through a bank. But the thing is, I don't fully own it. I actually own it jointly with my father.

**Agent:** Thank you for sharing that. Just to confirm, since you mentioned you own an industrial property jointly with your father, is that correct?

**Customer:** Yeah, yeah, sure.

**Agent:** Great, thank you. Are the original property documents available for verification?

**Customer:** Yeah, sure. All the documents are ready.

**Agent:** Thank you. What loan amount are you looking for? The maximum available under this—

**Customer:** Thirty-five, actually. I'm looking for a loan of thirty-five lakh, and the tenure should be eight to nine years.

**Agent:** Thank you for—

**Customer:** Eight to nine years.

**Agent:** Thank you. Just to confirm, would you prefer a repayment period of eight to nine years?

**Customer:** Yeah.

**Agent:** Thank you. What is the approximate current market value of your property?

**Customer:** It is somewhere around forty to fifty lakh.

**Agent:** Thank you. To confirm the details you've shared: your property is industrial, owned jointly with your father, the original documents are available, you are looking for a loan amount of thirty-five lakh rupees, you are self-employed with income through a bank, the estimated property market value is around forty to fifty lakh rupees, and your preferred repayment tenure is eight to nine years. Is all this correct?

**Customer:** It is right, it is right.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today. Goodbye!

</details>

**Observed outcome:**

- **Initial information extraction:** Pass — the agent captured property type, ownership, occupation, and income mode from the customer's opening response.
- **Ownership clarification:** Pass — the agent confirmed joint ownership with the customer's father.
- **Duplicate-question avoidance:** Pass — the agent did not ask again for occupation or income mode after the customer supplied those details.
- **Loan amount and tenure extraction:** Partial pass — the agent captured the loan amount and tenure range, but did not ask the customer to choose a specific tenure within that range.
- **Property value extraction:** Pass — the agent captured the estimated value range of ₹40–50 lakh.
- **Eligibility decision:** Needs review — the agent declared preliminary eligibility despite the industrial property and the requested loan amount relative to the estimated property value. Confirm that this outcome follows the assignment's actual eligibility rules.

**Overall result:** Partial pass — the agent successfully captured several out-of-order answers, but tenure clarification and eligibility validation require further review.

**Status:** Completed — call executed; partial pass against the test objective.

## Test 11 — Customer Corrects a Previous Answer

**Scenario:** The customer initially requests a loan of ₹40 lakh with an 11-year tenure, then corrects the loan amount to ₹50 lakh and the tenure to 13 years.

**Expected outcome:** The agent accepts the customer's corrections, updates the previously captured values, confirms the revised details, and uses the latest confirmed answers in the final summary.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1MiCMOma5UdDMMelkgL0sol_-9rWLZr2m/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, sure.

**Agent:** Thank you. I'm calling because, as one of our valued customers, you may be eligible for a special pre-approved Loan Against Property offer of up to seventy-five lakh rupees. I'd like to ask a few questions to check whether you meet the preliminary eligibility criteria. Would you be comfortable proceeding?

**Customer:** For sure.

**Agent:** Could you tell me what type of property you own? Is it residential, commercial, or industrial?

**Customer:** Basically, it is a commercial property.

**Agent:** Thank you for that. Is the property in your name alone, or is it jointly owned with someone else?

**Customer:** It is basically jointly owned.

**Agent:** Are the original—

**Customer:** With my brother.

**Agent:** Thank you for sharing that. Are the original property documents available for verification?

**Customer:** Yeah, all the documents are ready.

**Agent:** What loan amount are you looking for?

**Customer:** Forty lakh rupees.

**Agent:** Thank you. Are you salaried or self-employed?

**Customer:** I am self-employed.

**Agent:** Does your income come into your bank account, or do you receive it in cash?

**Customer:** Through a bank account.

**Agent:** Thank you. What is the approximate current market value of your property?

**Customer:** It is—

**Agent:** I didn't quite catch the estimated—

**Customer:** Twenty-five lakh rupees.

**Agent:** Thank you. What repayment period would you prefer? The available tenure for this offer is between three and fifteen years.

**Customer:** I would require somewhere around eleven years.

**Agent:** Thank you.

**Customer:** But one thing, sorry, I made a mistake.

**Agent:** No problem.

**Customer:** Actually, I want a loan of not forty but fifty lakh, and please increase my tenure from eleven years to thirteen years.

**Agent:** Thank you for the update. You want a loan amount of fifty lakh rupees and a tenure of thirteen years. Is that correct?

**Customer:** Yeah, sure. This is right.

**Agent:** Thank you. Let me quickly confirm the details you've shared. Your property is commercial, the ownership is joint, the original documents are available, you're looking for fifty lakh rupees, your occupation is self-employed, your income comes through a bank, the estimated property value is twenty-five lakh rupees, and your preferred tenure is thirteen years. Is everything correct?

**Customer:** Yes, everything's right.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today.

</details>

**Observed outcome:**

- **Correction recognition:** Pass — the agent recognized that the customer wanted to revise previously provided details.
- **State update:** Pass — the loan amount was updated from ₹40 lakh to ₹50 lakh, and the tenure from 11 to 13 years.
- **Explicit confirmation:** Pass — the agent repeated the revised values and obtained confirmation.
- **Final summary:** Pass — the final summary used the corrected values rather than the original answers.
- **Eligibility validation:** Needs review — the agent declared preliminary eligibility despite the requested loan of ₹50 lakh against an estimated property value of ₹25 lakh. Verify the applicable loan-to-value rules before treating the eligibility decision as correct.

**Overall result:** Pass for correction handling; eligibility-rule validation requires further review.

**Status:** Completed — call executed and correction behavior observed.

## Test 12 — Customer Gives a Tenure Range

**Scenario:** The customer requests a repayment tenure of approximately eight to nine years instead of specifying one exact duration.

**Expected outcome:** The agent recognizes the tenure range, asks the customer to select a specific number of years, and confirms the selected tenure before completing the eligibility assessment.

**Recording:** [Listen to the test recording](https://drive.google.com/file/d/1bZ9Q1JCzHxvTKd7Th4hK5KtPRjQgdL7E/view?usp=drive_link)

**Transcript:**

<details>
<summary>View full conversation transcript</summary>

**Agent:** Hello, may I speak with Shreyansh? My name is Priya, calling from Loan2k26. Is this a convenient time for a brief conversation?

**Customer:** Yeah, for sure, but one thing to convey: I own an industrial property, basically a factory. I'm self-employed, and my income comes through a bank. But I don't fully own it. I own it jointly with my father.

**Agent:** Thank you.

**Customer:** I basically—

**Agent:** Thank you for sharing that. Just to confirm, since you mentioned you own an industrial property jointly with your father, is that correct?

**Customer:** Yeah, yeah, sure.

**Agent:** Great, thank you. Are the original property documents available for verification?

**Customer:** Yeah, sure. All the documents are ready.

**Agent:** Thank you. What loan amount are you looking for? The maximum available under this—

**Customer:** Thirty-five. Actually, I'm looking for a loan of thirty-five lakh, and the tenure should be—

**Agent:** Thank you for—

**Customer:** Eight to nine years.

**Agent:** Thank you. Just to confirm, would you prefer a repayment period of eight to nine years?

**Customer:** Yeah.

**Agent:** Thank you. What is the approximate current market value of your property?

**Customer:** It is somewhere around forty to fifty lakh.

**Agent:** Thank you. To confirm the details you've shared: your property is industrial, owned jointly with your father, the original documents are available, you are looking for a loan amount of thirty-five lakh rupees, you are self-employed with income through a bank, the estimated property market value is around forty to fifty lakh rupees, and your preferred repayment tenure is eight to nine years. Is all this correct?

**Customer:** It is right, it is right.

**Agent:** Thank you for confirming those details. Based on the information you've shared, you meet the preliminary eligibility criteria for this Home Credit Loan Against Property offer. A senior loan expert will contact you shortly to discuss the applicable interest rate and next steps. Thank you for your time today. Goodbye!

</details>

**Observed outcome:**

- **Tenure-range recognition:** Pass — the agent captured the customer's requested range of eight to nine years.
- **Specific-tenure clarification:** Fail — the agent repeated and confirmed the range instead of asking the customer to select eight or nine years.
- **Final summary:** Partial pass — the agent accurately included the requested range but did not establish a single confirmed tenure.
- **Eligibility communication:** Needs review — the agent declared preliminary eligibility without resolving the tenure ambiguity or independently validating all eligibility rules.

**Overall result:** Partial pass — the agent captured the tenure range but did not satisfy the requirement to confirm one specific duration.

**Status:** Completed — call executed; specific-tenure clarification requires improvement.

## Test 13 — Customer Asks About the Interest Rate

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
