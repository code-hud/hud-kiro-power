# Hud Power for Kiro

Production code runtime sensor for monitoring application performance, investigating issues, and analyzing code behavior in real-time. This power enables Kiro AI agents to query and analyze your production systems using Hud's data.

## About Hud

[Hud](https://hud.io) is the first Runtime Code Sensor designed specifically to make AI-generated code production-safe by default. Installed in under a minute with no configuration needed, it streams real-time, function-level runtime data from your live systems directly into your IDE.

Once deployed, Hud tracks how each function behaves in production—mapping execution patterns, surfacing behavioral changes, and delivering structured runtime signals without requiring logs or any manual work.

Hud is purpose-built for engineering teams using code-generating agents like Kiro.

## Features

- **Real-Time Production Insight**: Monitor function-level performance metrics, execution patterns, and errors
- **Forensics**: Detailed execution traces collected for specific requests to help with root cause analysis
- **Zero Configuration**: Deploy in under a minute with no configuration needed
- **AI-First Design**: Built specifically for AI agents to reason over production behavior
- **SQL-Based MCP**: Query your production runtime data from Hud using SQL through MCP tools
- **Smart Agent Context Management**: Pre-built investigation workflows for common scenarios (endpoint errors, slow endpoints, deployment analysis)

## Installation

### Prerequisites

1. **Hud Account**: Sign up at [app.hud.io](https://app.hud.io)
2. **Hud SDK**: Install the Hud SDK in your production services ([Node.js](https://docs.hud.io/docs/nodejs-installation) or [Python](https://docs.hud.io/docs/python-installation))

### Kiro Power Setup

#### Install Hud IDE Extension

1. Install the "Hud" extension from your IDE marketplace
2. Login via the extension panel

#### Add Hud Kiro Power

1. Open the Powers panel
2. Click "Add power from GitHub"
3. Enter: `https://github.com/code-hud/hud-kiro-power`

## What can you do with Hud and Kiro?

### 1 - Investigate Production Errors
Use prompts like:
- Why is `/endpoint` failing in production?
- Why is `kafka_queue` returning errors since 10:00?
- Why does `/api` return 501? 
- Why does service `service` have `TypeError`?

### 2 - Analyze Deployment Impact
Use prompts like: 
- Did my deployment from 14:00 cause any performance degradation?
- Is this week's performance improved compared to last month?
- Make sure no deployments from the last week caused a higher error rate

### 3 - Debug Slow Endpoints
Use prompts like:
- Why is `/api` slow in production?
- Users are complaining that sometimes the product pages take a minute to load, why?
- What's the endpoint with the highest P90 in `my_service`? Why is that happening? 


## Resources

- **Documentation**: [docs.hud.io](https://docs.hud.io)
- **Support Email**: support@hud.io
- **Support Chat**: [app.hud.io](https://www.app.hud.io/?support_chat=true)
