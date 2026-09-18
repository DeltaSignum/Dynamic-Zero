## Adaptive Pneumatic State and Distributed Physical Memory

Dynamic Zero is hypothesised to operate as a coupled state-dependent pneumatic system in which the physical state of the entire system participates in each subsequent interaction.

The system does not store the past as a separate record. Instead, the consequences of preceding interactions remain physically present in the current state of the diaphragm, moving air mass, pressure distribution, DMI, DM Impulser, DM Container, DMDC, and their mutual coupling.

In this sense, DZ exhibits distributed physical memory:

$$
X(t) = \{X_{diaphragm}, X_{DMI}, X_{impulser}, X_{container}, X_{DMDC}, X_{air}\}
$$

where X(t) represents the instantaneous physical state of the coupled DZ system.

The next state is therefore not determined by the new electrical input alone:

$$
X(t+\Delta t) = F(X(t),u(t))
$$

where u(t) is the new driver input.

Conceptually:

**Inherited system state + new input → physical interaction → new system state**

The previous state is not reproduced or recalled. It persists only through its physical consequences in the present system state.

### Momentum Heritage

One component of this distributed state is the momentum and pressure history inherited from preceding motion.

Rather than treating each half-cycle as beginning from an independently reset pneumatic condition, DZ assumes physical continuity between successive interactions. Air-mass momentum and pressure distribution produced by preceding motion may therefore remain part of the initial condition for subsequent motion.

This inherited component can be represented conceptually as:

- **M(t)** — momentum heritage

The heritage need not represent only the immediately preceding half-cycle. Successive interactions may form a decaying physical trail in which more recent states contribute more strongly while the effects of older states progressively diminish.

This natural weakening of inherited state is referred to here as **recency decay**.

Under sufficiently repetitive or monotonic excitation, the momentum trail may approach a relatively stable recurring form. When the input changes, however, part of the inherited state may no longer remain compatible with the developing system motion.

### Mismatch-Dependent Attenuation

DZ is hypothesised to exhibit an adaptive process in which incompatible parts of the inherited pneumatic state are attenuated more rapidly than would occur through recency decay alone.

This process is termed **mismatch-dependent attenuation**.

The distinction is important:

- **Recency decay** describes the natural reduction of older inherited state with time.
- **Mismatch-dependent attenuation** describes additional reduction associated with a difference between the inherited state and the state developing under the new input.

The DMDC is expected to participate in this process through controlled bidirectional mass exchange, but the adaptive behaviour is not assigned to the DMDC alone. It is hypothesised to emerge from the coupled response of the complete DZ pneumatic system.

A useful conceptual analogy is an eraser. The system does not erase its entire inherited state. Instead, parts of the inherited state that no longer remain compatible with the developing interaction may be reduced more rapidly.

Importantly, this erasure is not assumed to be instantaneous or memoryless. The physical process by which an inherited state is modified may itself leave a residual state within the coupled pneumatic system.

### Erasure Heritage and Second-Order Memory

A further DZ hypothesis is that mismatch-dependent attenuation is itself state-dependent.

If the process that modifies inherited momentum leaves a physical consequence within the pneumatic system, then the next interaction begins not only with momentum inherited from preceding motion, but also with a state conditioned by previous corrections.

This second history-dependent component can be represented conceptually as:

- **E(t)** — erasure heritage

The two conceptual state components therefore describe different aspects of system history:

- **M(t)** — what physical state was inherited.
- **E(t)** — how previous inherited states were modified.

The resulting conceptual state evolution can be written as:

$$
[M(t),E(t)] + u(t) \rightarrow [M(t+\Delta t),E(t+\Delta t)]
$$

This does not imply that M(t) and E(t) are stored in separate physical memory elements. Both are conceptual variables describing history-dependent properties distributed across the same coupled pneumatic system.

The distinction introduces a possible **second-order memory** effect.

The present interaction may depend not only on the physical consequences of preceding motion, but also on the physical consequences of how previous inherited states were modified.

In simplified form:

**First-order heritage:** what happened remains physically consequential.

**Second-order heritage:** how the system responded to what happened also remains physically consequential.

The system therefore does not need to store or recall previous signals. Its present physical state already contains the surviving consequences of previous interactions.

### Adaptive State Formation

The combined hypothesis can be represented conceptually as:

**Past interactions → decaying momentum trail → inherited system state → interaction with new input → mismatch-dependent attenuation → updated system state**

Because the attenuation process may itself have a residual physical state, the complete process becomes:

**Previous interactions → M(t) + E(t) → new input → coupled pneumatic interaction → M(t+Δt) + E(t+Δt)**

Under repetitive excitation, the inherited state may progressively approach a recurring form.

When the input changes, the existing heritage does not need to disappear completely before the system can respond. Instead, the new input interacts with the state already present, while incompatible parts of that state may be progressively attenuated.

This provides a possible physical basis for adaptive DZ behaviour without requiring an electronic controller, stored digital information, or prediction of a future signal.

The system does not know what comes next. It responds to the new input from the physical state in which the preceding interactions have left it.

### Relation to ICMC

Inter-Cycle Momentum Continuity (ICMC) describes one part of this broader state-dependent behaviour.

ICMC specifically refers to the persistence of air-mass momentum and pneumatic state between successive half-cycles.

Distributed physical memory is a broader hypothesis. It considers the complete coupled DZ state, including not only momentum continuity but also the possibility that previous state-modification processes influence subsequent interactions.

Therefore:

**ICMC → continuity of inherited pneumatic momentum and state**

while:

**Distributed physical memory → continuity of the coupled physical consequences of previous system interactions**

ICMC should therefore be understood as a component of the broader state-dependent DZ model rather than as a complete description of its memory behaviour.

### Relation to the MOPA Analogy

The distributed-state behaviour described here is outside the scope of the MOPA analogy used elsewhere in this document.

The MOPA analogy describes only the reinforcement principle: energy retained from a preceding state can participate in the interaction with new input energy.

It does not describe the complete DZ mechanism.

In a classical MOPA architecture, the amplified output does not mechanically act back upon the source in a way that becomes part of the source state for the next interaction.

DZ is hypothesised to operate differently because its pneumatic interaction is reciprocal. The diaphragm modifies the pneumatic system, while the resulting pneumatic state acts back upon the diaphragm through the coupled DZ network.

Conceptually:

**MOPA analogy → retained energy + new input → reinforcement**

whereas:

**DZ → inherited coupled state + new input → reciprocal interaction → new coupled state**

The new DZ state then becomes the physical initial condition for subsequent interaction.

The MOPA analogy therefore describes the principle of energy reinforcement, not the adaptive or state-dependent mechanism by which DZ is hypothesised to operate.

### Experimental Status

Distributed physical memory, momentum heritage, recency decay, mismatch-dependent attenuation, and erasure heritage are currently working hypotheses intended to provide a state-space framework for describing observed DZ behaviour.

The existence of pneumatic state continuity is physically expected in a coupled mechanical-pneumatic system, but the specific contributions represented here by M(t) and E(t), their decay rates, spatial distribution, interaction, and dependence on operating conditions have not yet been independently quantified.

Future synchronized measurements of diaphragm motion, local pneumatic pressure, air-mass motion, driver voltage, and driver current are intended to determine whether these state variables provide a useful quantitative description of DZ operation.

The purpose of this model is therefore not to assume a final mechanism, but to define a falsifiable framework from which measurable predictions and a more complete dynamical model can be developed.
