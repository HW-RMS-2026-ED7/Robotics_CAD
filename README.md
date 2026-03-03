# Robot Mechanical Systems - CAD Project

## Overview
This repository contains the Computer-Aided Design (CAD) files for the Robot Mechanical Systems group project. All designs are created using **Autodesk Inventor** and organized hierarchically to represent the complete robot assembly.

## Alternate Hosting
Files available on grabcad too ![HERE](https://grabcad.com/library/spool-style-pick-and-place-robot-1)


## Required Software
- **Autodesk Inventor** (2026)

## Project Structure

### Root Directory
- **`main.iam`** - Main assembly file containing the complete robot assembly

### Assembly Hierarchy
```
main.iam (Main Assembly)
├── parts/
│   ├── base.ipt
│   ├── MOTOR_MOUNT_.ipt
│   ├── SIDE_BEAMS.ipt
│   ├── spool.ipt
│   ├── motor_imported_Simplify_1.ipt
│   └── motor_imported.iam
├── sub_assemblies/
│   ├── beam_sub_asssem.iam
│   ├── motor_mount_sub_assem.iam
│   └── motor_spool_sub_assem.iam
└── deprec/ (deprecated components - archived)
```

## File Naming Conventions
- **`.ipt`** - Inventor Part file (individual components)
- **`.iam`** - Inventor Assembly file (grouped components)
- **`.ipj`** - Inventor Project file (project configuration)
- **`.stp`** - STEP format (universal CAD format for exchange)
- **`.3mf`** - 3D print format
- **`.gcode`** - CNC/3D printer toolpath

## Version Control
- The `OldVersions/` directories maintain historical records of designs
- The `deprec/` folder contains superseded components
- Use Inventor's native versioning system for active development


---
**Last Updated**: March 2026  
**Project**: HW-RMS-2026-ED7 Robotics CAD
