# uav-wing-spar-fea-ansys-apdl
FEA of UAV wing spar using ANSYS APDL (BEAM188). Analysis under point load, torsion, &amp; distributed aerodynamic loads. Compares theoretical calculations with FEA for displacement, rotation & stress. Assesses against material yield/ultimate strength.
# FEA of UAV Wing Spar using ANSYS APDL (ASDA Assignment)

## Project Overview
This repository contains my 2024-25 ASDA (Aerospace Structural Design and Analysis) FEA Assignment from the University of Hertfordshire. The project focuses on evaluating the structural performance of a UAV's wing spar (hollow rectangular aluminium alloy section) under various defined loading conditions using ANSYS APDL.

The core objective was to compare FEA results with theoretical calculations to validate the FE model and understand the spar's structural behaviour.

## Analyses Performed:
1.  **Point Load Analysis:**
    *   Deflection calculation under a 1000N point load at x=2.0m.
    *   Comparison of ANSYS APDL (BEAM188 element) deflection results with theoretical beam theory.
2.  **Torsional Moment Analysis:**
    *   Torsional rotation calculation under a 30Nm moment at x=2.0m.
    *   Comparison of ANSYS APDL rotational displacement with theoretical torsion equations (using calculated torsional constant K).
3.  **Distributed Aerodynamic Load Analysis:**
    *   Application of a distributed load along the spar (quarter chord).
    *   FEA to determine maximum tensile stress (Von Mises).
    *   Assessment of structural integrity against material yield (300 MPa) and ultimate tensile strength (340 MPa) using proof (1.25) and ultimate (1.50) safety factors.
    *   Analysis of tip displacement (Uz) and rotation (ROTy, ROTx).

## Key Concepts & Skills Demonstrated:
*   **Finite Element Analysis (FEA):** Proficiency with ANSYS APDL for structural analysis.
*   **Beam Element Modelling:** Utilisation of 2-node BEAM188 elements.
*   **Structural Mechanics:** Application of beam theory for bending and torsion.
*   **Load Application:** Modelling point loads, torsional moments, and distributed loads in FEA.
*   **Boundary Conditions:** Applying fixed constraints to represent root attachment.
*   **Results Interpretation:** Analyzing displacements, rotations, and Von Mises stresses.
*   **Validation & Comparison:** Comparing FEA results with theoretical predictions.
*   **Safety Factor Analysis:** Assessing structural integrity against material limits.
*   **Technical Reporting.**

## Repository Contents:
*   `ASDA_FEA_Assignment_Report.pdf`: The full assignment report detailing methodology, theoretical calculations, ANSYS APDL setup, results, comparisons, and conclusions.

## Software Used:
*   ANSYS APDL (for FEA simulation)*   [Microsoft Excel/MATLAB - if used for theoretical calculations or plotting]
---
This assignment provided practical experience in using ANSYS APDL for detailed structural analysis of an aerospace component and validating FEA models against theoretical principles.
