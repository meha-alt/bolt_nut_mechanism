# Bolt-Nut Mechanism & Motion Simulation

A parametric bolt-nut assembly designed and simulated in **PTC Creo Parametric**, including external and internal helical threads and dynamic motion analysis.

## Project Overview

This project covers the complete workflow from individual component modeling to assembly and mechanism simulation.

### Bolt

* Parametric bolt head and shank design
* Chamfered edges
* External thread created using **Helical Sweep**

### Nut

* Parametric nut geometry
* Internal thread created using **Helical Sweep**
* Thread clearance incorporated for assembly

### Assembly

* Bolt and nut assembled using a **Dynamic Cylinder constraint**
* Allows coupled rotational and translational movement

### Mechanism & Animation

* **Gear Connection** used to couple rotation and translation
* **Servo Motor** applied to drive the mechanism
* **Mechanism Analysis** performed to simulate thread engagement
* Animation generated to visualize the motion

## Creo Features Used

* Extrude
* Revolve
* Chamfer
* Helical Sweep
* Dynamic Cylinder
* Gear Connection
* Servo Motor
* Mechanism Analysis

## Repository Structure

* `Bolt/` — Bolt modeling files
* `Nut/` — Nut modeling files
* `Assembly/` — Assembly and constraint files
* `Animation/` — Mechanism simulation/animation

## Tools

**Software:** PTC Creo Parametric
**Domain:** CAD / Mechanical Design / Mechanism Simulation

## Preview

<img width="790" height="690" alt="image" src="https://github.com/user-attachments/assets/7f7e037d-e564-482d-9c5c-3f440be38f16" />

## Outcome

Successfully modeled a threaded bolt-nut pair, assembled the components, and simulated their rotational and translational motion to demonstrate realistic thread engagement.
