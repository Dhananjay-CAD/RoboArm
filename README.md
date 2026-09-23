<h1 align="center">RoboArm</h1>
<p align="center">A multi-DOF robotic arm — fully modeled in SolidWorks, from concept to engineering drawings.</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-in--progress-yellow" alt="status">
  <img src="https://img.shields.io/badge/CAD-SolidWorks-red" alt="cad">
</p>

<p align="center">
  <a href="https://vimeo.com/1144080727?fl=pl&fe=cm">
    <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_3840_webp/1adde8235112197.6933e5e7e69ec.jpg" width="20%">
  </a>
</p>

---

## Overview

This repository contains the full CAD design of a robotic arm — individual part files, assemblies, and engineering drawings. It's part of an ongoing series of mechanical design projects; see [Related Projects](#related-projects) below.

<p align="center">
  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/3d4e0b235112197.6933ddd648c50.gif" width="500" alt="RoboArm motion demo">
</p>

## Related Projects

This RoboArm design uses actuator concepts developed in these companion repositories:

| Project | Description | Link |
|---------|-------------|------|
| Harmonic Actuator | Harmonic drive actuator CAD design | [Harmonic_Actuator →](https://github.com/Dhananjay-CAD/Harmonic_Actuator) |
| Cycloidal Actuator | Cycloidal drive actuator CAD design | [cycloidal_actuator →](https://github.com/Dhananjay-CAD/cycloidal_actuator) |

On GitHub.com, click the blue links to open each repo. On mobile or other viewers, copy the URL into your browser's address bar.


## Features

- Multi-DOF robotic arm mechanical design
- Modular joint design for easy assembly/disassembly
- Fully parametric SolidWorks model
- STEP/STL exports for use in other CAD tools or 3D printing

## Repository Structure

<details>
<summary>Click to expand</summary>

```
RoboArm/
├── CAD/
│   ├── Parts/          # Individual component files (.SLDPRT)
│   ├── Assemblies/     # Full and sub-assemblies (.SLDASM)
│   └── Drawings/       # Engineering drawings (.SLDDRW)
├── STEP_STL/           # Neutral formats for other CAD software / 3D printing
├── Drawings_PDF/        # PDF versions of drawings for quick viewing
└── Images/              # Renders and screenshots
```

</details>

## Specifications

| Parameter          | Value            |
|---------------------|-----------------|
| Degrees of Freedom  | TBD              |
| Reach               | TBD              |
| Payload             | TBD              |
| Material            | TBD              |
| Software Used       | SolidWorks 2025  |

## How to Use

1. Clone or download this repository.
2. Open the assembly file in `CAD/Assemblies/` using SolidWorks (or a compatible version).
3. No SolidWorks? View the `.STEP` files in `STEP_STL/` using a free viewer like FreeCAD or eDrawings Viewer.
4. Drawings are available as PDFs in `Drawings_PDF/` for quick reference without CAD software.

## Tools & Software

- SolidWorks 2025

## Future Work

- [ ] Add motor/actuator selection
- [ ] Add motion simulation
- [ ] Add BOM (Bill of Materials)
- [ ] 3D print and test prototype

## Author

**Dhananjay** — [GitHub Profile](https://github.com/Dhananjay-CAD)
