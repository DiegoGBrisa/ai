---
'@tanstack/ai': minor
---

feat: add experimental agentLoop for agentic text generation

Introduces `agentLoop`, which orchestrates agentic text generation by wrapping `text()` with automatic tool execution and looping. Supports tool calls, approval flows, client tools, and configurable loop strategies.
