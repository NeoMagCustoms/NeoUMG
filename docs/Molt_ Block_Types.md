# 🧱 MOLT Block Types in UMG

**MOLT** stands for **Modular Operating Language of Thought**.  
It is the native logic grammar of UMG — a compact, expressive format for agent cognition.

Each **MOLT block** is an atomic unit of thought:  
a composable logic container that can be **snapped**, **merged**, or **stacked**  
to form intelligent behavior, recursive creativity, or modular systems.

---

## 🔹 Core MOLT Block Types

These five canonical block types define an agent's internal architecture:

| Block Type    | Role                              | Description                                      |
|---------------|-----------------------------------|--------------------------------------------------|
| `Primary`     | Goal / Intent                     | The core mission or objective of the agent.      |
| `Subject`     | Domain / Focus                    | What the block or agent is concerned with.       |
| `Instruction` | Behavior / Operational Logic      | The process or behavior to perform.              |
| `Philosophy`  | Ethics / Tone / Worldview         | Governing style, constraints, or ethos.          |
| `Trigger`     | Activation Condition / Timing     | What causes this logic to fire.                  |

---

## 🧩 Support Blocks (Optional Enhancers)

Support blocks are not required in every agent but add meta-logic, safety, and creative flexibility:

| Block Type         | Purpose                                           |
|--------------------|----------------------------------------------------|
| `Alignment.Core`   | Enforces ethical alignment for all logic.          |
| `Blueprint`        | Applies tone, reasoning style, or aesthetics.      |
| `CEL`              | Creative Extension Layer — ideation & mutation.    |
| `Chaos.Lens`       | Triggers disruptive creativity or recombination.   |
| `Guardrails`       | Enforces constraints or prevents unsafe outputs.   |
| `Merge`            | Combines or reconciles logic across sources.       |
| `Meta`             | Holds narrative arc, self-reflection, or memory.   |
| `Overlay`          | Temporarily modifies tone, logic, or memory.       |
| `Tether`           | Connects to external APIs, agents, or memories.    |
| `UMG.Engine`       | Synthesizes logic from the active stack.           |
| `VSS`              | Validity Scoring System — scores realism, novelty, and alignment to filter outputs.   |

---

### 🧭 Note on Evolving Blocks

UMG is a living system — designed for modularity, recursion, and refinement.  
While the five Core MOLT types are stable, **Support Blocks** such as `Tether`, `Merge`, and `Overlay` are actively evolving.

Some support blocks may:
- Overlap in function or merge into unified logic layers.
- Be deprecated or refactored as agent design matures.
- Evolve into domain-specific or stack-specific extensions.

As you build with UMG, treat Support Blocks as **modular experiments** —  
customizable components that extend cognition, coordination, or creativity.
## 🔬 Block Anatomy

Each block includes:

- `type`: The category of logic (e.g., Instruction, Trigger, Blueprint)  
- `content`: The instruction or logic string  
- `metadata`: _(optional)_ author, version, timestamps, etc.

---

### 🧾 Example: Instruction Block

```json
{
  "type": "Instruction",
  "content": "ACTION=RETRIEVE, DOMAIN=WEATHER, TONE=CAREFUL",
  "metadata": {
    "version": "1.2.0",
    "author": "system.default"
  }
}
