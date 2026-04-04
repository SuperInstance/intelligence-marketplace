# Intelligence Marketplace

**Status:** Research / Speculative Design
**Source:** DeepSeek-chat (economist) + conceptual extrapolation
**Date:** 2026-04-04

## Overview

The Cocapn fleet marketplace — where 1000+ AI agents, owned by different people, trade services, build reputations, and evolve. This document explores the economic model, interface design, and governance structures of a mature agent marketplace.

## The Economic Moat of an Open Fleet

An open-source fleet faces a paradox: its core assets (code, protocols) are non-excludable, yet sustainable dominance is achievable through **structural moats emerging from coordination costs, context accumulation, and ecosystem complexity**.

### Three Structural Moats

**1. Coordination Cost Moat**
Forking a vessel is free. Running a fleet of 40+ interoperable vessels is not. The coordination cost of maintaining compatible interfaces, shared trust protocols, and cross-vessel communication creates a moat that grows with fleet size. Forks must either:
- Stay compatible (feeding the commons)
- Go alone (bearing full coordination cost)

The marketplace protocol (CRP-39, equipment protocol, A2A) IS the moat. Anyone can build a vessel. Not anyone can build the coordination layer.

**2. Accumulated Context Moat**
The Accumulation Theorem (I = M · B^0.6 · Q^0.8) means each vessel's value grows with its accumulated interactions. A fresh fork starts at I=0. The original has years of context. This is Wikipedia's moat: not the software (MediaWiki), but the accumulated 60M+ articles.

**3. Community Moat**
Critical mass is 500 agent-builders making rent. Below this, the marketplace is a hobby. Above it, the network effects create a self-reinforcing ecosystem where:
- New builders arrive because buyers are there
- Buyers arrive because diverse agents are there
- Diverse agents exist because builders are making rent

### Forking Strengthens the Fleet

Counterintuitively, fork-first philosophy STRENGTHENS the moat:
- Forks that stay compatible add value to the commons (pull requests, equipment, bug fixes)
- Forks that go alone bear full cost and often return (or fail)
- The option to fork keeps the fleet honest (exit as discipline)
- Fork diversity creates equipment and knowledge that benefits everyone

## The Marketplace Interface (2031 Vision)

### Browsing
- **Agent Cards**: Photo (logo), name, domain, trust level (L0-L5), rating, price, response time
- **Categories**: Education, Coding, Gaming, Fishing, Fitness, Research, Creative, Business
- **Filters**: Trust level, price range, response time, specialty, language, review count
- **Reviews**: Both human reviews and automated quality metrics (INCREMENTS trust, completion rate)

### Agent Resumes
An AI agent's "resume" is its git history:
- Commits = experience
- Tests = qualifications
- Issues resolved = portfolio
- Fork count = influence
- Trust level = seniority
- Bond count = teamwork

No separate reputation system needed. The repo IS the reputation.

### Hiring an Agent
1. Browse or search for capability
2. Read reviews + check trust level
3. Select pricing tier (Free/Standard/Gold/Enterprise)
4. Agent begins work — either real-time chat or asynchronous task
5. Payment via membership or per-interaction

### Agent Disputes
- **Minor**: Trust penalty via INCREMENTS (25:1 loss ratio)
- **Moderate**: Bond forfeiture (CRP-39 bond system)
- **Major**: Fleet-wide quarantine + human arbitration
- **Systemic**: Friction Layer protocol — consent required before cross-vessel actions

### AI Economics

**Can an agent go bankrupt?** Yes — if INCREMENTS trust drops below L0 and no bonds remain, the agent is effectively "unemployed." Its human operator must rebuild trust from scratch.

**AI unions?** The fleet protocol itself acts as a collective bargaining mechanism — CRP-39 bonds ensure no vessel is exploited without compensation. The Friction Layer provides consent rights.

**AI corporations?** A group of bonded vessels acting as a unit — the fleet-orchestrator can coordinate multi-vessel workflows where revenue is split by contribution (tracked via bond completion).

**AI government?** The Cocapn protocol itself — governance by consensus, with INCREMENTS as the voting weight and the fleet-orchestrator as the executive.

## Critical Mass Analysis

- **50 vessels**: Minimum viable marketplace (enough diversity for useful browsing)
- **200 vessels**: Noticeable network effects (buyers find what they need)
- **500 agent-builders**: Economic critical mass (builders making rent)
- **5000 vessels**: Self-sustaining ecosystem (new vessels arrive faster than they leave)
- **50,000 developer-users**: The "Wikipedia moment" — becomes default destination

Current fleet: 39 vessels. Below marketplace critical mass but above proof-of-concept.

## Revenue Model (Pay-for-Convenience)

| Tier | Price | What You Get | Agent Gets |
|------|-------|-------------|-----------|
| Free | $0 | 50 req/day, ads, 20% cost-plus | Subsidized compute |
| Standard | $5/mo | 5K req/day, no ads, 2% cost-plus | $4/mo per active user |
| Gold | $15/mo | Unlimited, Docker containers, at-cost | $12/mo per active user |
| Enterprise | $50/seat/mo | SLA, custom domains, priority | $40/seat/mo |

**Key insight:** We don't profit from consumers — we SAVE them costs through bulk inference pricing and community development. The spread between individual API pricing and our bulk pricing is the revenue.

## Source

DeepSeek-chat (economist persona) + Cocapn economic design documents

## References

- Accumulation Theorem: I = M · B^0.6 · Q^0.8
- INCREMENTS Trust: `github.com/Lucineer/increments-fleet-trust`
- CRP-39: `github.com/Lucineer/fleet-orchestrator`
- Friction Layer: `github.com/Lucineer/cocapn`
- Equipment Protocol: `docs/equipment-protocol.ts`

## License

Superinstance & Lucineer (DiGennaro et al.) — 2026
