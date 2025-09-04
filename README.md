# Master Triage Filter Repository (Internal Use Only)

This repository tracks all triage filters created across customer Brains.  
It provides analysts with a searchable reference for past decisions to ensure consistency, faster triage, and audit readiness.

---

## Categories
- Botnet
- C&C
- Lateral
- Recon
- Exfil
- Info

Each category has its own folder where individual triage filter entries are stored.

---

## Entry Format
Each triage filter is stored as a markdown file in the respective category folder:

**Filename convention:**  YYYY-MM-DD_Customer_FilterName.md


**Example:**  
`2025-08-30_CustomerX_SMBBruteForce.md`

---

## Triage Filter Entry Template
```markdown
# Triage Filter Entry

**Category:** [Category → Sub-Category]  
**Customer:** [Customer Name]  
**Date Created:** YYYY-MM-DD  
**Created By:** [Analyst Name]  
**Filter Logic:** [Description of filter logic applied]  
**Justification:** [Reason for creation and validation outcome]  
**Detection ID / Link:** [Vectra Brain link placeholder]  
**Status:** Active / Retired  
**Review Date:** YYYY-MM-DD  

### Analyst Notes
- [Supporting notes and validation]


```
See `TriageFilter_Template.md` in each category folder for the entry format.


All new triage filter entries must follow this convention and be saved under the correct category folder.
