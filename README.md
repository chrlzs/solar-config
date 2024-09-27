# Solar Config

This repository contains diagrams and scripts for monitoring, managing, and reporting on my solar array and battery system setup. It serves as a single source of truth for my solar power system, including hardware inventory, performance data, and custom scripts for automation and insights.

## Overview

The **Solar Config** repository is structured to document and manage:
- **Mermaid Diagrams**: Visual representations of the solar array, battery array, and hardware components.
- **Monitoring Scripts**: Scripts to track performance metrics such as power generation, battery levels, and overall system health.
- **Hardware Inventory**: Detailed inventory of all the components in the solar setup, including panels, inverters, batteries, and more.

## Repository Structure

```
solar-config/
├── diagrams/
│   └── solar_array.mmd         # Diagram of the solar array
│   └── battery_array.mmd       # Diagram of the battery array
├── scripts/
│   └── monitoring.sh           # Monitoring script to track power generation
├── inventory/
│   └── hardware_list.txt       # Inventory of all hardware used in the system
└── README.md                   # Project documentation
```

## Getting Started

1. **Diagrams**: All diagrams are created using [Mermaid](https://mermaid-js.github.io/mermaid/). To view them, you can render the `.mmd` files using a Markdown viewer that supports Mermaid, or convert them to other formats as needed.
   
2. **Monitoring**: The scripts provided in the `scripts/` directory can be used to automate the monitoring of system performance. You may need to customize them to match your specific hardware and environment.

3. **Hardware Inventory**: The inventory provides a list of all components in use. Feel free to update it as your system evolves.