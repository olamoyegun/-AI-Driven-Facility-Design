# AI-Driven Refinery Design Transformation Using PML Macros

## Overview

This project demonstrates how Generative AI can support oil and gas facility redesign by preserving engineering expertise from existing 3D models.

The proof-of-concept focuses on exporting PML macros from an existing mechanical equipment model with connected piping, then using AI to generate a modified design based on an engineering prompt.

The long-term vision is to scale this approach from a single equipment case study to full refinery redesign, modular facility replication, brownfield upgrades, and digital twin-ready engineering transformation.

## Core Idea

Existing refinery and oil and gas facility designs contain valuable engineering knowledge. Much of this knowledge is embedded in 3D models, PML macros, naming conventions, equipment layouts, pipe routing decisions, and experienced engineers' design choices.

This project explores how AI can capture and reuse that knowledge by:

1. Exporting design logic from 3D as PML macros
2. Interpreting the geometry, connectivity, and metadata
3. Applying prompt-driven engineering transformations
4. Generating revised PML macros for review and re-import
5. Validating outputs against engineering rules and naming standards

## Proof-of-Concept Case Study

The first case study focuses on a mechanical equipment item with connected piping.

### Example Prompt

> Increase the size of the equipment by 1.5 while maintaining proportion, preserving location and orientation, retaining connected piping relationships, and creating a unique equipment name based on the project naming convention.

### Expected Output

- Scaled equipment geometry
- Preserved location and orientation
- Retained pipe/nozzle relationships
- New compliant equipment name
- Revised PML macro
- Engineering validation report

## Strategic Vision

The initial equipment scaling test is a building block for a larger refinery redesign platform.

Future capability areas include:

- Multi-equipment package redesign
- Process unit scaling
- Modular facility replication
- Brownfield refinery upgrades
- Capacity expansion scenarios
- AI-assisted digital twin readiness
- Integration with AVEVA, Hexagon, and Autodesk ecosystems

## Target Users

- Oil and gas operators
- Refineries and petrochemical companies
- EPC contractors
- Mechanical engineers
- Piping engineers
- Digital engineering teams
- Asset integrity and digital twin teams
- National oil companies and infrastructure agencies

## Repository Structure

```text
docs/               Concept notes and use case documentation
case-study/         Proof-of-concept equipment scaling case
pml-macros/         Example original and AI-generated PML macro placeholders
prompts/            AI prompt examples
validation-rules/   Naming, geometry, and connectivity validation logic
architecture/       System architecture and workflow notes
sample-data/        Example equipment and tag data
```

## Development Roadmap

See [roadmap.md](roadmap.md).

## Status

This is an early-stage concept and prototype repository intended to support:

- Technical demonstration
- Funding conversations
- Partner engagement
- Pilot project development
- Thought leadership in AI-driven facility design

## Disclaimer

This repository is a conceptual and prototype project. Any generated engineering output must be reviewed, validated, and approved by qualified engineers before use in real projects.
