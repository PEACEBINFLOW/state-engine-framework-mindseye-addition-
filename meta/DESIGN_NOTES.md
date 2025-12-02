# Design Notes – State Engine Framework

The State Engine Framework is based on a simple idea:

> Conversations with AI should behave more like **state machines** than endless scrolls of text.

Key principles:

- **Sections, not streams** – Break work into labeled sections.
- **Dependencies, not guesses** – Explicitly declare what affects what.
- **Commands, not vibes** – Use a small command vocabulary (UNLOCK, UPDATE, FREEZE, etc.).
- **Templates, not ad-hoc prompts** – Reuse the same structures across tools and sessions.
- **Outputs as state** – Final outputs generate templates that become the next starting state.

Future notes will document each Template type (PST, SST, CST, etc.) and how they interact.
