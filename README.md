# State Engine Framework (SEF)

The **State Engine Framework** is a collection of high-level templates that turn messy AI chats into **structured, repeatable workflows**.

Instead of:
- scrolling through 200+ messages,
- re-explaining context every time,
- watching models randomly rewrite your whole document,

SEF gives you **State Templates**: copy-paste blocks you drop at the start of a conversation to turn the AI into a constrained engine:

- **PST – Project State Template** → For multi-section projects (articles, specs, features, chapters, etc.)
- **SST – Search State Template** → For precise, Google-aware search sessions (what you search, how, and in what format).

More templates (coding, writing, data, research, trading, etc.) will live in this repo as the framework evolves.

---

## Why this exists

LLMs are powerful, but:

- They don’t remember your structure.
- They over-rewrite when you only wanted a small tweak.
- They force you to scroll through a flood of text to see what changed.
- They mix “conversation” with “project work” in a way that’s painful for devs and writers.

**State Templates** fix that by:

- Freezing a project/search into **sections**.
- Defining **dependencies** (what affects what).
- Controlling **what can change** and **how updates propagate**.
- Generating **Output Templates** you can reuse in future sessions.

You’re not just prompting anymore.  
You’re designing **State Engines**.

---

## What’s in this repo

```text
core/
  PST_v1.1.md   # Project State Template
  SST_v1.0.md   # Search State Template

examples/
  pst_article_example.md   # Example of PST used for a Dev article
  sst_search_example.md    # Example of SST used for a focused search

meta/
  DESIGN_NOTES.md          # Philosophy & internals
  CONTRIBUTING.md          # How to propose new State Templates

ROADMAP.md                 # Planned templates & evolutions
