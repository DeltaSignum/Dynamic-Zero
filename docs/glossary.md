# Glossary — Dynamic Zero Architectural Terminology

To avoid ambiguity, the terms used throughout the Dynamic Zero framework are defined as follows.

---

**+0 / −0 Reference Points**  
Dynamic kinetic equilibrium bounds representing the instantaneous diaphragm velocity turnover points at the transition of each half-cycle. Unlike a conventional static rest position, these points are instantaneous velocity reversals within the coupled pneumatic-mechanical system.

---

**Phase-Zero Interval (PZI)**  
The semicycle between the +0 and −0 reference points where Delta Signum first appears. This interval marks the operational window in which the coupled pneumatic and mechanical system begins coherent energy reconstruction and phase-dependent momentum continuity.

---

**Dynamic Reference Frequency (Fd)**  
The instantaneous, state-dependent effective frequency of the coupled driver-air system, maintained below the excitation frequency (Fd < Fin).

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
