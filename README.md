# show markdown

● online : https://dustinchen26.github.io/markdown_show

## How to use
```
上傳檔案 PowerOnSequence_Enhanced.json 
即可顯示 markdown

TerraEdge BIOS Power On Sequence Analysis Report (Enhanced v4)
Source Root: C:\Users\dustin\Desktop\ReleaseCode
Total Modules: 2878
Total OEM Hooks: 1774

1. Hardware Power-On Flow Mapping
HW Step	UEFI Phase	Code Entry Point	Source File
Step 5: CPLD Asserts AUX_PWRGOOD	Hardware	N/A	``
Step 6: CPU Reset De-asserted	SEC	resetVector	UefiCpuPkg/ResetVector/Vtf0/Ia16/ResetVectorVtf0.asm
Step 7: Microcode Load	SEC/PEI	ShadowMicrocodePeimInit	IntelSiliconPkg/Feature/ShadowMicrocode/ShadowMicrocodePei.c
Step 8-9: CAR Setup	SEC	SecStartupPhase2	UefiCpuPkg/SecCore/SecMain.c
Step 10: Memory Init (FSP-M)	PEI	FspmWrapperPeimEntryPoint	IntelFsp2WrapperPkg/FspmWrapperPeim/FspmWrapperPeim.c
Step 11: FSP-S Init	PEI	FspsWrapperPeimEntryPoint	IntelFsp2WrapperPkg/FspsWrapperPeim/FspsWrapperPeim.c
Step 12: DXE IPL	PEI	PeimInitializeDxeIpl	MdeModulePkg/Core/DxeIplPeim/DxeLoad.c
Step 13: DXE Core	DXE	DxeMain	MdeModulePkg/Core/Dxe/DxeMain/DxeMain.c
Step 14: PCIe Enum	DXE	PciBusDriverEntryPoint	MdeModulePkg/Bus/Pci/PciBusDxe/PciBusDxe.c
Step 15: BDS	BDS	BdsEntry	MdeModulePkg/Universal/BdsDxe/BdsEntry.c
Step 16: OS Boot	BDS	EfiBootManagerBoot	MdeModulePkg/Library/UefiBootManagerLib/BmBoot.c

2. Critical Device Initialization

```
