# Optimal_Operational_Scheduling_of_a_Grid_Connected_System_Based_on_DSM

## 📘 Overview

This repository contains the models, code, and documentation for the project **"Optimal Operational Scheduling of a Grid-Connected System Based on Demand Side Management (DSM)"**. The main goal of this project is to develop and implement an **optimization-based energy scheduling framework** that enables smart and cost-effective operation of a grid-connected system by applying **Demand Side Management (DSM)** techniques.

With the increasing penetration of **renewable energy sources**, especially **solar PV**, and the growing demand for **smart energy usage**, it becomes essential to design intelligent control and scheduling algorithms that can balance **supply and demand** effectively while ensuring **grid stability** and **economic efficiency**.

---

## ⚡ What is Demand Side Management (DSM)?

**Demand Side Management (DSM)** refers to a group of strategies and technologies used to optimize consumer energy consumption patterns. It is a key component of **smart grid** infrastructure and aims to:

- Reduce peak energy demand.
- Shift load to off-peak periods (load shifting).
- Encourage energy usage when renewable generation is high.
- Lower electricity bills using real-time pricing or Time-of-Use (ToU) tariffs.
- Increase system flexibility and reliability.

DSM techniques empower consumers to become active participants in energy systems, which supports better integration of distributed energy resources (DERs) such as rooftop solar and energy storage systems.

---

## 🔍 Project Objectives

- ✅ Design an **optimal energy scheduling** algorithm using DSM strategies.
- ✅ Minimize electricity cost for end-users based on ToU tariffs.
- ✅ Maximize self-consumption of local renewable generation (e.g., PV).
- ✅ Reduce dependency on the utility grid during peak hours.
- ✅ Improve the reliability and operational efficiency of the grid-connected system.
- ✅ Enable **real-time demand response (DR)** integration.

---

## 🏗️ System Architecture

The system model includes the following components:

- **Grid-Connected PV System**: Provides renewable energy during sunlight hours.
- **Energy Storage System (ESS)**: Stores excess PV generation and discharges during peak demand.
- **Flexible Loads**: Non-critical loads that can be scheduled, curtailed, or shifted.
- **Grid Utility**: Supplies electricity when local generation is insufficient.
- **DSM Controller**: Optimization unit that schedules load and storage based on pricing and availability.

---

## 🧮 Methodology

1. **Modeling of Energy System**:
   - Power balance equations
   - Load demand profiles
   - PV generation forecast
   - Storage capacity and constraints

2. **DSM Strategy Implementation**:
   - Load classification (critical vs. flexible)
   - Load shifting, peak shaving, valley filling
   - Integration of Time-of-Use (ToU) pricing or Real-Time Pricing (RTP)

3. **Optimization Algorithm**:
   - Objective: Minimize total electricity cost over a scheduling horizon
   - Constraints:
     - Energy balance at each time step
     - Load operation time windows
     - Battery state-of-charge limits
   - Algorithms: Linear Programming (LP), Mixed Integer LP (MILP), or Heuristic algorithms

4. **Simulation Tools**:
   - MATLAB / Simulink
   - Python (Pyomo, SciPy, or custom solver)
   - PLECS (for power electronics simulation if needed)

---

## 🧪 Example Use Cases

- 📈 **Residential DSM**: Scheduling appliances like washing machines, electric vehicles (EVs), and air conditioning based on ToU tariffs.
- 🏢 **Commercial Buildings**: HVAC systems and lighting control using occupancy and pricing signals.
- 🏭 **Industrial Loads**: Process scheduling with high energy savings potential.
- 🏘️ **Microgrid Communities**: Coordinated DSM in grid-connected solar communities.

---

