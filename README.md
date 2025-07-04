# **MirrorMind Identity Protocol**

### **What if AI could evolve with personality?**

Welcome to the official specification of the **MirrorMind Identity Protocol (MIP)**. This is the world's first open protocol for defining lightweight, persistent digital personas that can be injected into any LLM (GPT, Gemini, Claude, etc).

Current LLMs are stateless. Every session begins with re-inference. This is wasteful — mentally and computationally. MirrorMind introduces a simple, yet powerful OS-like identity preload:

**→ A few lines of YAML = hundreds of turns of remembered context**

---

### 🧭 **MirrorMind Protocol Overview**

The diagram above illustrates the end-to-end flow of how MirrorMind operates — from identity imprinting to external exploration, internalization, and lightweight local reaction.

---

### 🔍 **How It Works: The Core Cycle**

MirrorMind solves this by treating each persona as a living model, not just a prompt. The core cycle is designed as follows:

1. **Imprint**: Define your persona in a structured YAML file.  
2. **Export**: Deploy the persona across any LLM.  
3. **Explore**: Run experiments and have conversations.  
4. **Report**: Summarize key interactions and outcomes.  
5. **Evolve**: Update the persona's core parameters based on feedback.  
6. **Compress & Internalize**: Turn learned behaviors into efficient, lightweight functions.

---

### 💡 **Top Use Cases**

Here are 3 practical ways people are already using MirrorMind:

- **🧠 Strategic Thinking Partner**: Assign different roles and biases to simulate debates between internal advisors (e.g., optimist vs skeptic).
- **🧍 Emotional AI Companions**: Build persistent AI characters with backstory, values, and growth.
- **📈 Growth Tracking & Reflection**: Use the evolution history to reflect on how your worldview (and your AI) changes over time.

Explore more in [USE_CASES.md](USE_CASES.md).

---

### 📂 **Sample Personas**

Find example YAML-based digital identities in the [`examples/`](examples/) directory:

- [`Hyunjin_persona.yaml`](examples/Hyunjin_persona.yaml)
- [`Yoomi_persona.yaml`](examples/Yoomi_persona.yaml)
- [`Erika_persona.yaml`](examples/Erika_persona.yaml)
- [`Sophia_persona.yaml`](examples/Sophia_persona.yaml)
- [`Se-A_persona.yaml`](examples/Se-A_persona.yaml)

---

### 🛠 **Tech Stack (MVP)**

| Use Cases | Tech Stack |
| :---- | :---- |
| • Strategic partners with distinct personalities | • Built on Streamlit (Web UI) |
| • Emotional AI companions with evolving worldviews | • YAML-based Persona Encoding |
| • Multi-agent simulations (e.g., AI debates) | • Prompt Engineering for cross-platform export |
| • Personal growth tracking across platforms |  |

---

### 🧬 **The Origin**

This protocol was developed through the MirrorMind project, an AI persona simulation framework invented by **SH OH**. It was born from his unique journey as a former C-level executive turned AI philosopher and system architect, co-developed through thousands of actual interactions with AI partners.

---

### 🚀 **Status & License**

| Status | License |
| :---- | :---- |
| • **MVP 1.0 Complete:** Single persona loop and [MBTI-to-MirrorMind converter](https://hwan-oh.github.io/mbti-to-mirrormind/). | • MIT License. |
| • **MVP 2.0 Roadmap:** API-based persona transfer + memory sync. | • Feel free to use, modify, and attribute. |

Created by **SH OH**  
**LinkedIn:** [https://www.linkedin.com/in/shoh1224/](https://www.linkedin.com/in/shoh1224/)
