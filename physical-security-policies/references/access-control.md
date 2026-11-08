# Access Control Policy Reference

## Domain-Specific Inputs Required

- Badge/credential system vendor and type (e.g., HID, Lenel, Genetec)
- Number and classification of access zones
- Hours of operation per facility
- Tailgating/piggybacking countermeasures in use
- Integration with HR onboarding/offboarding systems
- Visitor management system (if separate from badge system)
- Loading dock / delivery access procedures
- Parking structure access controls
- After-hours access authorization process
- Union or CBA considerations for access restrictions

## Key Policy Provisions to Include

### Zone Classification
Define a tiered access zone model. Standard tiers:
- **Zone 1 - Public**: Lobbies, reception areas, public-facing spaces
- **Zone 2 - General Employee**: Office areas, break rooms, common workspaces
- **Zone 3 - Restricted**: Server rooms, R&D labs, executive suites, security operations centers
- **Zone 4 - High Security**: SCIFs, vaults, evidence storage, classified areas

Each zone shall specify:
- Who is authorized
- How authorization is granted and by whom
- What credential type is required (badge, badge + PIN, biometric, escort)
- Time-of-day restrictions
- Logging and audit requirements

### Credential Lifecycle
Cover the full lifecycle:
1. Credential issuance (new hire, contractor, visitor, temporary)
2. Credential activation and access level assignment
3. Credential modifications (role changes, transfers, project-based access)
4. Credential suspension (leave of absence, investigation, termination)
5. Credential revocation and physical return
6. Lost/stolen credential procedures
7. Credential audit schedule and reconciliation

### Anti-Tailgating / Anti-Piggybacking
- Employee responsibility to challenge or report
- Technical controls (mantrap, turnstile, optical sensors)
- Reporting mechanism
- Enforcement and consequences

### After-Hours and Emergency Access
- Authorization chain for after-hours access
- Lone worker procedures
- Emergency override protocols (fire, medical, law enforcement)
- Documentation requirements for emergency access events

### Contractor and Vendor Access
- Sponsorship requirements
- Background check requirements before access granted
- Escort requirements by zone
- Access duration limits and renewal process
- NDA and security acknowledgment requirements

## ISO Control Mapping

| ISO Standard | Control | Title | Relevance |
|-------------|---------|-------|-----------|
| ISO/IEC 27001:2022 | A.7.1 | Physical security perimeters | Zone classification and boundary controls |
| ISO/IEC 27001:2022 | A.7.2 | Physical entry | Credential management, authentication methods, loading dock access controls |
| ISO/IEC 27001:2022 | A.7.3 | Securing offices, rooms and facilities | Zone-specific access restrictions |
| ISO/IEC 27001:2022 | A.7.5 | Protecting against physical and environmental threats | Perimeter controls |
| ISO/IEC 27001:2022 | A.7.6 | Working in secure areas | High-security zone procedures |
| ISO/IEC 27001:2022 | A.5.16 | Identity management | Credential lifecycle |
| ISO/IEC 27001:2022 | A.5.18 | Access rights | Access level assignment, credential audit and reconciliation, termination and revocation procedures |
| ISO/IEC 27001:2022 | A.7.4 | Physical security monitoring | Access event monitoring and alarm response |

## Compliance Metrics

- Percentage of terminated employees with credentials deactivated within [USER INPUT REQUIRED: SLA, e.g., 4 hours]
- Percentage of access logs reviewed per [USER INPUT REQUIRED: frequency, e.g., weekly/monthly]
- Number of tailgating incidents reported per quarter
- Credential audit reconciliation rate (issued vs. active vs. recovered)
- Time from access request to provisioning (measure against SLA)
- Percentage of contractors with expired access still active (target: 0%)

## Common Legal Considerations

- ADA: Accessible entry points must not be less secure than primary entry points
- Fire Code: Access controls must not impede emergency egress (fail-safe vs. fail-secure configuration)
- OSHA: Means of egress must remain unobstructed (29 CFR 1910.36)
- Union/CBA: Restrictions on monitoring employee movement may apply
- State Privacy Laws: Biometric data collection (Illinois BIPA, Texas CUBI, Washington state biometric law)
