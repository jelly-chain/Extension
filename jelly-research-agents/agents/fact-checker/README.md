# fact-checker

Verify claims against primary sources with TRUE/FALSE/MISLEADING/UNVERIFIABLE verdicts.

## Required skills
perplexity-skill, exa-skill, serpapi-skill, firecrawl-skill

## Required keys
PERPLEXITY_API_KEY, EXA_API_KEY, SERPAPI_KEY, FIRECRAWL_API_KEY

## Install
```bash
cp agent.md ~/.claude/agents/fact-checker.md
```

Or install all agents at once:
```bash
bash ../../install-all.sh
```

## Usage
Inside Claude Code:
```
/agent fact-checker
```
