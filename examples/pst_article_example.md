# PST Example — Dev Article: "Navigating AI Projects Without Scrolling to Death"

This example shows how to use `PST_v1.1` with an AI model (ChatGPT/Claude/Grok) to structure and write a DevCommunity article.

---

## 1. Initialization

**User action:**

Paste the full contents of `core/PST_v1.1.md` into a new AI chat, then append:

```text
Fill in the PROJECT METADATA now:

- PROJECT NAME: Navigating AI Projects Without Scrolling to Death
- PROJECT TYPE: DevCommunity article
- GOAL OF PROJECT: Teach developers how to structure their AI chats using a Project State Template so they can control sections, avoid messy rewrites, and stop scrolling through endless text.

SECTION MAP:
- [ A ] Introduction & The Scroll Problem
- [ B ] Pain Points of Unstructured AI Conversations
- [ C ] The Project State Template Framework
- [ D ] Concrete Walkthrough: Managing a Dev Article
- [ E ] Summary & Implementation Guide

DEPENDENCY MAP:
- A affects: B, C, E
- B affects: C, D
- C affects: D, E
- D affects: E
- E references all, usually independent

Keep all sections LOCKED internally. Then: SHOW SNAPSHOT.
