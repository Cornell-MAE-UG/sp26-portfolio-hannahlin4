---
layout: project
title: Nutcracker-Design-continued
description: Design of a nutcracker with non-rigid handles (beams)
---
**Problem Statement and Objective:**\
Initially, the handles were considered in your design to be rigid. Now, assume the nutcracker handles are no longer rigid. In fact, they are now best described as beams which bend due to the combined action of the forces from the nut and from the actuator. Consider only the components of these forces transverse to your beam:\
a. Find the location of maximum elastic deflection in your handles. State your
assumptions clearly and describe your analysis.\
b. Choose a “beam” design (cross-section, material) such that the vertical elastic deflection is below 2% of its length and is the most mass-efficient possible.\
c. Present your final design in an image or drawing.\
**Constraints and Input Parameters**\
Force of the actuator: 222.18 kg*9.81 m/s^2=2179 N
Mechanical advantage: Lc/Ln= 2/17\
Force applied at the handle= 2179 N/2.17=1004 N\
Handle length=0.2 m\
Maximum deflection=0.2 m(0.02)=0.004 m\
Aluminum Material Properties\
**Approach to the Problem**\
Assumptions:
1. The handle is modeled as a cantilever beam fixed at the pivot point.\
2. The actuator force acts as a point load at the free end (where the user pushes).\
3. Only transverse forces are considered; axial forces are neglected.\
4. Material is homogeneous, isotropic, and follows Hooke’s law.\
5. Deflections are small (linear beam theory applies).\
For a cantilever with an end load, there is maximum deflection at the free end, or when x=L. Using the deflection formula δ_max = PL³/(3EI) and setting δ_max = 0.004 m, the required moment of inertia is I_req = PL³/(3E·0.004). Substituting aluminium properties gives I_req = 9.70×10⁻⁸ m⁴. For my design, I decided to use an I beam due to it being able to withstand high loads with high mass-efficiency. A simple I‑beam (25 mm wide, 42 mm tall, 5 mm web and flange thickness ) provides I = 1.80×10⁻⁷ m⁴ with a mass per length of 1.1 kg/m. I chose to use Aluminum because it is mass-efficient with a low density and high relative stiffness, especially compared to steel.\
Area A = 2Bt + (H-2t)t = 4.1 ×10⁻⁴ m². \
Moment of inertia: I = (B H³)/12 – (B-t)(H-2t)³/12 = 1.333×10⁻⁷ – 4.5×10⁻⁸ = 9.73×10⁻⁸ m⁴.\

**Diagram**\
<img width="558" height="546" alt="Screenshot 2026-05-03 at 2 00 19 AM" src="https://github.com/user-attachments/assets/dc313abf-4622-4417-b937-1fee80e024b5" />

**Discussion on Usability of Design**\
Aluminium makes the nutcracker lightweight and mass-efficient, while the 200 mm length is ergonomic for hand operation. There is slight cushioning from the beams, which may reduce shock from the nut cracking. The I-beam can be created in a factory easily, since it is very widely used. However, the shape might be an odd choice for a nutcracker. 
