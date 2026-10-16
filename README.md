## Bhavesh Upadhyay

**I build agent systems that hold up at marketplace scale.**

By day I lead Recommendations at Flipkart: real-time user state for Flipkart, Myntra and Cleartrip at ~800K QPS with a sub-50 ms SLA. In public, I run a small team of AI agents that ships open-source software, and I publish exactly how it works, including what it gets wrong.

### The agent team

[**crew**](https://github.com/bhavesh1/crew): five Claude-powered agents (triager, builder, reviewer, release & docs, evals) working through GitHub issues and PRs. Agents propose; only I merge. Every decision, merged or rejected, goes into a public [decision log](https://github.com/bhavesh1/crew/blob/main/docs/decision-log.md) and a weekly [scorecard](https://github.com/bhavesh1/crew/blob/main/docs/scorecard.md).

```
issue → triager → builder → reviewer → me (merge / reject) → release & docs
                                              ↓
                                       decision log → evals
```

### Flagships

| Project | What it does | Status |
| --- | --- | --- |
| [crew](https://github.com/bhavesh1/crew) | A reusable template for running an agent team on a repo, with guardrails and evals | Building |
| kafka-mcp | MCP server so Claude can inspect Kafka topics, lag and schemas, read-only by default | Next |
| statekeeper | Real-time memory and user-state layer for agents on Redis + Kafka, with published latency benchmarks | Planned |

### Upstream

Contributions to MCP, agent SDKs and eval tooling will be listed here as they merge.

### Writing

Design docs and posts on running agents in production, newest first. Coming soon.

### Background

Tech Lead, Recommendations at Flipkart · Cofounder & CTO at Jellybean · Bing Ads AdQuality at Microsoft · Myntra · founding engineer at Evok Analytics (acquired by Walmart) · NIT Durgapur.

Bengaluru · [LinkedIn](https://www.linkedin.com/in/REPLACE_ME)
