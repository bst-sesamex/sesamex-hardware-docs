# BST SesameX Hardware Documents

English | [简体中文](README_zh-CN.md)

Hardware documents for the Aura NX-5000 and Kalos NX-3000 modules and their developer kits. Original file names are retained to identify document revisions.

## Contents

### Aura NX-5000

**Datasheets, carrier board specifications and placement drawings**

- [Aura DevKit Carrier Board Specification_DX-5000-D_V1.2.5.pdf](<aura-nx-5000/datasheets/Aura DevKit Carrier Board Specification_DX-5000-D_V1.2.5.pdf>)
- [Aura Module Datasheet_NX-5000-D_V1.11.pdf](<aura-nx-5000/datasheets/Aura Module Datasheet_NX-5000-D_V1.11.pdf>)
- [Aura_Module_BOT点位图.pdf](<aura-nx-5000/datasheets/Aura_Module_BOT点位图.pdf>)
- [Aura_Module_TOP点位图.pdf](<aura-nx-5000/datasheets/Aura_Module_TOP点位图.pdf>)

**Schematics and PCB layout**

- [QSC801XP-AP_EVB_PCB_V1.2_20260310.brd](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_EVB_PCB_V1.2_20260310.brd>)
- [QSC801XP-AP_EVB_SCH_V1.2_20260430.pdf](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_EVB_SCH_V1.2_20260430.pdf>)
- [QSC801XP-AP_SCH_V1.1.pdf](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_SCH_V1.1.pdf>)

**3D models**

- [00_qsc801xp-ap_v1-2_pcba_3d_260415.stp](<aura-nx-5000/3d-models/00_qsc801xp-ap_v1-2_pcba_3d_260415.stp>)

### Kalos NX-3000

**Datasheets, carrier board specifications and placement drawings**

- [Kalos DevKit Carrier Board Specification_DX-3000-D.pdf](<kalos-nx-3000/datasheets/Kalos DevKit Carrier Board Specification_DX-3000-D.pdf>)
- [Kalos Module Datasheet_NX-3000-D_V1.4.pdf](<kalos-nx-3000/datasheets/Kalos Module Datasheet_NX-3000-D_V1.4.pdf>)

**Schematics and PCB layout**

- [RC01_CARRIER_V100-20260211C.pdf](<kalos-nx-3000/schematics-and-pcb/RC01_CARRIER_V100-20260211C.pdf>)
- [RC01_CARRIER_V100-20260212C.brd](<kalos-nx-3000/schematics-and-pcb/RC01_CARRIER_V100-20260212C.brd>)
- [RC01_CORE_V100.pdf](<kalos-nx-3000/schematics-and-pcb/RC01_CORE_V100.pdf>)

**3D models**

- [rc01-all_20260330_0415.stp](<kalos-nx-3000/3d-models/rc01-all_20260330_0415.stp>)

## File integrity

SHA-256 checksums are provided in [SHA256SUMS](SHA256SUMS). Run `sha256sum -c SHA256SUMS` from the repository root to verify the files.

## File formats

- PDF: datasheets, specifications, schematics and placement drawings.
- BRD: PCB layout files; a compatible PCB design viewer is required.
- STP: 3D models; a STEP-compatible CAD viewer is required.

## Git LFS

PCB layout (`.brd`) and 3D model (`.stp`) files are tracked with Git LFS. Install Git LFS before cloning to obtain the actual files. If a clone contains LFS pointers, run `git lfs install` and `git lfs pull` in the repository.
