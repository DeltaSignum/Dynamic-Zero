# Glossary — Dynamic Zero Architectural Terminology

To avoid ambiguity, the terms used throughout the Dynamic Zero framework are defined as follows.

---

**+0 / −0 Reference Points**  
Dynamic kinetic equilibrium bounds representing the instantaneous diaphragm velocity turnover points at the transition of each half-cycle. Unlike a conventional static rest position, these points a[...]

---

**Phase-Zero Interval (PZI)**  
The semicycle between the +0 and −0 reference points where Delta Signum first appears. This interval marks the operational window in which the coupled pneumatic and mechanical system begins coherent energy reconstruction and phase-dependent momentum continuity.

---

**Dynamic Resonance (Fd)**  
The instantaneous, state-dependent operational resonance frequency of the coupled driver-air system, dynamically modulated by fluid momentum. The DZ architecture maintains Fd < Fin across all oper[...]

---

**Fd < Fin**  
The core operating condition of Dynamic Zero. The system's dynamic resonance (Fd) is kept continuously below the instantaneous input frequency (Fin), eliminating the static Fs cutoff boundary pres[...]

---

**Dynamic Mass Interchanger (DMI)**  
The primary acoustic interface chamber located directly behind the driver diaphragm. Designed to collect and guide the rear pressure wave into the active pneumatic network rather than dissipating [...]

---

**DM Impulser**  
An inertial fluidic port and cycle initiator governing momentum acceleration and energy transfer between half-cycles. Without the Impulser, coherent signal reconstruction across cycles is not poss[...]

---

**DM Container**  
A time-delay compliance volume that stores compression and rarefaction energy states across half-cycles. The Container holds past-cycle energy which, combined with the incoming signal, constructs [...]

---

**DM Delta Compensator**  
A differential phase accumulator designed to absorb timing mismatches, structural asymmetries, and fluid phase delays between past and present half-cycles. Under ideal operating conditions, the Co[...]

---

**Reciprocal Pneumatic Symmetry (RPS)**  
The theoretical design ideal of a DZ module in which pneumatic energy across both half-cycles becomes functionally equivalent, independent of signal amplitude or frequency.

---

**Inter-Cycle Momentum Continuity (ICMC)**  
The retention of air mass momentum between successive half-cycles within the pneumatic network, creating a continuous, time-dependent dynamic acoustic process.

---

**Module**  
The base functional unit of the DZ array architecture. Contains a single full-range transducer and the complete internal pneumatic network (DMI, DM Impulser, DM Container, DM Delta Compensator).

---

**Block**  
A paired assembly of two Modules establishing reciprocal pressure balance.

---

**Superblock**  
A 2×2 matrix of four Modules (two Blocks) providing phase stabilisation across multiple driver pairs. The first scaling level at which emergent low-frequency behaviour becomes measurable.

---

**Megablock**  
An extended N×N modular matrix. Theoretical scaling behaviour suggests progressive low-frequency extension and pressure increase with each hierarchical level. Empirical validation at this scale i[...]

---

**Reciprocal State Inversion**  
At the +0/−0 transition point, the stored pneumatic state reverses its functional role — from an effective inertial mass to an active pressure wave — coupling energy stored during the previo[...]

---

**T/S Incompatibility**  
Dynamic Zero is not compatible with conventional Thiele–Small modelling. T/S assumes a linear, time-invariant system with fixed parameters. DZ is a state-dependent, nonlinear system with pneumat[...]

---

**Fluid / Fluid Momentum**  
Throughout this documentation, "fluid" refers exclusively to air in motion. Dynamic Zero contains no liquids. All pneumatic coupling occurs through air mass dynamics within the internal chamber ne[...]

---

*For full theoretical framework see [docs/theory.md](theory.md).*  
*Delta Signum — [deltasignum.org](https://deltasignum.org)*
