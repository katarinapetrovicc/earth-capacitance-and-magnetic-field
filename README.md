# Earth Capacitance and Magnetic Field

## Overview

This repository contains COMSOL Multiphysics models developed as part of a project assignment in Computational Electromagnetics.

The project focuses on the numerical modeling of the Earth's electromagnetic environment through three simulation models.

---

## 1. Earth–Ionosphere Capacitance Model

The Earth and the ionosphere are modeled as two concentric conducting spheres, forming a spherical capacitor.

The simulation includes:

- Electric potential distribution
- Electric field distribution
- Electric field lines
- Maxwell capacitance calculation

**Model file:** `kapacitivostZemlje.mph`

---

## 2. Earth–Ionosphere Current Density Model

This model analyzes the distribution of electric current density in the atmosphere between the Earth and the ionosphere.

The simulation includes:

- Electric current density distribution
- Current flow direction
- Current density magnitude

**Model file:** `struje_Zemlja_Jonosfera.mph`

---

## 3. Earth's Magnetic Field Model

The Earth's magnetic field is modeled using a magnetic point dipole located at the Earth's center.

The simulation includes:

- Magnetic flux density distribution
- Magnetic field lines
- Magnetic field intensity at the equator and the poles
- Comparison of numerical and theoretical results

**Model file:** `magpoljeZemlje.mph`

---

## Software and Physics Interfaces

- COMSOL Multiphysics 5.4
- AC/DC Module

The following physics interfaces were used:

- **Electrostatics (es)** – for modeling the Earth–ionosphere capacitance, electric potential, and electric field distribution.
- **Electric Currents (ec)** – for analyzing the electric current density between the Earth and the ionosphere.
- **Magnetic Fields (mf)** – for modeling the Earth's magnetic field using a magnetic point dipole.

---

## Repository Contents

- COMSOL simulation models (`.mph`)
- Numerical models of the Earth–ionosphere capacitance
- Electric current density analysis
- Earth's magnetic field simulation

---

## Objectives

The main objectives of this project are:

- Model the Earth–ionosphere system as a spherical capacitor.
- Analyze electric potential and electric field distribution.
- Investigate electric current density between the Earth and the ionosphere.
- Simulate the Earth's magnetic field using a magnetic dipole approximation.
- Compare numerical simulation results with theoretical values.
