# Glossary — Dynamic Zero Architectural Terminology

> **Note:** DZ-specific terminology is used only where conventional terminology does not adequately describe the intended architectural function. As the theoretical model develops, project-specific terms may be simplified, consolidated, or removed where standard physical descriptions are sufficient.

To avoid ambiguity, the terms used throughout the Dynamic Zero framework are defined as follows.

---

**+0 / −0 Reference Points**  
The instantaneous diaphragm velocity-turnover states (v = 0) at the transition between successive half-cycles. These are not diaphragm displacement zero-crossings (x = 0).

---

**Phase-Zero Interval (PZI)**  
The transition interval between successive +0 and −0 reference states during which pneumatic-mechanical continuity is maintained across the half-cycle transition. Conceptually, PZI defines the operating region intended to avoid a discontinuous or inactive transition between successive dynamic states.

---

**Dynamic Mass Interchanger (DMI)**  
The primary pneumatic exchange interface directly behind the driver diaphragm, through which diaphragm motion alternately transfers air-mass momentum into and receives pneumatic loading from the internal DZ network.

---

**DM Impulser**  
The inertial pneumatic element coupling the DMI to the DM Container. It governs the acceleration and transfer of moving air mass and provides the reciprocal coupling between pressure-wave energy and inertial air-mass motion.

---

**DM Container**  
The pneumatic volume in which pressure distribution and air-mass momentum inherited from preceding half-cycles form part of the initial state for subsequent system motion.

---

**DM Delta Compensator (DMDC)**  
The pneumatic element that compensates for differences between the inherited pneumatic state and the requirements of the new half-cycle. It also provides controlled bidirectional mass exchange when the internal pneumatic state alone cannot satisfy that difference.

---

**Inter-Cycle Momentum Continuity (ICMC)**  
The persistence of air-mass momentum and pneumatic state between successive half-cycles. Each new half-cycle therefore begins from the physical state inherited from preceding motion rather than from an independently reset state.

---

**Fluid / Fluid Momentum**  
Throughout this documentation, "fluid" refers exclusively to air in motion. Dynamic Zero contains no liquids. "Fluid momentum" refers to the momentum of moving air mass within the pneumatic network.

---

*For the full theoretical framework see [docs/theory.md](theory.md).*  
*For hierarchical architecture see [docs/architecture.md](architecture.md).*  
*Delta Signum — [deltasignum.org](https://deltasignum.org)*
