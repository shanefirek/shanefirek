### Shane Firek

GTM Systems Architect. I build acquisition infrastructure as production software: Postgres warehouses, enrichment and scoring pipelines, event-to-rep routing, and governed write paths (dry-run defaults, receipts, kill switches) safe enough for AI agents to operate in production. Code-first, not vendor-dependent.

**What I build:**
- Acquisition data layers: warehouse mirrors of the GTM stack, scheduled job fleets, gated CRM writers
- Signal pipelines: ingest, enrichment waterfalls, ICP + intent scoring, routing with reasons
- MCP servers and agent-safe tooling for enterprise systems
- Co-building [Braid](https://www.agentrelayprotocol.com): a coordination layer for AI agents owned by different people. Live, in beta.

**Open source:**
- [GTM Signal Pipeline](https://github.com/shanefirek/gtm-signal-pipeline) — signal ingest to routed action on Cloudflare Workers; atomic claims, reapers, kill switches. Live demo.
- [CRM Provisioner](https://github.com/shanefirek/crm-provisioner) — natural language to provisioned CRM; the LLM proposes, a human approves, a deterministic driver executes
- [Signal Pipeline Template](https://github.com/shanefirek/signal-pipeline-template) — production signal-to-CRM pipeline scrubbed into a template; Supabase + Trigger.dev, 412 tests
- [HubSpot Provisioner](https://github.com/shanefirek/hubspot-provisioner-template) — one install provisions a GTM-ready portal in ~30 seconds
- [MCP Security Scanner](https://github.com/shanefirek/mcp-security-scanner) — NSA-guidance-mapped static scanner, 35+ checks across 11 threat categories
- [MCP Handbook](https://github.com/shanefirek/mcp-handbook) — plain-English guides to MCP servers
- [Porkbun MCP Server](https://github.com/shanefirek/porkbun-mcp-server) — domain registration + DNS from Claude Code

**Links:** [shanefirek.com](https://shanefirek.com) · [LinkedIn](https://linkedin.com/in/shanefirek) · [X](https://x.com/shanefgtm)
