# BST SesameX 硬件资料

[English](README.md) | 简体中文

本仓库收录 Aura NX-5000 和 Kalos NX-3000 模组及其开发套件的硬件资料。文件保留原始名称，便于识别文档版本。

## 目录

### Aura NX-5000

**模组数据手册、载板规格书及点位图**

- [Aura DevKit Carrier Board Specification_DX-5000-D_V1.2.5.pdf](<aura-nx-5000/datasheets/Aura DevKit Carrier Board Specification_DX-5000-D_V1.2.5.pdf>)
- [Aura Module Datasheet_NX-5000-D_V1.11.pdf](<aura-nx-5000/datasheets/Aura Module Datasheet_NX-5000-D_V1.11.pdf>)
- [Aura_Module_BOT点位图.pdf](<aura-nx-5000/datasheets/Aura_Module_BOT点位图.pdf>)
- [Aura_Module_TOP点位图.pdf](<aura-nx-5000/datasheets/Aura_Module_TOP点位图.pdf>)

**原理图和 PCB 布局**

- [QSC801XP-AP_EVB_PCB_V1.2_20260310.brd](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_EVB_PCB_V1.2_20260310.brd>)
- [QSC801XP-AP_EVB_SCH_V1.2_20260430.pdf](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_EVB_SCH_V1.2_20260430.pdf>)
- [QSC801XP-AP_SCH_V1.1.pdf](<aura-nx-5000/schematics-and-pcb/QSC801XP-AP_SCH_V1.1.pdf>)

**3D 模型**

- [00_qsc801xp-ap_v1-2_pcba_3d_260415.stp](<aura-nx-5000/3d-models/00_qsc801xp-ap_v1-2_pcba_3d_260415.stp>)

### Kalos NX-3000

**模组数据手册、载板规格书及点位图**

- [Kalos DevKit Carrier Board Specification_DX-3000-D.pdf](<kalos-nx-3000/datasheets/Kalos DevKit Carrier Board Specification_DX-3000-D.pdf>)
- [Kalos Module Datasheet_NX-3000-D_V1.4.pdf](<kalos-nx-3000/datasheets/Kalos Module Datasheet_NX-3000-D_V1.4.pdf>)

**原理图和 PCB 布局**

- [RC01_CARRIER_V100-20260211C.pdf](<kalos-nx-3000/schematics-and-pcb/RC01_CARRIER_V100-20260211C.pdf>)
- [RC01_CARRIER_V100-20260212C.brd](<kalos-nx-3000/schematics-and-pcb/RC01_CARRIER_V100-20260212C.brd>)
- [RC01_CORE_V100.pdf](<kalos-nx-3000/schematics-and-pcb/RC01_CORE_V100.pdf>)

**3D 模型**

- [rc01-all_20260330_0415.stp](<kalos-nx-3000/3d-models/rc01-all_20260330_0415.stp>)

## 文件完整性

[SHA256SUMS](SHA256SUMS) 提供文件的 SHA-256 校验值。在仓库根目录执行 `sha256sum -c SHA256SUMS`，即可验证文件完整性。

## 文件格式

- PDF：数据手册、规格书、原理图和点位图。
- BRD：PCB 布局文件，需要使用兼容的 PCB 设计查看工具。
- STP：3D 模型，需要使用兼容 STEP 的 CAD 查看工具。

## Git LFS

PCB 布局（`.brd`）和 3D 模型（`.stp`）文件使用 Git LFS 管理。克隆前请先安装 Git LFS，以获取实际文件。如果克隆结果中包含 LFS 指针，请在仓库内执行 `git lfs install` 和 `git lfs pull`。
