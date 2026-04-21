# Jelly-Research Agents

> 6 ready-to-use agent templates for the Jelly-Research multi-tool research AI agent.

**GitHub:** [github.com/jelly-chain/jelly-research-agents](https://github.com/jelly-chain/jelly-research-agents)

Each agent is a pre-configured Claude Code sub-agent you can summon with the `/agent` command. Agents come pre-loaded with the right skills, workflows, and behavior guidelines for specific research tasks.

---

## Install all agents

```bash
bash install-all.sh       # Mac / Linux
.\install-all.ps1         # Windows PowerShell
```

## Install one agent

```bash
cp agents/deep-researcher/agent.md ~/.claude/agents/deep-researcher.md
```

## Use an agent

Inside Claude Code:
```
/agent deep-researcher
/agent competitive-intel
/agent fact-checker
```

---

## Agent list (6 agents)

| Agent | Description |
|-------|-------------|
| `deep-researcher` | Multi-step research chains with Perplexity + Exa + Firecrawl producing comprehensive reports |
| `news-monitor` | Real-time news tracking, daily briefings, and keyword monitoring |
| `fact-checker` | Verify claims with TRUE/FALSE/MISLEADING/UNVERIFIABLE verdicts and source citations |
| `serp-analyst` | Analyse Google SERP results, features, and ranking page content |
| `competitive-intel` | Competitor profiles, market maps, and company tracking |
| `web-scraper` | Scrape, crawl, and extract structured data from any website |

---

## License

MIT
