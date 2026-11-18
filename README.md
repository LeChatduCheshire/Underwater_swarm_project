# Underwater Swarm Project

An academic project exploring the design of a small underwater robot platform for swarm applications. This repository currently brings together the vehicle's mechanical and electronics design files, component and cost research, and background literature. The CAD and technical drawings include work-in-progress material.

![Modular underwater ROV concept](figures/underactuated_rov_cad.png)

## Repository map

- [`hardware/CAD/`](hardware/CAD/) — vehicle assembly and component CAD source files.
- [`hardware/3D print files/`](hardware/3D%20print%20files/) — exported STL parts for printing.
- [`hardware/electronics/`](hardware/electronics/) — electronics architecture diagram and source file.
- [`hardware/technical documentation/`](hardware/technical%20documentation/) — assembly manual, technical drawings, BOMs, design comparison, and component references.
- [`hardware/ressources/`](hardware/ressources/) — supporting enclosure files and the upstream modular ROV model submodule.
- [`deliverables/2026.10.29_Paper_Charlie/`](deliverables/2026.10.29_Paper_Charlie/) — project paper, source files, and annexes.
- [`litterature review/`](litterature%20review/) — research papers, proposal, and video references.
- [`figures/`](figures/) — images used in this README.
## Design snapshots

| Assembly drawing | Electronics architecture |
| --- | --- |
| ![Vehicle assembly drawing, version 1.0](figures/assembly_drawing_v1.0.png) | ![Underactuated ROV electronics diagram](figures/electronics_diagram.png) |

The assembly drawing is version 1.0 and was rendered from the PDF in the technical drawings folder. The CAD rendering is marked work in progress; consult the source CAD for the current design state. The electronics diagram is an architecture reference.

## Getting the files

Clone the repository and initialize its ROV model submodule to retrieve the upstream model files:

```bash
git clone --recurse-submodules <repository-url>
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

CAD source files are provided in the formats present in their respective folders (including Autodesk Inventor files, STEP/IGES models, and printable files where available). Refer to each folder's documentation for format-specific details. No software build or simulation entry point is currently documented in this repository.
