# Hi, I'm Harsh Sahay 👋

**Master's in AI Systems Management @ Carnegie Mellon University** · previously UW–Madison

I like the part of engineering where a real customer problem meets real systems: messy documents, third-party APIs, cloud infrastructure, and the people who have to use the result. I build end-to-end, from the data and integrations up to the UI, and I'm looking for **Forward Deployed Engineer** roles.

[LinkedIn](https://www.linkedin.com/in/harsh-sahay09) · [hsahay@andrew.cmu.edu](mailto:hsahay@andrew.cmu.edu)

---

## Featured projects

### 🛡️ [proTecht](https://github.com/Harsh-Sahay009/protecht-ssp-analyzer): compliance automation for FedRAMP / NIST / ISO / PCI
Compliance teams check System Security Plans against the cloud environment by hand. proTecht ingests an SSP in any format (PDF, DOCX, text), finds the controls with four fallback parsing strategies, scores each one against AWS security posture (MFA, S3 exposure, CloudTrail, GuardDuty, encryption and more), and generates a prioritized remediation plan with an LLM. A rule-based fallback keeps it working offline.
`Python` `Flask` `AWS` `OpenAI` `GRC`

### 🚚 [Freight Load Search](https://github.com/Harsh-Sahay009/freight-load-search): built against a Schneider FreightPower brief
A carrier-facing search engine for available freight loads. I wrote most of the app: search with radius and state fallback, Trimble PC\*MILER integration (miles, tolls, emissions, directions, route maps), Google Maps routing, and cached geocoding over an AWS DynamoDB-backed dataset of 3,500+ loads.
`Python` `Flask` `AWS DynamoDB` `PC*MILER API` `Google Maps API`

### 🩺 [CareRelay](https://github.com/Harsh-Sahay009/CareRelay): elder-care coordination (hackathon)
Turns noisy family messages and care documents into structured care events that a person reviews, then routes each event to the right caregiver, physician, or older adult through a central role-based access and audit layer. AI extraction and transcription sit behind swappable provider interfaces.
`TypeScript` `React` `RBAC` `Human-in-the-loop`

<details>
<summary><b>More projects</b></summary>

- **[ConnecTech](https://github.com/Harsh-Sahay009/ConnecTech)**: a team Android app (Kotlin/MVVM) that matches businesses with tech service providers. I built the shared domain model and utility layer.

</details>

---

## Tools I work with

- **Languages:** Python · TypeScript / JavaScript · Kotlin · SQL
- **Backend & data:** Flask · Node / Express · pandas · PySpark · REST API integration
- **Cloud:** AWS (DynamoDB, IAM, S3, CloudTrail, GuardDuty)
- **AI:** OpenAI and Gemini APIs · LLM-assisted workflows with deterministic fallbacks
- **Frontend:** React · Vite
