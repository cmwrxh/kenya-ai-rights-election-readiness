# Data Protection Impact Assessment (DPIA) — Kenya Context (Template)

> Use this template when deploying AI that processes personal data or impacts people’s rights.
> Keep answers short, factual, and link evidence in `/evidence`.

## 1) Project overview
- Project name:
- Owner / team:
- Sector (e.g., fintech, gov, media, health):
- AI use case (1–2 sentences):
- Go-live date:
- Users impacted (who, where, how many approx.):

## 2) Data & processing map
### Personal data involved
- Data categories (e.g., identifiers, contact info, location, biometrics, financial, behavioral):
- Sensitive data involved? (yes/no) If yes, specify:
- Data sources (first-party, third-party, public, scraped, user-provided):

### Processing activities
- Collection:
- Storage:
- Model training (yes/no). If yes: where, when, and on what dataset:
- Inference/serving:
- Sharing/third parties:
- Retention period:
- Data deletion process:

## 3) Purpose, necessity, proportionality
- Purpose (why are we doing this?):
- Legal basis / justification (brief):
- Why AI (vs rules/manual)?:
- What is the minimum data needed?:
- How do you prevent function creep?:

## 4) Risk assessment (rights & harms)
Rate each risk: Likelihood (Low/Med/High) × Impact (Low/Med/High)

| Risk | Example | Likelihood | Impact | Mitigations | Evidence |
|---|---|---:|---:|---|---|
| Bias / unfair outcomes | Unequal rejection rates |  |  |  |  |
| Privacy leakage | Outputs reveal PII |  |  |  |  |
| Misinformation / manipulation | Election-adjacent content |  |  |  |  |
| Security compromise | Model/API abused |  |  |  |  |
| Lack of explainability | Users can’t contest |  |  |  |  |
| Over-reliance | Human stops verifying |  |  |  |  |

## 5) Controls & safeguards
### Governance
- Decision log maintained? (link `docs/DECISIONS.md` entry):
- Accountable owner named?:
- Approval gates before launch:

### Technical controls
- Access control (who can view data/models):
- Encryption (at rest/in transit):
- Logging & audit trail:
- Rate limiting / abuse prevention:
- Output filters / safety rules:

### Model quality controls
- Dataset documentation:
- Bias testing plan:
- Red-team plan:
- Monitoring (drift, performance, abuse):

## 6) Transparency & user rights
- Notice to users (what you tell them):
- How users can contest outcomes:
- Human review path:
- Contact channel:

## 7) Residual risk & decision
- Residual risk summary:
- Launch decision (approve / approve with conditions / reject):
- Conditions (if any):
- Sign-off (name/title/date):

## 8) Evidence checklist (attach or link)
- Data map diagram or notes
- Model card
- Risk register entry
- Test results (bias, privacy, robustness)
- Incident response plan
- Vendor due diligence (if applicable)
