---
name: physical-security-policies
description: Write professional physical security policies, procedures, and plans aligned with ISO 27001 (Annex A.11), ISO 22301, and ASIS standards. Use this skill whenever the user asks to draft, review, edit, or create any physical security policy, procedure, standard operating procedure (SOP), emergency plan, access control policy, CCTV policy, bomb threat procedure, key control program, visitor management policy, workplace violence prevention plan, incident response procedure, executive protection protocol, security officer post orders, or any document related to corporate physical security programs. Also trigger when the user mentions ISO certification prep for physical security, security policy templates, or compliance-ready security documentation.
---

# Physical Security Policy & Procedure Writer

Generate professional, ISO-aligned physical security policies and procedures ready for corporate adoption and certification audits.

## Core Principles

Every policy produced by this skill must:

1. Follow a consistent document control structure (see Document Framework below)
2. Align with ISO 27001 Annex A.11 (Physical and Environmental Security) and ISO 22301 (Business Continuity) where applicable
3. Use clear, enforceable language -- not aspirational statements
4. Call out every unknown or site-specific variable with `[USER INPUT REQUIRED: description]` tags so nothing gets silently assumed
5. Include measurable compliance indicators wherever possible
6. Be jurisdiction-aware -- flag legal requirements that vary by state, country, or industry

## Document Framework

ALWAYS use this structure for every policy document:

```
DOCUMENT CONTROL
- Document Title:
- Document ID: [USER INPUT REQUIRED: org document numbering scheme]
- Version:
- Classification: [USER INPUT REQUIRED: Internal / Confidential / Public]
- Effective Date:
- Review Date: [default: 12 months from effective date]
- Document Owner: [USER INPUT REQUIRED: title/role]
- Approved By: [USER INPUT REQUIRED: approving authority]
- Distribution: [USER INPUT REQUIRED: distribution list or "All Employees"]

REVISION HISTORY
| Version | Date | Author | Description of Changes |
|---------|------|--------|----------------------|
| 1.0     | [Date] | [Author] | Initial release |

1. PURPOSE
2. SCOPE
3. DEFINITIONS
4. ROLES AND RESPONSIBILITIES
5. POLICY STATEMENTS / PROCEDURE STEPS
6. COMPLIANCE AND ENFORCEMENT
7. RELATED DOCUMENTS
8. APPENDICES
```

## How to Use This Skill

### Step 1: Identify the Policy Domain

When the user requests a policy, match it to one of the supported domains below. If the request spans multiple domains, produce each as a separate document with cross-references.

**Supported Domains** (read the corresponding reference file before drafting):

| Domain | Reference File | ISO Alignment |
|--------|---------------|---------------|
| Access Control | `references/access-control.md` | ISO 27001 A.11.1.1, A.11.1.2 |
| CCTV / Video Surveillance | `references/cctv-surveillance.md` | ISO 27001 A.11.1.1, GDPR Art. 6 |
| Key & Lock Control | `references/key-control.md` | ISO 27001 A.11.1.3 |
| Emergency Response | `references/emergency-response.md` | ISO 22301, OSHA 1910.38 |
| Bomb Threat Response | `references/bomb-threat.md` | ISO 22301, DHS guidance |
| Visitor Management | `references/visitor-management.md` | ISO 27001 A.11.1.2 |
| Workplace Violence Prevention | `references/workplace-violence.md` | OSHA General Duty Clause |
| Incident Reporting | `references/incident-reporting.md` | ISO 27001 A.16, ISO 22301 |
| Security Officer Post Orders | `references/post-orders.md` | ASIS standards |
| Executive Protection | `references/executive-protection.md` | ASIS EPP standards |
| Security Program Charter | `references/program-charter.md` | ISO 27001 A.5.1 |

### Step 2: Gather Required Inputs

Before drafting, collect these minimum inputs (ask for any that are missing):

**Always Required:**
- Organization name
- Industry / sector
- Number of facilities (single site vs. multi-site)
- Approximate headcount
- Regulatory environment (federal, state, industry-specific)
- Existing security infrastructure (badge systems, cameras, guard force, etc.)

**Domain-Specific Inputs:**
- Read the relevant reference file for additional required inputs per domain

### Step 3: Draft the Policy

1. Read the appropriate reference file(s) from `references/`
2. Apply the Document Framework structure
3. Write in clear, directive language:
   - Use "shall" for mandatory requirements
   - Use "should" for recommended practices
   - Use "may" for optional or permissive actions
   - Never use "try to," "make an effort to," or other non-enforceable language
4. Mark every assumption or unknown with `[USER INPUT REQUIRED: specific description]`
5. Include compliance metrics in Section 6

### Step 4: ISO Certification Mapping

For every policy, append an ISO mapping table:

```
ISO CONTROL MAPPING
| ISO Standard | Control Reference | Control Title | How This Policy Addresses It |
|-------------|-------------------|---------------|------------------------------|
```

This makes audit evidence collection straightforward.

## Output Formatting Rules

- Use numbered sections and subsections (1.1, 1.2, 2.1, etc.)
- Use bullet points for lists of requirements, equipment, or roles
- Use tables for matrices, schedules, and mappings
- Use bold for defined terms on first use
- Keep paragraphs to 3-4 sentences maximum
- Include page headers/footers notation for print formatting

## Legal Compliance Flags

When drafting, flag these common legal landmines:

- **CCTV**: State wiretapping laws, union notification requirements, GDPR/privacy regulations, audio recording restrictions
- **Access Control**: ADA accessibility requirements, fire code egress requirements, union access rights
- **Workplace Violence**: State-specific reporting mandates, restraining order protocols, Duty to Warn obligations
- **Emergency Response**: OSHA requirements (1910.38), local fire marshal requirements, ADA evacuation considerations
- **Key Control**: State landlord-tenant laws (if applicable), union considerations
- **Executive Protection**: Concealed carry reciprocity, surveillance law variations, international travel considerations

Always include a disclaimer:

> This policy has been drafted for internal organizational use and should be reviewed by qualified legal counsel before adoption. Requirements vary by jurisdiction, industry, and collective bargaining agreements.

## Quality Checklist

Before presenting any policy, verify:

- [ ] Document control block is complete (with `[USER INPUT REQUIRED]` tags where needed)
- [ ] All sections from the Document Framework are present
- [ ] Language uses shall/should/may correctly
- [ ] Every assumption is flagged with `[USER INPUT REQUIRED]`
- [ ] ISO control mapping table is included
- [ ] Legal compliance flags are noted for the relevant jurisdiction
- [ ] Cross-references to related policies are listed
- [ ] Compliance metrics are defined and measurable
- [ ] Review cycle is specified (default: annual)
