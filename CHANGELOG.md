# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.1.0] - 2026-11-08

### Changed
- Remapped every control mapping table from ISO/IEC 27001:2013 numbering (A.9, A.11, A.12, A.16, etc.) to ISO/IEC 27001:2022 Annex A, using the correspondence in ISO/IEC 27002:2022 Annex B. Rows that collapse into one 2022 control are merged.
- Added A.7.4 Physical security monitoring (new in 2022) to the Access Control, CCTV, and Post Orders mappings.
- Replaced the "ASIS EPP-2020" citation, which does not correspond to a published standard, with the ASIS Executive Protection Standard (2025).
- Updated README and SKILL.md domain tables to match.
## [1.0.0] - 2026-02-28

### Added
- Initial release with 11 policy domain reference files
- Core SKILL.md framework with ISO 27001/22301 alignment
- Document control framework with consistent structure across all domains
- Access Control policy reference (ISO 27001 A.11.1.1, A.11.1.2, A.9.2.x)
- CCTV / Video Surveillance policy reference (ISO 27001 A.11.1.1, GDPR, state wiretap laws)
- Key and Lock Control policy reference (ISO 27001 A.11.1.3)
- Emergency Response procedure reference (ISO 22301 8.4, OSHA 1910.38)
- Bomb Threat Response procedure reference (ISO 22301, DHS guidance)
- Visitor Management policy reference (ISO 27001 A.11.1.2)
- Workplace Violence Prevention policy reference (OSHA General Duty Clause, CA SB 553)
- Incident Reporting policy reference (ISO 27001 A.16)
- Security Officer Post Orders reference (ASIS standards)
- Executive Protection policy reference (ASIS EPP-2020)
- Security Program Charter reference (ISO 27001 A.5.1, ISO 22301 5.x)
- README with usage documentation
- Contributing guidelines
- CC BY-NC-SA 4.0 License
