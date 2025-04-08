# Fluent Python Study Tracker

This tracker follows my study of *Fluent Python* by Luciano Ramalho. The goal is to master Python’s advanced features and idiomatic patterns.

---

## 📅 Weekly Plan

| Week | Chapters | Status | Focus | Deliverable |
|------|----------|--------|-------|-------------|
| 1    | 1–2      | ☐ Not started | Dunder methods, sequences | Custom container class (Boss 1) |
| 2    | 3–4      | ☐ Not started | Dictionaries, Unicode | Word frequency analyzer |
| 3    | 5–6      | ☐ Not started | First-class functions | Strategy pattern refactor (Boss 2) |
| 4    | 7–8      | ☐ Not started | Decorators, mutability | Memoization & logging decorators |
| 5    | 9–10     | ☐ Not started | String reps, custom sequences | Slicing-enabled class |
| 6    | 11–13    | ☐ Not started | ABCs, inheritance, overloading | Vector class with operators (Boss 3) |
| 7    | 14–15    | ☐ Not started | Iterators, context managers | CSV reader with `with` support |
| 8    | 16       | ☐ Not started | Coroutines | Coroutine-based filtering pipeline |
| 9    | 17–18    | ☐ Not started | Asyncio, futures | Async downloader (Boss 4) |
| 10   | 19–20    | ☐ Not started | Multiprocessing, descriptors | Parallel data processor |

---

## ✅ Study Rules

- Code all examples manually and tweak them
- Use notebooks or markdown for notes per chapter
- Build a mini-project or script for each major concept
- Reflect each week: "How can I use this in my DNA scanner?"
- Document learning through structured writing (no need for video)

---

## ✍️ Reflection System (Memory Boost Mode)

📁 `reflections/`
- `daily_log.md` → Write 1–3 bullet points after each session
- `weekX_reflection.md` → Weekly summary of concepts learned, struggles, and practical use

📁 `concepts/`
- Sketches, diagrams, or mental models for hard ideas (e.g., data model, coroutines, async)

### Example – daily_log.md
```markdown
## Day 1 – April 9
- Learned how `__getitem__` makes an object indexable.
- Wrote a custom Deck class → works with `random.choice()`.
- Unsure: when to use `__contains__` vs fallback to iteration?
```

### Example – week1_reflection.md
```markdown
## Week 1 Reflection

### 🧠 What I learned:
- Python data model is what makes code feel native.
- Implementing just two dunders gives you a lot of behavior for free.

### 🤔 Struggles:
- Understanding fallback mechanism when `__contains__` isn’t defined.

### 🔁 DNA Project Relevance:
- I can use `__getitem__` to allow indexing on DNA sequence strings.
- Plan to build a container that supports slicing and membership checks.
```

---

## ⚔️ Project Checkpoints

| Level | When | Project Focus |
|------------|------|----------------|
| 1     | After Week 1 | Custom DNAContainer class with slicing/indexing support |
| 2     | After Week 3 | Strategy pattern for DNA scan steps (e.g. flexible function pipeline) |
| 3     | After Week 6 | A mini library with OOP-powered sequence utilities and vector-like ops |
| 4     | After Week 9 | Async batch DNA pattern matcher across multiple input files |

---

## 🧠 Extra

- 📝 Daily micro-journal: short notes per study session
- ✍️ Weekly summary: highlight what I have learned, what was hard, and how it connects
- 🧱 Build my own `fluentbox/` library over time
- 📊 Track levels and reflections for personal growth
- 🧭 Map ideas visually for clarity and deeper understanding
