# R7026R Spacecraft Control

Aim of the course: assess and report on the feasibility of different attitude control systems in different situations. Study period 2, autumn 2026 (2 Nov – 11 Dec). Books: FPE = Franklin, Powell and Emami-Naeini, *Feedback Control of Dynamic Systems*; Sidi = *Spacecraft Dynamics and Control* (study guide: [[StudyGuide.pdf]]).

## Lectures
**Part 1: introduction**
- [[R7026R L1]] – Review of classical control

**Part 2: control theory**
- [[R7026R L2]] – State-space models and stability
- [[R7026R L3]] – Controllability and observability
- [[R7026R L4]] – State feedback and LQR
- [[R7026R L5]] – Observers, compensators, going digital
- [[R7026R L6]] – Disturbance and noise models
- [[R7026R L7]] – Kalman filter and LQG

**Part 3: the spacecraft**
- [[R7026R L8]] – Attitude kinematics
- [[R7026R L9]] – Attitude dynamics and gravity-gradient stability
- [[R7026R L10]] – Sensors, actuators and attitude determination
- [[R7026R L11]] – Gravity-gradient response and damping
- [[R7026R L12]] – Spin and dual-spin stabilization
- [[R7026R L13]] – Reaction and momentum wheels
- [[R7026R L14]] – Choosing an attitude control system (incl. what to be able to compute for the exam)

**Optional (if given)**
- [[R7026R E1]] – Magnetic attitude control and time-optimal maneuvers
- [[R7026R E2]] – Momentum bias in depth and pointing accuracy

## Problem sessions
Ten problems each; ⋆ = solved together in class. By hand like the exam, unless marked (MATLAB).
- [[ProblemSession_1.pdf|Problem Session 1]] – Lectures 2–5: ⋆3 controllable/observable directions, ⋆5 observable canonical form, ⋆7 pole placement and LQ for a double integrator, ⋆8 observing a GEO station-keeping satellite
- [[ProblemSession_2.pdf|Problem Session 2]] – Lectures 6–10: ⋆3 position or velocity sensor, ⋆4 LQG of an unstable first-order system, ⋆6 Euler angles and the quaternion, ⋆8 linearized attitude equations
- [[ProblemSession_3.pdf|Problem Session 3]] – Lectures 11–14: ⋆2 GG satellite with magnetic damping, ⋆6 fuel for active nutation control, ⋆7 momentum bias with roll-only sensing, ⋆8 position-plus-rate pitch control

## Projects
- [[Project_1.pdf|Project 1]] – Active nutation damping with a Kalman filter and LQG (individual). Start after L4; 4-page IEEE paper + one zip with MATLAB/Simulink files (one script reproduces every figure). See [[R7026R L12]] (active wheel damper) and [[R7026R L7]].
- [[Project_2.pdf|Project 2]] – Attitude dynamics by hand (individual): principal axes, energy and stable spin, spin stabilized by a rotor, gravity-gradient pitch. Start after L9; some parts need L11–L12. One PDF via Canvas.

## Key dates
- Project 1: start after Lecture 4
- Project 2: start after Lecture 9
- Exam: week of 11–15 Jan 2027 (written, by hand, small models; checklist in [[R7026R L14]])
