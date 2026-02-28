# Contributing to Physical Security Policy Framework

Contributions that improve the quality, coverage, and global applicability of this framework are welcome.

## What We're Looking For

**High-value contributions:**
- Country-specific legal compliance additions (EU, UK, Australia, Singapore, Japan, etc.)
- Industry-specific regulatory overlays (healthcare/HIPAA, financial services/SOX, critical infrastructure/NERC CIP, government/FedRAMP)
- New policy domains (travel security, investigations, use of force, mail and package screening, parking security, construction site security)
- Translations of reference files
- Corrections to ISO control mappings or legal references
- Compliance metric improvements based on operational experience

**What does not fit:**
- Organization-specific policies (this is a generic framework)
- Vendor-specific implementation guides
- Content that requires proprietary tools or paid platforms to use
- Marketing or promotional content

## How to Contribute

1. **Fork the repository** and create a feature branch from `main`.
2. **Make your changes.** Follow the formatting conventions described below.
3. **Submit a pull request** with a clear description of what you changed and why.

## Formatting Conventions

**Reference files** (`references/*.md`) shall follow this structure:

```markdown
# [Domain] Policy Reference

## Domain-Specific Inputs Required
- [List of inputs needed before drafting]

## Key Policy Provisions to Include
### [Sub-section]
- [Detailed provisions]

## ISO Control Mapping
| ISO Standard | Control | Title | Relevance |
|---|---|---|---|

## Compliance Metrics
- [Measurable KPIs]

## Common Legal Considerations
- [Jurisdiction-specific flags]
```

**Language rules:**
- Use "shall" for mandatory requirements
- Use "should" for recommended practices
- Use "may" for optional actions
- No aspirational language ("strive to," "endeavor to," etc.)
- Flag unknowns with `[USER INPUT REQUIRED: description]`

**Legal contributions:**
- Cite the specific statute, regulation, or standard
- Include the jurisdiction and effective date
- Note if the requirement is industry-specific
- Do not provide legal opinions or interpretations

## Code of Conduct

Be professional. Disagree on substance, not personalities. This is a security practitioner community, and the bar for professional conduct is high.

## Questions

Open an issue or reach out via LinkedIn: [Tim Reed, CPP](https://www.linkedin.com/in/timreedcpp/)
