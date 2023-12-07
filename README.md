# opw_bloodflow_gen2_hw
Openwater Blood Flow Gen 2 Hardware

![system](https://github.com/OpenwaterInternet/opw_bloodflow_gen2_hw/assets/128628160/eda21643-f991-4cbd-9b0f-b8796700e434)

Openwater Gen 2 Blood Flow System hardware designs are detailed in this repository. 

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

Before getting started with the design data included in this repo, you may want to visit the Gen 2 Blood Flow Hardware Wiki for some background information on the system and its design. You may also want to review the See the [Openwater Blood Flow Gen 2 Software](link) and [Openwater Blood Flow Gen 2 Analysis](link) repos for additional information about the system and its operation. 

### Prerequisites

Required software will depend on the type of data desired by the user. In general, we have tried to include generic formats, viewable with free tools, wherever possible. Data in proprietary formats such as SolidWorks and Altium native are provided for the convenience of users with access to those tools.  

Several file types commonly used include
- STEP assembly files and SolidWorks native files for mechanical assemblies
- PDFs of assembly and component drawings, electrical schematics, datasheets, and documentation
- Gerber files for printed circuit designs
- Altium design files for circuit designs and layouts
- DXF and STL files for individual mechanical components

### Repository Contents
[Mechanical design files](mechanical), which include
- [Major subsystems](mechanical/major_subsystems)
- Additional design files for various components and subassemblies in various formats ([PDF](mechanical/pdf), [STL](mechanical/stl), [DXF](mechanical/dxf))

[Electrical design files](electrical), which includes printed circuit board assemblies and harnessing

[System design](system_design) files which include high-level documents describing the design of the blood flow system

[Assembly and Test](assembly_and_test) which includes various documents detailing contruction of various device subsystems

## Contributing

We welcome contributions from the community. If you have ideas for improvements or find any issues, please open an issue or submit a pull request.

Before contributing, please read our [Contributing Guidelines](contributing.md).

## License

This project is licensed under the AGPLv3 License - see the [license](LICENSE.md) file for details.
