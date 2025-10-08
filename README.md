# JacksCyberSecOntology - Integrated Attack Path Analysis Framework

**Author:** Jack Trodes <dderwahnsinn@gmail.com>  
**License:** Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)  
**Version:** 1.0  
**Created:** 2025-10-08

## Overview

JacksCyberSecOntology is a comprehensive cybersecurity framework that integrates attack path analysis with compliance requirements for KRITIS operators and cybersecurity professionals. It provides quantitative risk assessment capabilities while mapping to international standards (ISO 27001, NIST CSF) and German/EU legal requirements (NIS2, CRA, BSIG).

## Key Features

- **93 Security Controls** across 4 domains (OpSec, TechSec, PhySec, HumSec)
- **MITRE ATT&CK Integration** with tactic mappings (TA0001-TA0011)
- **Attack Path Simulation** with quantitative success probability calculation
- **German Legal Compliance** (BSIG, KRITISDachG, NIS2UmsuCG)
- **EU Framework Integration** (NIS2, CRA, CER directives)
- **Supply Chain Risk Analysis** with IRAM2-based methodology
- **Vulnerability Intelligence** (EPSS scores, KEV status, CVE integration)

## Files Included

2. **JacksCyberSecOntology.db** - SQLite database with views and indices (233,472 bytes)
3. **README.md** - This documentation
5. **CHANGELOG.md** - Complete development history

## Usage

### Academic Research
```bibtex
@misc{trodes2025cybersec,
  author = {Jack Trodes},
  title = {Jacks CyberSec Ontology},
  year = {2025},
  license = {CC BY-SA 4.0},
  url = {https://github.com/JackTrodess/JacksCyberSecOntology}
}
```

### Commercial Use
This work is licensed under CC BY-SA 4.0, allowing commercial use with attribution. 
Any derivative works must be shared under the same license.

### Database Usage
```sql
-- Load main controls
SELECT * FROM cybersecurity_controls;

-- Check license compliance
SELECT * FROM copyright_compliance_dashboard;

-- View third-party attributions
SELECT * FROM third_party_attributions;
```

## Legal Compliance

All third-party frameworks are properly attributed:
- MITRE ATT&CK® (trademark attribution provided)
- NIST CSF (public domain)
- ISO 27001/27002 (fair use references)
- BSI IT-Grundschutz (educational exception)
- German/EU laws (official works exemption)

## Contact

For questions, collaboration, or licensing inquiries:
- **Email:** dderwahnsinn@gmail.com
- **Author:** Jack Trodes

## Disclaimer

This ontology is provided for educational and research purposes. No warranty is provided regarding completeness or accuracy. Use at your own risk.
