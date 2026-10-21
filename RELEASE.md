# ModusToolbox PSE8XXGP BSP Template Library Release Notes

### What Changed?
#### v1.5.0
- Added LLVM 22.1.0 compiler support
#### v1.4.0
- Fixed GCC_ARM 14.2.1 linker warning "LOAD segment with RWX permissions" in CM33/CM55 linker scripts
- Fixed ARM compiler warnings in system_edge.h caused by weak inline crypto remap address
#### v1.3.0
- Updated BSP template dependencies
- Added CYBSP_MCUBOOT_HEADER_SIZE define to bsp.mk
#### v1.2.0
- Enhanced API naming for CM55/U55/CM33 special operations while maintaining backward compatibility
- Added CM55 debug mode configuration option during enablement
- Updated documentation
#### v1.1.0
Minor bug-fixes
#### v1.0.0
Initial release

### Supported Software and Tools
This version of mtb-template-pse8xxgp was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---------------------------------------- | :-----: |
| ModusToolbox™ Software Environment        | 3.8.0   |
| GCC Compiler                              | 14.2.1  |
| IAR Compiler                              | 9.70.4  |
| ARM Compiler                              | 6.22    |
| Arm Toolchain for Embedded (ATfE)         | 22.1.0  |

Minimum required ModusToolbox™ Software Environment: v3.8.0

### More information
* [Development Board Documentation](https://www.infineon.com/cms/en/design-support/finder-selection-tools/product-finder/evaluation-board/)
* [Infineon Technologies AG](https://www.infineon.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.infineon.com/modustoolbox)

---
© Infineon Technologies AG or an affiliate of Infineon Technologies AG, 2022-2026.