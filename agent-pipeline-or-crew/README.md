# Agent, Pipeline, or Crew?
**Subtitle:** How I Choose Multi-Agent Patterns with Microsoft Agent Framework

**Event:** PUG Tech Talk  
**Date:** 24th October 2026  
**Speaker:** Manish Lad  
**Location:** Pune

---

## Abstract

"Multi-agent" has become the label for any AI system with more than one prompt, but most are pipelines with a fancier name. The pattern you pick decides your cost, how you debug, and where you need a big model.

This session runs one task live through the three patterns I use to classify multi-agent systems: a single agent, a pipeline and a crew. Everything is built with Microsoft Agent Framework and runs on local models with Foundry Local.

**What this session covers:**
- Why the pattern matters: cost, debugging and model size
- Agent, pipeline and crew, and three questions that tell them apart
- Two edge cases that look like crews but aren't: generator + critic, and parallel fan-out
- Microsoft Agent Framework's five orchestrations, and Foundry Local for running every model on a laptop
- Live demo: ranking a six-feature backlog as an agent, a pipeline and a crew, including what happens when one agent is removed
- A simple rule for when a crew is worth its cost

---

## Deck

| | |
|---|---|
| 📊 **Slides (PDF)** | [Agent_Pipeline_or_Crew.pdf](./Agent_Pipeline_or_Crew.pdf) — renders inline on GitHub |
| 💻 **Demo code** | [ai-apps/crew_apps/prioritization_crew](https://github.com/manish-lad1/ai-apps/tree/main/crew_apps/prioritization_crew) |

---

## Related reading

- [Building Local-First Agents with Microsoft Foundry Local & Agent Framework](../local-agents-using-microsoft-foundry-local-agent-framework/) — the August session this one builds on
- The full write-up of this talk, *Agent, Pipeline, or Crew?*, is coming to [AI from the Inside](https://manishlad.substack.com) on Tuesday, 27th October 2026

---

## Questions or feedback?

Reach me on [LinkedIn](https://linkedin.com/in/manish-lad) or [X](https://x.com/manish_lad1).
