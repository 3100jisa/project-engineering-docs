# Project Engineering Documentation

> Documentation repository for SW/FW/HW project development, based on **SPICE** (Automotive SPICE) and **SPICE** (ISO/IEC 15504) best practices.  
> Applicable to automotive, aerospace, and safety-critical embedded systems.

## Standards & Frameworks Referenced

| Standard | Domain | Description |
|---|---|---|
| SPICE 3.1 | Automotive | Automotive SPICE process reference & assessment model |
| ISO/IEC 15504 (SPICE) | General | Software process improvement & capability determination |
| ISO 26262 | Automotive | Functional safety for road vehicles |
| IEC 61508 | General | Functional safety of E/E/PE systems |
| DO-178C | Aerospace | Software considerations in airborne systems |
| DO-254 | Aerospace | Design assurance guidance for airborne electronic hardware |
| ARP4754A | Aerospace | Guidelines for development of civil aircraft and systems |
| MISRA-C:2012 | Embedded SW | C language guidelines for safety-critical systems |

## Repository Structure

| Folder | Content | SPICE Process |
|---|---|---|
| `00_process_framework/` | Standards overview, capability model | — |
| `01_project_management/` | Project plan, risk, metrics | MAN.3, MAN.5, MAN.6 |
| `02_system_engineering/` | StRS, SyRS, system architecture, integration & test | SYS.1–SYS.5 |
| `03_software_engineering/` | SRS, SW architecture, design, unit & integration test | SWE.1–SWE.6 |
| `04_firmware_engineering/` | FW requirements, BSP, embedded safety | FW-specific |
| `05_hardware_engineering/` | HRS, HW design, integration & qualification test | HWE.1–HWE.4 |
| `06_supporting_processes/` | QA, verification, CM, problem & change mgmt | SUP.1–SUP.10 |
| `07_safety_and_compliance/` | Functional safety plan, HARA, FMEA, compliance | ISO 26262, IEC 61508 |
| `08_traceability/` | RTM, test coverage, impact analysis | SUP.2 |
| `09_tools_and_environments/` | Toolchain, CI/CD, tool qualification | SUP.8 |
| `10_reviews_and_audits/` | Code, design, TRR checklists | SUP.4 |
| `11_release_management/` | Release process, notes, delivery checklist | SUP.8 |
| `12_lessons_learned/` | Lessons learned per discipline | All |

## Contributing

Please follow the [documentation guidelines](06_supporting_processes/documentation_guidelines.md) when adding or updating documents.  
For lessons learned, use the [template](12_lessons_learned/lessons_learned_template.md).

## Status Legend

| Icon | Meaning |
|---|---|
| 🚧 | Placeholder — not yet written |
| 📝 | Draft — work in progress |
| ✅ | Approved / Baseline |
| 🔒 | Controlled document |