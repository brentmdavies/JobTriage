---
description: 'DevOps/SRE Job Analysis Instructions - Guidelines for analyzing job postings with structured skepticism, web verification, and comprehensive documentation'
---

# DevOps/SRE Job Analysis Instructions

## File Organization Standards

### Project Structure
```
/job-analysis-project/
├── analyses/           # Individual job analysis files
├── templates/         # Analysis templates
├── research/          # Company research files
├── scoring/           # Scoring matrices and criteria
└── README.md         # Project overview and usage
```

### File Naming Conventions
- **Job Analyses**: `YYYY-MM-DD_CompanyName_Position.md`
- **Research Files**: `YYYY-MM-DD_CompanyName_research.md`
- **Scoring Files**: `YYYY-MM-DD_CompanyName_scoring.json`

## Analysis Documentation Standards

### Required Sections for Job Analysis Files
1. **Job Posting Source** - URL, date found, recruiter info
2. **Company Verification** - Website, legitimacy checks, background
3. **Role Analysis** - Scope fit, skill alignment, clarity assessment
4. **Red/Green Flag Assessment** - Specific indicators found
5. **NoOps Risk Evaluation** - Technology signals and organizational structure
6. **Scoring Matrix** - Detailed breakdown with evidence
7. **Decision and Rationale** - Final recommendation with confidence level
8. **Next Actions** - Questions to ask, information needed
9. **Research Trail** - All sources checked and verification steps

### Markdown Formatting Standards
- Use H2 (##) for main sections
- Use H3 (###) for subsections
- Use tables for scoring matrices
- Use checkboxes for verification checklists
- Use blockquotes for direct job posting quotes
- Use code blocks for technical details

### Evidence Documentation
- **Link all sources** with working URLs
- **Quote directly** from job postings and company materials
- **Timestamp all research** with date/time of verification
- **Flag unverified claims** clearly
- **Maintain objectivity** - separate facts from interpretation

## Web Research Standards

### Mandatory Verification Steps
1. **Company Website Analysis**
   - Verify legitimate business operations
   - Check for professional web presence
   - Analyze company size and structure claims

2. **Background Research**
   - Recent news and press coverage
   - Financial stability indicators
   - Leadership team verification
   - Glassdoor or similar review analysis

3. **Technology Stack Verification**
   - Confirm claimed technologies are actually used
   - Check for consistency with job requirements
   - Assess alignment with candidate skills

### Research Documentation Format
```markdown
## Research Conducted

### Company Verification
- **Website**: [URL] - Verified [DATE]
- **Business Registration**: [Details if found]
- **Recent News**: [Summary with sources]

### Technology Analysis
- **Claimed Stack**: [From job posting]
- **Verified Usage**: [From research]
- **Alignment Score**: X/10 with Brent's skills

### Risk Assessment
- **Legitimacy Score**: VERIFIED/QUESTIONABLE/RED FLAG
- **NoOps Risk**: [0.0-1.0] based on [specific signals]
```

## Scoring and Decision Standards

### Scoring Consistency
- Use the same 100-point scale for all analyses
- Document evidence for each score component
- Include confidence intervals (±) for uncertain areas
- Maintain scoring calibration across analyses

### Decision Criteria
- **APPLY**: Score ≥8.5, all verification passed, strong skill alignment
- **RESEARCH MORE**: Score 7.0-8.4, some unknowns but promising
- **SKIP**: Score <7.0 or any hard-fail criteria met

### Quality Assurance
- Cross-reference multiple sources for key claims
- Flag all assumptions and uncertainties
- Maintain evidence trail for all decisions
- Update analyses if new information emerges

## Tool Integration Requirements

### GitHub Copilot Usage
- Use web research tools aggressively for verification
- Leverage analysis templates for consistency
- Maintain comprehensive documentation
- Cross-reference similar analyses for calibration

### File Management
- Create separate analysis files for each opportunity
- Maintain master tracking spreadsheet/file
- Archive completed analyses with final decisions
- Update templates based on learning and experience

## Communication Standards

### Internal Documentation
- Write for future reference and pattern recognition
- Include lessons learned and calibration notes
- Document false positives and negatives for improvement

### External Communication Prep
- Prepare questions based on unknowns identified
- Draft follow-up scripts for promising opportunities
- Maintain professional tone while preserving skepticism
- Document negotiation points for salary/benefits discussions

## Continuous Improvement

### Pattern Recognition
- Track common red flags across multiple analyses
- Identify reliable green flag indicators
- Calibrate scoring based on outcomes
- Refine NoOps detection criteria

### Template Evolution
- Update analysis templates based on experience
- Refine research checklists for efficiency
- Improve scoring criteria accuracy
- Enhance decision-making frameworks

Remember: These instructions ensure consistent, thorough, and objective analysis while maximizing efficiency and minimizing cognitive load for decision-making.