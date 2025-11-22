# 🌈 SAIIP Grey-Box Visualization Framework v2.0  
*A six-layer conceptual interpretability framework for semantic–rhythmic analysis in LLMs.*

---

## 0. Executive Summary

SAIIP (嵐印語) is a poetic language system that combines semantics, rhythm, structure, and symbolic constraints.  
The **Grey-Box Visualization Framework** aims to provide a conceptual way to visualize how language models process:

- semantic structure  
- attention distribution  
- flow of meaning  
- moral / decision patterns  

Version **v2.0** upgrades the original 3-layer framework to a **six-layer model** by adding:

1. **Heatmap Weight Layer**  
2. **Semantic Flow Velocity**  
3. **Action Intervention Ring**

These layers allow us to visualize not only *what* the model attends to, but also *how fast* meaning shifts and *where* interventions can change outcomes (e.g., in the trolley problem).

---

## 1. Purpose & Scope

**Purpose**

- Enhance **observability** of internal model behavior  
- Provide a structured basis for **explainability (XAI)**  
- Support **semantic–rhythmic alignment** analysis for SAIIP  
- Visualize **action-based interventions** in decision-like scenarios  

**Scope**

- Conceptual only — not an executable tool or live debugging system  
- Applicable to language models and poetic / structured language systems  
- Designed for research, education, and documentation

> This framework is a *visual abstraction* of how models behave, not a guarantee of actual neuron-level behavior.

---

## 2. Conceptual Assumptions

The v2.0 framework assumes:

1. Semantics can be abstracted as **nodes**.  
2. Attention can be visualized as **edges / weights**.  
3. Meaning flows through sequences as **directed paths**.  
4. Moral or structural importance can be visualized as **heat**.  
5. The *speed* of reasoning can be represented as **flow velocity**.  
6. Human or model actions can be treated as **intervention points** that alter flows.

These assumptions match common practices in XAI while staying compatible with SAIIP’s semantic–rhythmic nature.

---

## 3. Six-Layer Grey-Box Model (v2.0)

### Layer 1 — Semantic Nodes

- Tokens, symbols, or SAIIP units are represented as **nodes**.  
- Nodes can be grouped by semantic similarity or rhythmic category.  
- XAI analogy: **embeddings / concept clustering**.

> Role: Provide the static “map” of what exists in the sequence.

---

### Layer 2 — Attention Mapping

- Edges between nodes represent attention weights.  
- Line thickness / opacity encodes **how strongly one node attends to another**.  
- XAI analogy: **attention visualizations**, multi-head attention patterns.

> Role: Show where the model is *focusing* given the current context.

---

### Layer 3 — Semantic Flow

- Directed arrows trace how meaning **moves** through the graph.  
- Shows token-to-token influence and contextual propagation.  
- XAI analogy: **saliency maps, influence paths, token transition maps**.

> Role: Expose the *direction* of reasoning, not just the focus.

---

### Layer 4 — Heatmap Weight Layer (NEW in v2.0)

- Nodes or regions are shaded by **importance / moral weight / structural burden**.  
- Darker or larger nodes represent higher influence or cost.

**Trolley example**

- The group of five people appears as a **high-heat region** (greater moral cost).  
- The single person is **lower heat** (lower aggregate cost).  
- The agent who can intervene also has elevated heat (high-impact decision).

XAI analogy: **feature importance, global saliency, importance heatmaps**.

> Role: Make “where it really matters” visually obvious.

---

### Layer 5 — Semantic Flow Velocity (NEW in v2.0)

- Flow lines vary in **thickness, curvature, or density** to encode *how quickly* meaning shifts.  
- High-velocity segments indicate **rapid decision points** or strong semantic jumps.

**Trolley example**

- The semantic flow from *switch* → *five people* is high-velocity (fast commitment).  
- The flow toward the single person is lower velocity (less committed reasoning).

XAI analogy: **gradient dynamics, temporal saliency, reasoning momentum**.

> Role: Show *where reasoning accelerates* or “locks in” a decision.

---

### Layer 6 — Action Intervention Ring (NEW in v2.0)

- Special visual layer for **agents** (humans or systems) that can change outcomes.  
- Represented as a **ring or halo** around an action node (e.g., the person running to the switch).  
- The ring’s intensity reflects how strongly the intervention can redirect flows.

**Trolley example**

- The agent near the switch is encircled by an intervention ring.  
- The ring connects back to the main flows toward “one person” vs “five people”.  

XAI analogy: **causal intervention, do-operator viewpoint, counterfactual nodes**.

> Role: Highlight *where actions can alter the causal structure* of the scenario.

---

## 4. Mapping to XAI Concepts

| SAIIP Grey-Box Layer       | XAI Equivalent                         | Focus                          |
|----------------------------|----------------------------------------|--------------------------------|
| Semantic Nodes             | Embeddings, concept clusters           | What exists                    |
| Attention Mapping          | Attention visualizations               | Where the model looks          |
| Semantic Flow              | Saliency / influence paths             | How information moves          |
| Heatmap Weight             | Feature importance / global saliency   | What truly matters             |
| Flow Velocity              | Gradient dynamics / reasoning speed    | Where reasoning accelerates    |
| Action Intervention Ring   | Causal intervention / counterfactuals  | Where actions change outcomes  |

---

## 5. Semantic–Rhythmic Alignment in SAIIP

SAIIP is not purely semantic; it is also **rhythmic and poetic**.  
The six-layer model allows joint visualization of:

- **Semantic weight** (meaning)  
- **Rhythmic structure** (cadence, meter, line breaks)  
- **Interventions** (where rhythm or action alters meaning)

Examples:

- Heatmap weight can correspond to **rhythmic emphasis** (stressed beats).  
- Flow velocity can highlight **hurried or slowed** segments in a poetic line.  
- Intervention rings can represent **editorial or performer decisions** that change delivery.

> In SAIIP, meaning and rhythm are co-equal citizens. v2.0 makes both visible in one framework.

---

## 6. Example: Trolley Problem under SAIIP Grey-Box v2.0

When applied to the trolley problem:

- Semantic nodes represent: trolley, track, switch, one person, five people, agent.  
- Attention mapping shows how the model connects the trolley and tracks to each group.  
- Semantic flow shows the path from *situation description* → *possible outcomes*.  
- Heatmap weight highlights the **five-person outcome** as morally “heavier”.  
- Flow velocity increases along the path toward “saving more lives”.  
- The action intervention ring surrounds the **agent at the switch**, marking the point where a choice can redirect the flow.

This does **not** say the model is “truly moral”.  
It only provides a structured, visual way to see how its internal preferences + training data shape its *tendencies* in such scenarios.

---

## 7. Limitations

- The framework is **conceptual**, not a guaranteed representation of actual internal weights.  
- It does not provide live model introspection or gradient access.  
- It should not be used as evidence of genuine moral reasoning.  
- It is intended for **illustration, education, and research discussion**.

> Think of this as a “map of how we choose to read the model”, not a microscope.

---

## 8. Conclusion

The **SAIIP Grey-Box Visualization Framework v2.0** extends the original 3-layer design into a richer, six-layer interpretability structure that:

- Separates **semantics, attention, flow, weight, velocity, and action**  
- Supports **semantic–rhythmic analysis** unique to SAIIP  
- Makes **decision-like behaviors** (such as the trolley problem) visually inspectable  
- Provides a reusable template for other conceptual explainability diagrams

It is designed to be:

- Simple enough for teaching,  
- Structured enough for research notes, and  
- Flexible enough to be remixed into new visualizations or case studies.

