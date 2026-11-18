# Axisbench Studio

**Hardware design through repeatable, documented workflows: parametric CAD, KiCad PCB layout, CFD/FEA simulation and scripted renders.** AI tooling speeds up the routine steps; the engineering calls and the checking stay with us.

## What we work on

- **PCB design, schematic to layout.** An ESP32 push-to-talk radio in KiCad 10: schematic, footprint and library cleanup, two-sided placement, routing, then a split into stacked main and power boards.
- **Simulation with stated limits.** FEA with CalculiX and gmsh, rigid-body dynamics in MuJoCo, GPU CFD with FluidX3D. Concept-study results are labelled as simulation, not test data.
- **Engineering toolchains.** MCP servers and launcher scripts that connect an AI agent to CAD, PCB, simulation and rendering tools on Windows + WSL.
- **Workflows that keep long projects traceable.** Stage plans, decision gates, written handoffs between sessions, and evidence labels.

## How we work

- **Decision gates.** A stage closes when its check passes, for example a design-rule check or a review round.
- **Evidence labels.** In the MYRIAD concept study, claims are tagged `[FACT]` (sourced, calculated or simulated) or `[EXTRAPOLATION]` (reasoned beyond the evidence), and its simulations are marked "simulation, not test-validated".
- **Honest status.** Every project says what stage it reached. The radio board is a design only: not fabricated, ordered or built.

## Case studies

- **[ESP32 Push-to-Talk Radio: Two-Board PCB Design](https://www.behance.net/gallery/258693621/ESP32-Push-to-Talk-Radio-Two-Board-PCB-Design)**: a staged KiCad layout, made over nine working sessions. Design stage only; DRC clean at the last session.
- **[Project MYRIAD: A Muscle-Fibre Arm, Worked as Theory](https://www.behance.net/gallery/258694051/Project-MYRIAD-A-Muscle-Fibre-Arm-Worked-as-Theory)**: a 16-stage roadmap, actuation models and simulations for a speculative robotic arm. A concept study, not hardware.

Source repositories for these will be added here as they are cleaned and ready.

## Tools

KiCad 10 · FreeCAD · Blender · CalculiX · gmsh · MuJoCo · FluidX3D · Python · matplotlib · Docker · WSL · Claude Code · MCP

## Contact

Via Behance: [behance.net/axisbench](https://www.behance.net/axisbench)
