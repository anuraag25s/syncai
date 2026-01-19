# SyncAI Architecture Overview

## High-Level Architecture

Input Layer
- Slack bot (MVP)
- Web form (future)
- Voice notes → Speech-to-text

Context Layer
- Jira / Linear tickets
- GitHub PRs and issues

AI Layer
- LLM summarization
- Blocker detection
- Dependency inference
- Decision extraction

Output Layer
- Team digest
- Personalized summaries
- Action items & routing

---

## Design Principles

- Async-first
- Human-in-the-loop
- Source-linked outputs
- Minimal user effort
