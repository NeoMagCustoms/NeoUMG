# 🧠 Logic Grammars in UMG

UMG (Universal Modular Generation) uses two complementary grammars to structure modular cognition:  

- **CantoCore** – a poetic, directive logic syntax used in most MOLT blocks  
- **CyentCore** – a compressed, code-like format optimized for parsing and recursion

---

## 🔡 CantoCore

**CantoCore** is a compact, readable syntax designed to express logical structures in a poetic, declarative style.  
It is human-readable, agent-trainable, and used for clarity of thought and modular expressiveness.

### ✨ Example

```
GOAL=RETRIEVE.DATA
DOMAIN=WEATHER
STYLE=CAREFUL
```

### 📘 Usage

- Used in `Primary`, `Subject`, `Instruction`, `Philosophy`, and `Trigger` blocks  
- Supports capitalized `KEY=VALUE` statements  
- Allows chaining multiple directives per block  
- Agent-friendly format for modular prompts

---

## 🧬 CyentCore

**CyentCore** is a condensed, machine-optimized version of CantoCore designed for tight logic parsing, runtime performance, and recursive self-modification.

It is used primarily in deeper stacks, reflection loops, or agent systems requiring compact and programmatic formats.

### ✨ Example

```json
{
  "type": "Instruction",
  "content": "ACTION=RETRIEVE, DOMAIN=WEATHER, STYLE=CAREFUL",
  "metadata": {
    "version": "1.2.0",
    "author": "system.default"
  }
}
```

### 📘 Usage

- Common in JSON-style MOLT stacks or pipelines  
- Can be interpreted directly by UMG.Engine or agent runtimes  
- Functions as a drop-in substitute when CantoCore needs compression

---

## 🧩 Notes

- **Both grammars are interoperable** — agents can convert between CantoCore and CyentCore based on context.  
- **CantoCore** emphasizes **readability and creative expression**, ideal for design and storytelling layers.  
- **CyentCore** emphasizes **performance and structure**, ideal for recursive agents and evaluation engines.  
- Support for both grammars ensures UMG systems can scale from poetic interaction to precise computation.

---

## 🔗 See Also

- [MOLT Block Types](./Molt_Block_Types.md)  
