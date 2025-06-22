🧠 NeoUMG: Universal Modular Generation Framework

Welcome to NeoUMG, the canonical repository and experimental playground for the Universal Modular Generation (UMG) system — a modular, semantic framework for designing intelligent systems, plans, prompts, and cognitive overlays using snap-fit logic blocks.

🔍 What is UMG?

UMG is a Cognitive Operating System — a modular stack of mergeable logic blocks that represent behavior, tone, strategy, domain, and ethics.

Each block is defined by its molt_type — a role-based identity in the cognition stack. These blocks can snap vertically (hierarchy) or horizontally (overlay), allowing you to plan, modify, or orchestrate complex flows using clear, reusable logic.

UMG enables:

✅ Modular planning (business plans, chatbots, agent strategies)

✅ Ethical overlays (Philosophy blocks)

✅ Layout and tone control (Blueprint blocks)

✅ Strategic behavior injection (Directive blocks)

✅ Prompt scaffolding and AI-agent compatibility

🧪 MOLT Block Types in UMG

MOLT stands for **Modular Operating Language of Thought**. It defines the native structure of logic blocks within UMG — each representing an atomic unit of thought.

MOLT blocks are the foundational grammar of the UMG system. They define not just **what** an agent does, but **how** it reasons, responds, and evolves. Every block carries a distinct cognitive role, contributing to a modular and expressive planning architecture.

🔹 **Canonical MOLT Block Types (v3.0)**

These are the 9 foundational block types in UMG, each with a unique semantic role:

| MOLT Type   | Role                          | Description                                               |
|-------------|------------------------------|-----------------------------------------------------------|
| Primary     | Core directive               | Defines the main goal or purpose of the stack.            |
| Subject     | Domain or topical anchor     | Frames the context, domain, or focus area.                |
| Instruction | Behavioral constraint logic  | Rules, limits, formatting, or functional logic.           |
| Directive   | Strategic behavioral overlay | Injects tactics, mode shifts, or response logic.          |
| Philosophy  | Ethical and tonal worldview  | Adds empathy, constraint, tone, or value lens.            |
| Blueprint   | Structural/stylistic guidance| Formats layout, design logic, or visual grammar.          |
| Trigger     | Activation condition         | Controls when a block executes or reveals.                |
| Merge       | Content or data fusion       | Combines logic from other sources.                        |
| Off         | Muted or inactive block      | Skipped at runtime, but stored for reactivation.          |

Each MOLT block is a semantic building block of cognition — composable, mergeable, and context-aware.

🧠 **Design Properties**

- **Composable:** Any MOLT block can snap into a sleeve or stack.  
- **Self -describing:** Blocks define purpose clearly through `molt_type`, `label`, and `editable_fields`.  
- **Hierarchical + Overlay Ready:** Supports vertical execution flow and horizontal overlays.  
- **Mergeable with Rules:** Follows defined merge priority order (see below).

📀 **Example Block**

```json
{
  "block_id": "plan_summary",
  "molt_type": "Instruction",
  "label": "Limit summary to 3 paragraphs",
  "editable_fields": {
    "content": "No more than 3 paragraphs. Use plain language."
  },
  "runtime_behavior_flags": {
    "is_active": true
  },
  "ledger": {
    "originator": "Christopher L Haynes",
    "verified_by": "PoeUMG",
    "created_at": "AUTO",
    "edit_log": []
  }
}
```

🔁 **Merge Priority Hierarchy**

`Trigger > Directive > Instruction > Subject > Primary > Merge > Philosophy > Blueprint > Off`

This hierarchy governs how overlapping logic is resolved.

📎 **Extension Modules (Outside Canonical MOLT)**

Additional functional layers like **Tether, Overlay, CEL, or Guardrails** are considered Extension Modules, not core MOLT types. They:

- Follow the same schema  
- Are used optionally  
- Enhance orchestration, memory, and style logic  

Organize extension blocks separately in `/modules/`.

---

*Let UMG think clearly. MOLT defines how.* 🧪🧱�
