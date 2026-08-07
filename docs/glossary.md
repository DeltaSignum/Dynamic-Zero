# Glossary — Dynamic Zero Architectural Terminology

To avoid ambiguity, the terms used throughout the Dynamic Zero framework are defined as follows.

---

**+0 / −0 Reference Points**  
Dynamic kinetic equilibrium bounds representing the instantaneous diaphragm velocity turnover points at the transition of each half-cycle. Unlike a conventional static rest position, these points are instantaneous velocity reversals within the coupled pneumatic-mechanical system.

---

**Phase-Zero Interval (PZI)**  
The semicycle between the +0 and −0 reference points where Delta Signum first appears. This interval marks the operational window in which the coupled pneumatic and mechanical system begins coherent energy reconstruction and phase-dependent momentum continuity.

---

**Dynamic Resonance (Fd)**  
The instantaneous, state-dependent operational resonance frequency of the coupled driver-air system, dynamically modulated by fluid momentum. The DZ architecture maintains Fd < Fin across all operating conditions.

---

**Fd < Fin**  
The core operating condition of Dynamic Zero. The system's dynamic resonance (Fd) is kept continuously below the instantaneous input frequency (Fin), eliminating the static Fs cutoff boundary present in conventional loudspeaker design.

---

**Dynamic Mass Interchanger (DMI)**  
The primary acoustic interface chamber located directly behind the driver diaphragm. Designed to collect and guide the rear pressure wave into the active pneumatic network rather than dissipating it as passive loss.

---

**DM Impulser**  
An inertial fluidic port and cycle initiator governing momentum acceleration and energy transfer between half-cycles. Without the Impulser, coherent signal reconstruction across cycles is not possible.

---

**DM Container**  
A time-delay compliance volume that stores compression and rarefaction energy states across half-cycles. The Container holds past-cycle energy which, combined with the incoming signal, constructs Inter-Cycle Momentum Continuity.

---

**DM Delta Compensator**  
A differential phase accumulator designed to absorb timing mismatches, structural asymmetries, and fluid phase delays between past and present half-cycles. Under ideal operating conditions, the Compensator maintains reciprocal pneumatic symmetry.

---

**Reciprocal Pneumatic Symmetry (RPS)**  
The theoretical design ideal of a DZ module in which pneumatic energy across both half-cycles becomes functionally equivalent, independent of signal amplitude or frequency.

---

**Inter-Cycle Momentum Continuity (ICMC)**  
The retention of air mass momentum between successive half-cycles within the pneumatic network, creating a continuous, time-dependent dynamic acoustic process.

---

**Module**  
The base functional unit of the DZ array architecture. Contains a single full-range transducer and the complete internal pneumatic network (DMI, DM Impulser, DM Container, DM Delta Compensator). Represents the fundamental quantised unit from which all larger assemblies are constructed.

---

**Quantisation Level**  
The hierarchical architectural principle in which each assembly class (Block, Superblock, Megablock, etc.) represents a discrete quantised scaling level. All assemblies at the same quantisation level share identical topological and pneumatic principles, regardless of module count.

---

**Block N**  
A DZ quantisation level containing N modules in a paired reciprocal arrangement. The numeric designation indicates total module count (e.g., Block 2 = 2 Modules; Block 4 = 4 Modules in 2×2 configuration). All Block-level assemblies maintain the same quantisation principle and reciprocal pressure balance architecture.

---

**Superblock N**  
A quantisation level above Block, constructed from smaller assemblies in hierarchical array. Superblock 8 (8 Modules) represents the first scaling level at which emergent low-frequency behaviour becomes measurable and stable. Superblock 16 (16 Modules in 4×4 configuration) demonstrates progressive low-frequency extension and increased pressure output.

---

**Megablock 64**  
An 8×8 modular matrix containing 64 Modules total. Extended hierarchical scaling demonstrating theoretical predictions of progressive low-frequency extension and pressure increase. Empirical validation at this scale shows sustained stability and predictable scaling behaviour across frequency range.

---

**Hierarchical Scaling Principle**  
The recursive modular architecture: Module → Block 2 → Block 4 → Superblock 8 → Superblock 16 → Megablock 64 → N (theoretically unbounded). Each quantisation level applies identical architectural principles at increasing acoustic scale. System behaviour becomes progressively more stable and the effective low-frequency boundary progressively lower with each hierarchical step.

---

**Reciprocal State Inversion**  
At the +0/−0 transition point, the stored pneumatic state reverses its functional role — from an effective inertial mass to an active pressure wave — coupling energy stored during the previous half-cycle into the present half-cycle.

---

**T/S Incompatibility**  
Dynamic Zero is not compatible with conventional Thiele–Small modelling. T/S assumes a linear, time-invariant system with fixed parameters. DZ is a state-dependent, nonlinear system with pneumatic memory and inter-cycle momentum continuity.

---

**Fluid / Fluid Momentum**  
Throughout this documentation, "fluid" refers exclusively to air in motion. Dynamic Zero contains no liquids. All pneumatic coupling occurs through air mass dynamics within the internal chamber network.

---

*For full theoretical framework see [docs/theory.md](theory.md).*  
*For hierarchical architecture see [docs/architecture.md](architecture.md).*  
*Delta Signum — [deltasignum.org](https://deltasignum.org)*
