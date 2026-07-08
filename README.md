# Doyel Das

Healthcare AI & Operations | Translating clinical domain expertise into analytical tools and operational systems

I work at the intersection of AI deployment, clinical operations, and customer success, focused on the problems that slow down care delivery and the workflows that can be rebuilt to solve them.

These projects were built to demonstrate how I think about designing systems that scale without scaling human effort proportionally: what breaks at scale, where the human bottlenecks are, and how to design around them.

---

## Projects

### 🏥 [Provider Outreach QA](https://github.com/doyel-das/provider-outreach-qa) · [Live demo →](https://doyel-das.github.io/provider-outreach-qa)
AI-powered QA tool for support ticket responses at a mental healthcare platform. Scores tone, clarity, and accuracy. Flags safety concerns where a response fails to handle signs of patient distress. Audits routing decisions before responses reach patients, providers, or payors.

### 📋 [Provider Credentialing Monitor](https://github.com/doyel-das/provider-credentialing-monitor) · [Live demo →](https://doyel-das.github.io/provider-credentialing-monitor)

Monitors credential expiration dates across a provider network. Generates urgency-calibrated outreach across four tiers. Runs automated verification checks on renewal submissions. Routes only genuinely complex cases — expired credentials, payor credentialing renewals, anomalous submissions — to a human.

### 💰 [Claims Pipeline Monitor](https://github.com/doyel-das/claims-pipeline-monitor) · [Live demo →](https://doyel-das.github.io/claims-pipeline-monitor)
Tracks outstanding insurance claims and automates the follow-up layer. Generates escalating payor outreach calibrated to days outstanding. Classifies denial reason codes and routes each to the correct resolution path automatically. Surfaces high-dollar escalations and complex denials to a human billing team.

### 📋 [Account Health Scoring Engine](https://github.com/doyel-das/account-health-engine) · [Live demo →](https://doyel-das.github.io/account-health-engine)

Scores healthcare AI SaaS accounts 0–100 across 7 configurable weighted signals. Assigns risk tiers, surfaces churn override conditions, and generates rule-based intervention recommendations. Outputs terminal summary, CSV, SQLite portfolio queries, and a self-contained HTML report with trend charts and Claude-powered intervention email drafts.

### 🏥 [Psychiatric Discharge Follow-Up Coordinator](https://github.com/doyel-das/psychiatric-discharge-workflow) · [Live demo →](https://bunkerhill-workflow.vercel.app)

A 20-agent CareBricks workflow specification and prototype dashboard targeting HEDIS FUH compliance across inpatient psychiatric discharges. Stratifies patients by clinical and social risk, routes coordinator outreach with a mandatory human review gate, and tracks 7-day and 30-day follow-up rates against NCQA national benchmarks. Includes a Missed Escalation Audit that surfaces tier miscalibrations when patients readmit within 90 days.

---

*Projects built with Python, the Anthropic API, and HTML.*
