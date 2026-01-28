---
name: "hud"
displayName: "Hud - Runtime Observability"
description: "Production runtime observability platform for monitoring application performance, debugging issues, and analyzing code behavior in real-time"
keywords: ["observability", "monitoring", "debugging", "performance", "tracing", "metrics", "logs", "apm", "runtime", "production", "error tracking", "profiling", "analytics"]
---

# Hud Power

Hud provides real-time observability into your production applications, helping you monitor performance, debug issues, and understand code behavior at runtime.

1. Get the Schema

**IMPORTANT: Always start by calling `hud-get-schema` to retrieve the current database schema, table structures, query patterns, and examples before querying Hud data.**

The schema includes:
- Complete table definitions (Endpoints, Functions, Metrics, Forensics, etc.)
- Query patterns and SQL functions
- Best practices for filtering and performance
- Example queries for common use cases


2. Get Skills for Common Scenarios

**Use `hud-get-skill` for guidance on specific scenarios:**

Read the "Available skills" in the tool, and check if the user's intent matches a description of a skill, if it is - call `hud-get-skill` with the relevant skill name. This tool provides:
- Step-by-step investigation guidance
- Recommended SQL queries
- Best practices for the scenario

Always check the tool's description to see available skills and determine if one is relevant to the user's request before proceeding with manual queries.

3. Query Hud

After getting the schema, use `hud-query` to execute SQL queries and `hud-get-forensics` to retrieve detailed error instances including parameters, exception messages, stacktraces, machine metrics, traceIDs and more.
To read files Hud put on the disk on a tmp folder, use bash commands.

# Onboarding

**Prerequisites:** [Hud Account](https://app.hud.io)

**Setup (choose one):**

1. **IDE Extension (Recommended):** Install "Hud" from your IDE marketplace → Login via the extension panel
2. **Environment Variable:** Set the environment variable `HUD_MCP_KEY` → take it from the API Keys tab in your Hud dashboard (https://www.app.hud.io/settings/api-keys)


# Support
- Documentation: [docs.hud.io](https://docs.hud.io)
- Support Email: support@hud.io
- Support chat: https://www.app.hud.io/?support_chat=true
- GitHub: [github.com/code-hud/hud-kiro-power](https://github.com/code-hud/hud-kiro-power)
