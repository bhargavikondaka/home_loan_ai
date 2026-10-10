# Home Credit – Loan Against Property AI Voice Agent

An AI-powered voice agent built to conduct preliminary eligibility screening for Home Credit's Loan Against Property (LAP) enquiries.

## 📌 Project Overview

**Sakshi** is a female AI voice agent designed to communicate with loan applicants in English, collect the required information, and perform preliminary eligibility screening based on predefined criteria.

The agent identifies potentially eligible applicants and directs them to a senior human loan expert for further assistance. It does not make final loan approval or sanction decisions.

## 🎯 Objectives

- Automate preliminary loan eligibility screening.
- Collect applicant and property-related information through natural conversation.
- Identify applicants who do not meet the specified screening criteria.
- Reduce repetitive information collection for human loan experts.
- Provide a clear next step for eligible applicants and referral cases.

## ✨ Key Features

- **Conversational screening:** Asks eligibility questions in a natural, one-at-a-time format.
- **Property eligibility:** Checks property type and ownership.
- **Document verification readiness:** Confirms whether original property documents are available or can be arranged.
- **Loan amount screening:** Applies a maximum requested amount of ₹75,00,000 for this screening workflow.
- **Income screening:** Checks occupation and whether income is received through a bank.
- **Property valuation:** Collects the applicant's estimated property market value.
- **Tenure validation:** Checks the requested loan tenure against the permitted range of 3–15 years.
- **Disqualification handling:** Explains applicable screening outcomes politely.
- **Human follow-up:** Refers eligible applicants to a senior loan expert.
- **Callback and existing-loan handling:** Supports callback requests and referrals for existing LAP EMI-reduction enquiries.

## 🧾 Eligibility Screening Criteria

The agent collects the following seven details:

1. Property type
2. Property ownership
3. Availability of original property documents
4. Requested loan amount
5. Occupation and income source
6. Estimated property market value
7. Preferred loan tenure

The agent follows the configured screening rules, including the agricultural-property exclusion, bank-based income requirement, ₹75 lakh maximum, and 3–15-year tenure range.

**Note:** These are preliminary screening criteria for this project, not a guarantee of Home Credit's current lending policy or final loan eligibility.

## 🛠️ Technology

- **AI voice agent platform:** Retell AI
- **Language:** English
- **Agent name:** Sakshi
- **Business domain:** Financial Services – Loan Against Property
- **Version control and documentation:** GitHub

## 🎥 Project Demonstration

Watch the screen recording of the agent and its workflow:

**[View Project Demo]: https://drive.google.com/file/d/1ycKy9cAMgwBPhTKU0XpK_0fNnM_ISQnl/view?usp=sharing**

## 🔗 Project Links

- **Published AI Agent:** [Open Agent](https://agent.retellai.com/orb/agent_e8c66224a8c10fc3c96638da17?token=68e9a1db75f776864c9d1de42ee8b2ff)

- **System Prompt:** [View Agent Instructions]([system-prompt.md](https://ginger-stag-a39.notion.site/sales-ai-agent-assignment-3f50db9f46e280bba114cdc9621c52c2))
- **Call Recording:** [Listen to Sample Call]([ADD_YOUR_CALL_RECORDING_URL_HERE](https://drive.google.com/file/d/1ycKy9cAMgwBPhTKU0XpK_0fNnM_ISQnl/view?usp=sharing))
- **Call Transcript / Logs:** [View Sample Transcript](https://drive.google.com/file/d/1cFpOJ8H-BKYFBXeZxpavPUjJBsZbKkGh/view?usp=sharing)

*Replace each placeholder with the corresponding link. If a published agent URL is not available, state that clearly rather than substituting an unrelated link.*

## 🔄 Workflow

1. The agent greets the applicant and explains the purpose of the call.
2. It collects the seven required eligibility details.
3. It checks the responses against the configured criteria.
4. It explains a disqualification when a mandatory criterion is not met.
5. It refers applicants who pass preliminary screening to a senior human loan expert.
6. It handles applicable callback and existing-LAP referral requests.

## ⚠️ Limitations

- The agent performs preliminary screening only.
- Final approval, sanction amount, interest rate, and other loan terms require further assessment by the appropriate human representative.
- The agent must not promise approval or loan disbursement.
- Its behavior depends on the configured system prompt, available tools, and workflow integrations.

## 🔒 Privacy and Security

Only share recordings and transcripts that are authorized for public demonstration. Remove personal information and sensitive applicant data before publishing. Never commit API keys, access tokens, or other credentials to a public repository.

## 👩‍💻 Author

**Project:** Home Credit Loan Against Property AI Voice Agent  
**Agent:** Sakshi  
**Purpose:** AI voice-based preliminary loan eligibility screening

---

*This project demonstrates the design and configuration of a conversational AI voice agent for a financial-services use case.*
