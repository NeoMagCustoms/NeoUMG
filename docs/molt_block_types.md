# 🧱 MOLT Block Types in UMG

A **MOLT block** is the atomic unit of thought in UMG —  
a modular, self-contained logic structure that can be composed, snapped, or stacked.

All UMG-based agents, apps, and tools are built by combining MOLT blocks into working systems.

---

## 🔸 MOLT Block Categories

| Type          | Purpose                                      |
|---------------|----------------------------------------------|
| `Primary`     | Defines the main goal, mission, or output intent |
| `Subject`     | Declares the focus area or domain of relevance |
| `Instruction` | Encodes executable logic, rules, or methods     |
| `Philosophy`  | Applies tone, bias, ethics, or worldview        |
| `Trigger`     | Defines reactive behavior or activation conditions |

---

## 🔹 Anatomy of a MOLT Block

Each block typically includes:

- `type`: the category of the block  
- `content`: the meaning, instruction, or data  
- *(optional)* `metadata`: versioning, author, timestamps


Example:

```json
{
  "type": "Instruction",
  "content": "INSTR:EXECUTE.ON.TRIGGER:USER.INPUT.RECEIVED"
}
