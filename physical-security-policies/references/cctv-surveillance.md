# CCTV / Video Surveillance Policy Reference

## Domain-Specific Inputs Required

- VMS platform (e.g., Genetec, Milestone, Verkada, Avigilon)
- Number of cameras and general coverage areas
- Recording retention period requirements (regulatory and business)
- Whether audio recording is in use or planned
- Cloud vs. on-premise storage architecture
- Integration with access control or analytics platforms
- Body-worn camera use (security officers, EP teams)
- Covert camera use (investigations only, or not at all)
- Jurisdictions covered (multi-state, international)
- Union presence and applicable CBAs
- Industry-specific regulations (healthcare HIPAA, financial SOX, etc.)

## Key Policy Provisions to Include

### Purpose and Scope
Clearly state the business purposes for video surveillance:
- Protection of employees, visitors, and assets
- Deterrence of criminal activity
- Support of incident investigations
- Verification of access control events
- Safety and compliance monitoring

Explicitly state what surveillance is NOT used for:
- General employee productivity monitoring (unless legally permitted and disclosed)
- Personal surveillance of specific individuals without cause

### Camera Placement Standards
- Public and common areas: lobbies, parking, perimeters, loading docks
- Restricted areas: server rooms, vaults, executive areas
- **Prohibited areas**: Restrooms, lactation rooms, changing areas, union meeting rooms (where applicable), medical treatment areas
- Signage requirements per jurisdiction
- Covert camera authorization process (if permitted)

### Recording Standards
- Minimum resolution requirements per camera type (e.g., 1080p for identification zones, 720p for general surveillance)
- Frame rate requirements (e.g., 15fps minimum, 30fps for critical areas)
- Retention schedule:
  - Standard footage: [USER INPUT REQUIRED: e.g., 30 days]
  - Incident-related footage: [USER INPUT REQUIRED: e.g., 1 year or until case closure]
  - Litigation hold footage: Until released by legal counsel
- Storage redundancy requirements
- Encryption at rest and in transit

### Access to Footage
Define who can:
- View live feeds (security operations center, security management)
- Review recorded footage (security investigators, HR with security escort, legal)
- Export footage (security management only, with chain of custody documentation)
- Authorize external disclosure (legal counsel, law enforcement liaison)

### Law Enforcement Requests
- All requests routed through [USER INPUT REQUIRED: role, e.g., Director of Security or Legal Department]
- Subpoena/warrant requirements before release
- Voluntary disclosure criteria
- Documentation and logging of all disclosures
- Preservation of original footage (provide copies only)

### Analytics and AI
If video analytics are in use or planned:
- Facial recognition use and restrictions
- License plate recognition (LPR/ANPR) use and data handling
- People counting and heat mapping
- Behavioral analytics (loitering, perimeter breach)
- Data retention for analytics metadata
- Bias testing and accuracy validation for AI-based systems

### Maintenance and Testing
- Camera health check schedule (daily automated, weekly manual review)
- Annual coverage audit (verify camera views match security requirements)
- Failover and redundancy testing
- Firmware/software update schedule

## ISO Control Mapping

| ISO Standard | Control | Title | Relevance |
|-------------|---------|-------|-----------|
| ISO 27001 | A.11.1.1 | Physical security perimeter | Perimeter camera coverage |
| ISO 27001 | A.11.1.2 | Physical entry controls | Entry point camera verification |
| ISO 27001 | A.11.1.6 | Delivery and loading areas | Loading dock surveillance |
| ISO 27001 | A.12.4.1 | Event logging | Video recording as event log |
| ISO 27001 | A.12.4.3 | Administrator and operator logs | Access to VMS audit trail |
| ISO 27001 | A.18.1.4 | Privacy and PII protection | Camera placement restrictions, data handling |

## Compliance Metrics

- Camera uptime percentage (target: 99.5%+)
- Percentage of cameras meeting resolution standards
- Average time to respond to camera failure alerts
- Footage retrieval success rate for incidents within retention period
- Number of unauthorized access attempts to VMS per quarter
- Annual coverage audit completion rate
- Signage compliance rate across all facilities

## Common Legal Considerations

- **Federal**: No comprehensive federal video surveillance law for private sector; wiretap laws (18 USC 2511) apply to audio
- **State wiretapping/eavesdropping**: One-party vs. two-party consent states affect audio recording
  - [USER INPUT REQUIRED: List operating states/jurisdictions]
  - California, Connecticut, Florida, Illinois, Maryland, Massachusetts, Montana, Nevada, New Hampshire, Pennsylvania, Washington require all-party consent for audio
- **GDPR** (if operating in EU/EEA): Lawful basis required, DPIA mandatory, data subject access rights, signage requirements, retention limits
- **Illinois BIPA**: If using facial recognition, specific consent and data handling requirements
- **Union/CBA**: May restrict camera placement, require notification, or limit use of footage for discipline
- **Healthcare (HIPAA)**: Camera placement must not capture protected health information
- **Retail**: State-specific fitting room surveillance prohibitions
