# Contributing to State Engine Framework

Want to propose a new State Template or improve an existing one?

## 1. Before you start

- Check `ROADMAP.md` to see if a similar template is already planned.
- Read `meta/DESIGN_NOTES.md` to understand the core principles.

## 2. Adding a new State Template

1. Create a new file in `core/`, e.g.:

   - `CST_v1.0.md` – Coding State Template  
   - `WST_v1.0.md` – Writing State Template  

2. Include:
   - Role & goal
   - Metadata section
   - Sections / states
   - Command vocabulary
   - Output format
   - Reuse instructions

3. Add at least one example in `examples/`.

4. Open a Pull Request with:
   - Summary of what the template solves
   - How you tested it (which AI model, what kind of project)

## 3. Improving existing templates

- Keep changes minimal and focused.
- Don’t make templates model-specific; they should be usable across tools (ChatGPT, Claude, Grok, etc.).
- Avoid overcomplicating – clarity beats cleverness.

---

Thanks for contributing to the State Engine ecosystem. 🚀
