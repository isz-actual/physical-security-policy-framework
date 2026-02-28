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
| ISO 27001 | A.11.1.1 | Physical security perimeter | Zone classification and boundary controls |
| ISO 27001 | A.11.1.2 | Physical entry controls | Credential management, authentication methods |
| ISO 27001 | A.11.1.3 | Securing offices, rooms, and facilities | Zone-specific access restrictions |
| ISO 27001 | A.11.1.4 | Protecting against external/environmental threats | Perimeter controls |
| ISO 27001 | A.11.1.5 | Working in secure areas | High-security zone procedures |
| ISO 27001 | A.11.1.6 | Delivery and loading areas | Loading dock access controls |
| ISO 27001 | A.9.2.1 | User registration and de-registration | Credential lifecycle |
| ISO 27001 | A.9.2.2 | User access provisioning | Access level assignment |
| ISO 27001 | A.9.2.5 | Review of user access rights | Credential audit and reconciliation |
| ISO 27001 | A.9.2.6 | Removal of access rights | Termination and revocation procedures |

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
