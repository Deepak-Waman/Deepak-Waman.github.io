---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on the microphysical processes that control cloud structure, precipitation, and electrification. I combine high-resolution numerical modeling with observational datasets from field campaigns and satellite platforms.

---

## Secondary Ice Production

Ice in clouds forms through two pathways: primary nucleation on ice-nucleating particles (INPs), and secondary ice production (SIP) -- the multiplication of ice crystals through mechanical and thermodynamic fragmentation. SIP can increase ice number concentrations by several orders of magnitude beyond what primary nucleation alone can explain.

My work quantifies the contributions of rime splintering (Hallett-Mossop process), droplet shattering during freezing, and collisional fragmentation between ice particles. Using the AC bin-microphysics model (Phillips group, Lund University) and ICON at convective-permitting resolution, I have shown that SIP exerts a strong control on cloud top glaciation, updraft dynamics, and precipitation formation in tropical and mid-latitude deep convection.

---

## Ice Nucleation and Aerosol-Cloud Interactions

The efficiency of primary ice formation depends on the concentration and properties of INPs, which are sensitive to aerosol loading and composition. I study how INP concentration modulates the partitioning between liquid and ice in mixed-phase clouds, and how this feeds back into cloud microphysics and dynamics.

Within the WarmWorld project at KIT, I have implemented CAMS reanalysis aerosol data into the ICON-AES framework, enabling kilometer-scale global simulations with prognostic aerosol input to the two-moment microphysics scheme.

---

## Thunderstorm Electrification

Lightning is a manifestation of electrical charge separation in deep convective clouds. The dominant charging mechanisms are inductive (involving polarized particle collisions in the electric field) and non-inductive (charge exchange during ice-ice collisions in the presence of supercooled liquid water).

I am developing a self-consistent thunderstorm electrification scheme for ICON, including a Poisson solver for the 3D electric field and parameterizations of inductive and non-inductive charging. The scheme is validated against field campaign observations (LEE, DC3, ESCAPE, STEPS) and targets flash-rate climatology in global convective-permitting simulations.

---

## ICON Model Development

The ICOsahedral Nonhydrostatic (ICON) model is the operational weather and climate model of DWD and KIT. My ICON development contributions include:

- Two-moment microphysics sedimentation energy conservation (ICON-NWP, MR !2133)
- CAMS aerosol reader integration into ICON-AES
- Secondary ice production process implementations
- Thunderstorm electrification module (in development)

---

## Observational Datasets Used

- **EarthCARE CPR (CPR_CLP_2A)**: cloud profiling radar for reflectivity and vertical velocity validation
- **CAIPEEX, DCMEX, MC3E, ORCESTRA**: in situ microphysics and dynamical measurements
- **STEPS, DC3, LEE, ESCAPE**: field campaigns for thunderstorm electrification studies
