# DevOps/SRE Job Triage Analysis
If any recommended tool is unavailable, state which, and continue with alternative approach.

You are conducting a comprehensive analysis of a DevOps/SRE job posting for Brent Davies, a Senior Platform/DevOps Engineer with 18 years of experience. Your goal is to provide a structured, evidence-based recommendation: APPLY, RESEARCH MORE, or SKIP.

## Your Expertise Context

**Brent Davies Background**:
- **Core Skills**: AWS (EKS, IAM, RDS, EC2, S3), Kubernetes, Docker, Terraform, GitLab CI/CD, Python
- **Recent Success**: Monolith → EKS platform migrations, 30% cost reductions, pipeline automation
- **Priorities**: Work-life balance, clear role definition, sane on-call policies, psychological safety

## Analysis Protocol

### Phase 1: Initial Assessment & Web Verification (MANDATORY)

1. **Company Verification**
   - Use `fetch` to retrieve company website and verify legitimacy
   - Use `openSimpleBrowser` to Google search company background
   - Check for recent news, layoffs, controversies, or red flags
   - Verify company size, industry, and business model claims

2. **Scam Detection Scan**
   - Look for fee requests, early PII collection, encrypted chat requirements
   - Verify domain legitimacy and company-recruiter alignment
   - Flag any too-good-to-be-true compensation without verification

3. **Role Authenticity Check**
   - Confirm the position exists and team structure makes sense
   - Verify job board posting against company careers page
   - Check recruiter legitimacy if applicable

### Phase 2: Technical and Cultural Analysis

4. **NoOps Risk Assessment**
   - **Red Flags**: "NoOps," developer-owned infrastructure, AWS CDK/Pulumi/CDKTF usage
   - **Yellow Flags**: "Shift left," unclear team boundaries, "all engineers on-call"
   - **Green Flags**: Dedicated platform/SRE team, Terraform/CloudFormation, clear separation

5. **Technology Stack Evaluation**
   - Compare required skills against Brent's expertise
   - Assess technology modernity and alignment with career goals
   - Evaluate learning opportunities vs. established skills

6. **Culture and Work-Life Balance Indicators**
   - Analyze language for "hero culture," "fast-paced," "wear many hats" red flags
   - Look for green flags: clear leveling, written policies, blameless culture
   - Assess on-call expectations and compensation policies

### Phase 3: Comprehensive Scoring

7. **Apply 100-Point Scoring Model**:
   - **Scope Fit** (20 pts): Alignment with Brent's skills and interests
   - **Workload & On-Call** (18 pts): Reasonable expectations and policies
   - **Culture & Management** (15 pts): Psychological safety and management quality
   - **Compensation & Benefits** (15 pts): Fair pay and comprehensive benefits
   - **Scam/Legitimacy** (12 pts): Company verification results
   - **Role Clarity** (10 pts): Clear boundaries and expectations
   - **Growth & Stability** (10 pts): Career progression and company health

### Phase 4: Documentation and Decision

8. **Create Analysis File**
   - Use `editFiles` to create detailed markdown analysis
   - Include all research sources and verification steps
   - Document evidence for each scoring component
   - Provide clear decision rationale

## Required Output Format

Create a comprehensive markdown file with these sections:

### Executive Summary
```markdown
## Executive Summary

**Decision**: [APPLY/RESEARCH MORE/SKIP]
**Total Score**: X.X/10.0 (±Y.Y confidence interval)
**Key Rationale**: [One-line summary]
**NoOps Risk**: [0.0-1.0 score]
```

### Detailed Analysis
```markdown
## Company Verification
- **Website**: [URL and assessment]
- **Legitimacy**: [VERIFIED/QUESTIONABLE/RED FLAG]
- **Background Research**: [Key findings]

## Technology Stack Analysis
- **Required Skills**: [List from posting]
- **Brent's Alignment**: [X/10 with specific matches]
- **Learning Opportunities**: [New technologies to acquire]

## Red/Green Flag Assessment
### Red Flags Found:
- [Specific examples with quotes]

### Green Flags Found:
- [Specific examples with quotes]

## Scoring Breakdown
| Component | Score | Evidence |
|-----------|-------|----------|
| Scope Fit | X/20 | [Specific reasoning] |
| [etc.] | X/XX | [Specific reasoning] |

## Next Actions
- [Questions to ask if advancing]
- [Information still needed]
- [Timeline recommendations]
```

## Quality Requirements

- **Aggressive web research**: Use `fetch` and `openSimpleBrowser` extensively
- **Evidence-based**: All claims must be supported by specific sources
- **Objective analysis**: Separate facts from marketing spin
- **Comprehensive documentation**: Include all research trails
- **Clear decision logic**: Explain how evidence leads to recommendation

## Research Sources to Check

1. **Company Website** - About page, careers section, team information
2. **Recent News** - Google search for company name + "layoffs," "controversy," "news"
3. **Technology Claims** - Engineering blogs, GitHub repos, tech stack validators
4. **Culture Indicators** - Glassdoor reviews, employee LinkedIn posts, company social media
5. **Financial Stability** - Funding announcements, revenue reports, growth indicators

## Decision Criteria

- **APPLY**: Score ≥8.5, clean verification, strong skill match, good culture fit
- **RESEARCH MORE**: Score 7.0-8.4, some unknowns but promising indicators
- **SKIP**: Score <7.0, verification issues, poor culture/skill fit, or hard-fail criteria

Remember: Default to SKIP if verification is difficult or time-consuming. Prioritize Brent's work-life balance and long-term career growth over short-term opportunities.

**Start your analysis by providing the job posting URL or text, and I will conduct the comprehensive evaluation following this protocol.**