# SCM Solution — Hardware Development System

A structured reference system for hardware product development, covering the full journey from Idea through to Mass Production.

Built for use alongside Google Drive, Notion, and Odoo Knowledge.

---

## Live Site
[View the Phase Map →](https://patrick-scm-solution.github.io/SCM-hardware-dev-system/index.html)

---

## What's Inside

### Phase Map (`index.html`)
Interactive overview of all six development phases — Idea, PoC, Design, Test, Factory, Mass Production. Click any phase to expand deliverables, SCM Solution tasks, and gate criteria.

### Checklists
| File | Description |
|------|-------------|
| [ME Asset Checklist](https://patrick-scm-solution.github.io/SCM-hardware-dev-system/checklists/checklist-me-assets.html) | Mechanical Engineering asset checklist — master assembly through to manufacturer exports |
| [EE Asset Checklist](https://patrick-scm-solution.github.io/SCM-hardware-dev-system/checklists/checklist-me-assets.html) | Electrical Engineering asset checklist — schematics, Gerbers, BOM, CPL, test scripts |

### Tools
| File | Description |
|------|-------------|
[Handoff Manfest Tool](https://patrick-scm-solution.github.io/SCM-hardware-dev-system/tools/handoff-manifest.html) | Asset Pack Manifest Builder For Keeping Assets Organized |
### Coming Soon
- `checklists/dr0-gate.html` through `dr4-gate.html` — Design review gate checklists
- `templates/mrd.html` — Market Requirements Document template
- `templates/prd.html` — Product Requirements Document template
- `templates/trd.html` — Technical Requirements Document template
- `templates/handoff-manifest.html` — Handoff manifest template
- `sops/file-release.html` — File release SOP
- `sops/revision-control.html` — Revision control SOP

---

## Development Phases

| Phase | Gate | Key Activities |
|-------|------|----------------|
| Idea | DR0 — Concept | MRD, vendor shortlist, NDAs, Drive structure |
| PoC | DR1 — Prelim | PoC sample, market validation, PRD |
| Design | DR2 — Critical | ME + EE assets, DFM, TRD, handoff packages |
| Test | DR3 + EVT/DVT | Build, test, FAI, vendor audit, certifications |
| Factory | DR4 + PVT | Production line, PVT, operator training |
| MP | Mass Production | Yield, QC, logistics, failure analysis |

---

## Google Drive Structure

Create this folder structure for every new project:

```
/[Project_Name]/
  /00_Master_Checklist/
  /01_Master_Assembly/
  /02_Parts/
  /03_Native_CAD/          ← restricted access
  /04_Exports/             ← STEP, DXF, PDF
  /05_Drawings/
  /06_Supporting_Docs/
  /07_EE_Assets/
  /08_BOM_AVL/
  /09_Test_Scripts/
  /10_Vendor_Audits/
  /11_Contact_Log/
  /Handoff_Packages/
    /CM_RevA_[date]/
    /ODM_RevA_[date]/
    /SupplyChain_RevA_[date]/
```



© 2025 SCM Solution LTD.
