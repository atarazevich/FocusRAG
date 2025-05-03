# FocusRAG

> A graph-enhanced, cognitively structured memory engine for LLM agents.

**FocusRAG** builds on [LightRAG](https://github.com/HKUDS/LightRAG) to provide LLMs with _focus_—not just memory. It enhances retrieval and response context using graph-based structure, semantic perspectives, and a markdown-style output format that organizes knowledge into **knowns**, **unknowns**, and **interpretations**.

---

## 🌐 Why FocusRAG?

Most LLM memory systems rely on flat text chunks or basic vector search. This creates two problems:
- 🧠 **Lack of cognitive layering** — LLMs can't distinguish between what is known, uncertain, or implied.
- 📎 **Flat memory structure** — There’s no modularity, perspective, or prioritization in how memory is retrieved.

**FocusRAG** changes this by:
- Using **graph-based linking** to connect semantically related concepts
- Injecting **perspective plugins** (like `@Critic`, `@Planner`, etc.) for deeper reflection
- Structuring results into an annotated, markdown-style **Focus Snapshot**

---

## ✨ Features

- ✅ **Graph-aware retrieval** via LightRAG core
- 🧭 **Focus Snapshot** output: `{knowns, unknowns, thoughts, suggestions}`
- 🧩 **Pluggable perspectives**: Run additional sub-models for insight
- 🔁 **Correction-aware**: Designed to learn from user refinements
- 🧠 **Cognitive zooming**: Expand or contract focus area dynamically
- 🌐 **JRPC-compatible API**: Easily drops into any agent runtime
