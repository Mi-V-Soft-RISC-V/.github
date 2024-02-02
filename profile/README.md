# Mi-V Soft RISC-V

We offer a comprehensive suite of software tool chains and IP cores for your FPGA designs. 
The Mi-V RV32 RISC-V cores are available for PolarFire®, RTG4™ and IGLOO® 2 FPGAs. 
The Libero® SoC Design Suite provides complete support for FPGA designs and the Eclipse-based SoftConsole IDE provides a development environment, GCC compiler and debugger needed for C/C++ embedded firmware development.

The Libero SoC Design Suite and SoftConsole development environments provide all the required tools to port RISC-V soft CPUs on our FPGAs and develop, test and debug embedded firmware.

For more information please see the Mi-V RISC-V Soft CPUs [product page](https://www.microchip.com/en-us/products/fpgas-and-plds/fpga-and-soc-design-tools/mi-v/soft-cpus).

## Getting started

This organisation provides the following for users to get started using the Mi-V soft RISC-V CPUs:

- FPGA design generation Tcl scripts
- FPGA programming job files
- Bare metal embedded software
    - Driver examples
    - Bootloader applications
- Documentation

For more information see "Resources" below.

## Support and contributing

For community support, issues, feature and enhancement requests please use the organization's [discussion forum](https://github.com/orgs/Mi-V-Soft-RISC-V/discussions).

For information on contributing to this project please see our [contributing guidelines]().

For technical support please open a tech support case with [Microchip tech support](https://microchipsupport.force.com/s/).

## Resources

Below is a list of the different resources that can be found in this organization:

**Documentation**

- [Documentation](https://github.com/Mi-V-Soft-RISC-V/miv-rv32-documentation): user guides and documentation for Mi-V soft CPUs

**Reference designs**

Note: all reference design repositories also provide pre-generated programming jobs.

- [Arrow Everest Board](https://github.com/Mi-V-Soft-RISC-V/Arrow-Everest-Board):
  scripts to generate an FPGA reference design and FlashPro Express job files for the Arrow Everest Board

- [Future Avalanche Board](https://github.com/Mi-V-Soft-RISC-V/Future-Avalanche-Board):
  scripts to generate an FPGA reference design and FlashPro Express job files for the Future Avalanche Board
  
- [PolarFire SoC Discovery Kit](https://mi-v-ecosystem.github.io/redirects/repo-discovery-kit-reference-design):
  scripts to generate a FPGA reference designs and FlashPro Express job files for the PolarFire SoC Discovery Kit.
  **Note:** These scripts are part of the PolarFire SoC GitHub organisation, they support generating the standard Mi-V RV32 reference designs based on the PolarFire Eval Kit and run the Mi-V RV32 [bare metal examples](https://mi-v-ecosystem.github.io/_redirects/mi-v-soft-risc-v/miv-rv32-bare-metal-examples)

- [PolarFire Eval Kit](https://github.com/Mi-V-Soft-RISC-V/PolarFire-Eval-Kit):
  scripts to generate an FPGA reference design and FlashPro Express job files for the PolarFire Eval Kit

- [PolarFire FPGA Splash Kit](https://github.com/Mi-V-Soft-RISC-V/PolarFire-FPGA-Splash-Kit):
  scripts to generate an FPGA reference design and FlashPro Express job files for the PolarFire FPGA Splash Kit

- [RTG4 Development Kit](https://github.com/Mi-V-Soft-RISC-V/RTG4-Development-Kit):
  scripts to generate an FPGA reference design and FlashPro Express job files for the RTG4 Development Kit

**Bare Metal Embedded Software**

- [Platform](https://github.com/Mi-V-Soft-RISC-V/platform): Hardware Abstraction Layer (HAL) and
  peripheral drivers for Mi-V Soft CPUs

- [Mi-V RV32 Bare Metal Examples](https://github.com/Mi-V-Soft-RISC-V/miv-rv32-bare-metal-examples):
  drivers and example projects for Mi-V Soft RISC-V CPUs and their associated peripherals
