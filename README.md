# Greg .. 6 Distribution Strategies Running in Your Terminal

Most founders build great products and then wonder why nobody knows. Greg runs 6 distribution strategies in parallel.. the same playbook Greg Isenberg uses to build audience-first businesses.

Built on Isenberg's distribution-first approach. Adapted for Claude Code.

## What Happens When You Run It

```
Greg Distribution Advisor -- 2026-04-09

1. MCP Servers      [##########..........] 50%
2. Programmatic SEO [####................] 20%
3. Free Tools       [############........] 60%
4. AEO              [########............] 40%
5. User Brag        [##############......] 70%
6. Content Engine   [################....] 80%

TODAY'S FOCUS: S3 (Ship Sales Call Scorecard tool) + S5 (member win artifact)
YESTERDAY'S RESULTS: S6 repurposed podcast ep #41 into 17 pieces
STALLED: None
```

This is real output from Strategy Sprints, where Greg runs daily alongside 14 other AI advisors managing sales, strategy, partnerships, health, and investing.

## The 6 Strategies

Every run reads your data, updates the scorecard, and delegates to strategy agents:

| # | Strategy | What It Does |
|---|----------|-------------|
| 1 | MCP Servers | AI agents that sell for you 24/7 |
| 2 | Programmatic SEO | Keyword-targeted pages at scale |
| 3 | Free Tools | Email-gated tools as top of funnel |
| 4 | AEO | Get cited by AI search engines |
| 5 | User Brag | Turn member wins into shareable artifacts |
| 6 | Content Repurposing | One recording becomes 15+ pieces |

## How It Works

Greg is a **pure strategist**. He reads results, updates the scorecard, designs experiments, and delegates to 6 specialized agents via task files. He does not build or publish anything himself.

The daily loop:

```
Greg reads results
  -> updates scorecard
  -> assesses priorities (1-3 strategies per day, not all 6)
  -> writes task files to queue/
  -> strategy agents execute
  -> results appear in done/
  -> Greg reads results next morning
```

Each strategy has its own agent:

- `greg-s1-mcp` .. builds MCP servers, publishes to npm
- `greg-s2-seo` .. generates keyword-targeted pages, deploys to GitHub Pages
- `greg-s3-tools` .. builds single-page HTML tools with email gates
- `greg-s4-aeo` .. writes FAQ content with JSON-LD schema for AI citation
- `greg-s5-brag` .. builds shareable HTML artifact cards from member wins
- `greg-s6-repurpose` .. full content pipeline from raw recording to published everywhere

## Install in 2 Minutes

```bash
# 1. Copy the skill
cp greg-advisor.md ~/.claude/commands/greg-advisor.md

# 2. Add your API keys
cp .env.example ~/.claude/.env
# Edit with your Notion token + Discord webhook

# 3. Run
/greg-advisor
```

Greg works best with Notion (content pipeline), Discord (notifications), and Google Analytics (AI referral tracking). Obsidian is used for task queue and scorecard storage.

## Stalled Strategy Alerts

If any strategy stays RED for 2+ weeks, Greg automatically escalates:

```
GREG ESCALATION: Strategy 2 (Programmatic SEO) has been RED for 3 weeks.
Proposal: Kill the "best CRM for X" pattern. Switch to
"how to X without Y" comparison pages. Deploy 50 test pages by Friday.
```

No strategy drifts silently. Every run checks for stalled work and proposes a fix.

## Part of a 15-Advisor Board

Greg is one piece of a full AI operations system. The advisors that founders use most:

| Advisor | What It Does | Repo |
|---------|-------------|------|
| **Anthony** | Scores your sales calls, coaches daily | [anthony-sales](https://github.com/SimonTheSalesBooster/anthony-sales) |
| **Richard** | Audits your strategy against Rumelt's kernel | [richard-strategy](https://github.com/SimonTheSalesBooster/richard-strategy) |
| **Jay** | $21B growth playbook, partnership intelligence | [jay-advisor](https://github.com/SimonTheSalesBooster/jay-advisor) |
| **Boris** | Fractional CTO.. stack health, cost audit | [boris-technical](https://github.com/SimonTheSalesBooster/boris-technical) |
| **Edge** | Options income.. probability-based, boring, profitable | [edge-trading](https://github.com/SimonTheSalesBooster/edge-trading) |

[See all 15 advisors](https://github.com/SimonTheSalesBooster/board-of-advisors)

## The Full System

These advisors run autonomously inside **Strategy Sprints**.. a 90-day operating system for B2B founders.

One client grew revenue 130% in 90 days (144x ROI on a $9K/month engagement). 254 founders run a lighter version through Sprint Club at $49/month.

Curious what Greg would find for your distribution? [Book a coffee with Simon](https://calendly.com/simonseverino/coffee-with-simon) and we'll run it live.

---

Built by [Simon Severino](https://www.youtube.com/@TheSalesShow) with [Claude Code](https://claude.ai/code).
