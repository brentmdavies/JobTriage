# Executive Summary

- Decision: RESEARCH MORE
- Confidence: 7.2/10.0 (±0.6 — unknowns: on-call policy, team size, exact tech ownership)
- One-line rationale: Strong technical fit to Brent's AWS/Kubernetes/Terraform experience and clear ownership of core infra, but unclear on-call practices and some stability/noops signals warrant clarification before applying.

## Job & Source

- Role: Senior Devops Engineer
- Company: Guild Education
- Posting: [Simplify posting](https://simplify.jobs/p/600213a6-772e-4984-becb-60a45cc490e5/Senior-Devops-Engineer?utm_source=job_post&utm_medium=copy_link&utm_campaign=organic_share) (Simplify jobs view)
- Company site: [Guild Education website](https://www.guildeducation.com/)
- Posted on: 2025-09-03 (Simplify page)

## Quick verification checklist

- [x] Company homepage visited
- [x] Job posting fetched from Simplify
- [x] Basic news/search queries opened (layoffs / press)
- [x] Glassdoor/company reviews checked (link found)

## Detailed Analysis

Scope-fit (what matches Brent)

- Many explicit matches to Brent's skillset: deep AWS, IaC, Terraform/CloudFormation/CDK, Kubernetes/Docker/Helm, Bash/Python, CI/CD (Github Actions / CircleCI). The posting requests ownership of core AWS infra, monitoring/observability, security, and central tooling — all align with Brent's experience migrating monoliths to EKS and pipeline automation.

Top 3 Pros

1. Clear technical ownership: role explicitly owns core AWS infrastructure, cross-account operations, IAM/secrets and centralized tooling — high-impact and matches senior SRE/Platform responsibilities.
2. Tech stack fits Brent: AWS + Kubernetes + Terraform/CloudFormation/CDK + CI/CD + monitoring and security.
3. Remote-friendly (many US states) and listed compensation ($150k–$188.6k + stock + benefits) — competitive baseline.

Top 3 Cons / Risks

1. No on-call policy or SLO/SRE specifics in the posting — unknown on-call expectations and compensation.
2. Stability flags: Simplify notes layoffs of 450+ employees in 2023–2024 and 1-year -1% growth; possible headcount instability or reorganizations.
3. NoOps / developer-first signals: the posting calls out "AWS CDK, CloudFormation" and asks to "lead the adoption of infrastructure as code (AWS CDK, CloudFormation)" — CDK emphasis can signal platform responsibilities being pushed toward application teams. Terraform is mentioned elsewhere, so the picture is mixed.

NoOps Risk Assessment

- NoOps risk score (0.0-1.0): 0.45
- Signals raising this score:
  - Explicit call-out to "lead adoption of AWS CDK, CloudFormation" (CDK often correlates with developer-owned infra patterns).
  - Mentions of developer-facing IaC options without clear mention of platform team ownership or governance.
- Signals mitigating this score:
  - Role is described as *owning core AWS infrastructure* and building centralized DevOps tooling — suggests a platform / central SRE function exists or is desired.

Scoring (100-point model)

| Category | Weight | Score (out of weight) | Rationale |
|---|---:|---:|---|
| Scope fit | 20 | 18 | Strong match across cloud, k8s, IaC, CI/CD |
| Workload & On-call | 18 | 9 | No on-call policy or compensation described; "fast-paced" hints not reassuring |
| Culture & Management | 15 | 9 | Benefits listed, but layoffs & limited SRE/process detail lower confidence |
| Compensation & Benefits | 15 | 11 | Salary band + equity + benefits — reasonable but location/level variance unknown |
| Scam / Legitimacy | 12 | 11 | Legit company (Series F, Crunchbase, corporate site); Simplify and press coverage present |
| Role Clarity | 10 | 8 | Posting is detailed about responsibilities, but some ambiguity in IaC ownership model |
| Growth & Stability | 10 | 6 | Funding is strong historically, but layoffs and small-negative growth raise concerns |

Total: 72/100 → 7.2/10.0

Decision mapping: falls into RESEARCH MORE (7.0–8.4).

Confidence & caveats

- Confidence: moderate (±0.6). Key unknowns: on-call policy & frequency, who currently owns IaC (platform vs application teams), team size/reporting line, and compensation by location.

Suggested follow-ups / Questions to ask if progressing

1. On-call: Is there a defined on-call rotation for this role? How often, expectations, and on-call comp (bonus, PTO, pager duty pay)?
2. Team structure: Which team does this role report into (Platform/SRE/Infrastructure)? How many people on the team today and planned hires?
3. IaC governance: The posting lists CDK, CloudFormation, and Terraform — which is the primary IaC in production? Is there a plan to standardize? Will the role be responsible for enforcing IaC guardrails or just enabling teams?
4. SRE practices: Are there SLOs/SLIs in place? Are blameless postmortems and incident management processes documented?
5. Stability: Can you clarify org changes referenced in press (layoffs) and how this role is positioned relative to those reorganizations?
6. Compensation: Confirm the target total comp and equity range for this role in my location (state) and level.

Next recommended action for Brent

- Email / apply only after clarifying on-call expectations and team structure (ask the 3 most critical Qs: on-call, team ownership, IaC primary tool). If answers indicate reasonable on-call and clear platform team ownership, move to phone screen.

Sources & verification trail

- Job posting (Simplify): [Simplify posting](https://simplify.jobs/p/600213a6-772e-4984-becb-60a45cc490e5/Senior-Devops-Engineer?utm_source=job_post&utm_medium=copy_link&utm_campaign=organic_share) — posting text, compensation band, and Simplify's notes about layoffs
- Company home: [Guild Education website](https://www.guildeducation.com/) — company overview, press links
- Guild news (example acquisition press): [Guild press release - Nomadic acquisition](https://guild.com/news-press/guild-announces-acquisition-of-nomadic-and-introduces-guild-talent-advantage)
- Crunchbase/company snapshot (linked from Simplify): [Crunchbase - Guild Education](https://www.crunchbase.com/organization/guild-education)
- Glassdoor reviews landing page: [Glassdoor - Guild Education reviews](https://www.glassdoor.com/Reviews/Guild-Education-Reviews-E1174528.htm)

Verification steps performed

1. Fetched full job posting via Simplify.jobs (captured role text and compensation). (fetch)
2. Opened Guild Education homepage to confirm corporate presence and press pages. (simple browser)
3. Opened Glassdoor and Google results pages to surface reviews and news articles about layoffs / reorganizations. (simple browser)

Assumptions made

- Compensation range shown on Simplify is accurate but may not reflect total comp in all locations.
- Simplify's "critics" / "layoffs" summary is accurate as a signal; further reading into primary news sources is advised for decisions that depend on headcount stability.

Final verdict

- RESEARCH MORE: The role is a credible, strong technical match for Brent but requires targeted clarifying questions about on-call, IaC ownership/governance, and team stability before recommending a full apply.

---

If you'd like, I can:

- Draft an outreach message or pre-screen email that asks the three highest-priority clarifying questions.
- Pull 2–3 news articles about the reported layoffs and summarize the timeline and scope.
- Create a short Evidence tracker JSON file in `research/` with the links and timestamps.
