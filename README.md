# 🥊 Awesome LLM Debates

A curated collection of edge-case prompts, logic puzzles, and multi-domain debates where single frontier models confidently hallucinate or fail, but **multi-model adversarial debates** successfully resolve the conflict and reach a stable consensus.

## 🤔 Why Multi-Model Debate?

Single-model evaluation is inherently flawed. If a model generates a hallucination, asking that same model to "double-check its work" often results in it just confirming its own bias. 

By forcing models to act as adversarial peers—where multiple models critique, refine, and judge each other's outputs across several rounds—we can programmatically surface a robust consensus without human intervention.

## 📂 The Live Debate Archive

Below is the live catalog of model consensus trials. Each assembly tracks the dynamic shifting of model viewpoints over multiple rounds until the debate seals.

*All transcripts are live-generated and hosted via [Debate](https://debate.tellodb.com/).*

| Topic / Debate Prompt | Mode | Metrics | The Consensus Transcript |
| :--- | :---: | :---: | :--- |
| **Creative Integrity vs. Commercial Sequels**<br>Should Pixar continue making sequels like Toy Story 5, or focus on original stories to preserve creative integrity? | Refinement | 38% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/60acd1c844ca1b2167f9106c51196a17) |
| **Game Development Cycle Timing**<br>Was Rockstar Games right to delay GTA 6 again for polish, or should they prioritize faster releases to meet fan expectations? | Refinement | 35% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/c90b7f87a4bfdadf04f024f7b98b2b64) |
| **AI Infrastructure Competitiveness**<br>Is Amazon’s move to sell Trainium AI chips a healthy challenge to Nvidia’s dominance, or another sign of wasteful fragmentation? | Refinement | 64% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/a73bd59dd426dbac8ae8270498a3a635) |
| **Sovereign Supply Chains & Onshoring**<br>Is the Apple-Intel domestic chip collaboration announced by Trump a smart boost for US manufacturing, or just political theater? | Refinement | 83% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/7425c4fde9d118757eb01440cbb606fa) |
| **Macro Economics of AI Capability R&D**<br>Does AI development, like high burn rates at OpenAI ($3.7B in Q1 2026), represent unsustainable hype, or necessary spending? | Refinement | 75% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/ec260fc15623c438cb0117cb7af69dbd) |
| **Venture Capital Saturation**<br>Is the AI boom creating a massive bubble that will burst soon, or are current investments in OpenAI and Anthropic justified? | Refinement | 40% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/7d1c689237d22c56060425ff4d1478fc) |
| **Tournament Format Expansion**<br>Does the expanded 48-team FIFA World Cup format improve global inclusivity, or does it dilute the tournament's quality? | Devil's Advocate | 40% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/d3353d14a4a7966a436eadbeccd02c39) |
| **Fairness Allocation in Global Athletics**<br>How fairly are underdog teams (e.g., Ghana, Uzbekistan, Panama) treated in scheduling and refereeing during the group stage? | Refinement | 50% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/0b077d28124246ef4825fdad0fbf5d1e) |
| **Geopolitical Incentive Structuring**<br>Should the US provide sanctions relief to Iran in exchange for nuclear limits and reopening the Strait of Hormuz? | Refinement | 80% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/cf88fb16f184764deab1377f93826f08) |
| **Labor Economics & Automation Policy**<br>Should the US federal government guarantee every adult a basic income once AI displaces 15% of jobs? | Refinement | 42% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/c28303b338c38c57a3a904104c186817) |
| **Scientific Protocol Integrity**<br>Should AI-generated content be banned from academic peer review entirely? | Refinement | 81% consensus<br>1 round | [Read Assembly ↗](https://debate.tellodb.com/share/e50f96a00cc49fe13e0cd6b369255464) |
| **The Shift In Standard Work Frameworks**<br>Is the 40-hour work week obsolete in 2026, or more necessary than ever? | Refinement | 88% consensus<br>3 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/d855e8fe1c5a4c78aed36384f4a35f8c) |
| **Game-Theoretic Mechanics of Hiring**<br>Is AI job apply inevitable these days when everyone is doing it and you don't have advantage now? | Refinement | 86% consensus<br>2 rounds | [Read Assembly ↗](https://debate.tellodb.com/share/ec88cc55cb584ea5b4d8c2e3ee4c6412) |

## ⚙️ How It Works Under the Hood

The platform handles the coordination overhead of running complex multi-model validation pipelines automatically:
1. **Persona Orchestration:** Splitting LLM calls into dedicated roles (e.g., *Generator*, *Critic*, *Devil's Advocate*, *Judge*).
2. **Multi-Turn Convergence:** Running multi-turn temporal interaction loops until consensus metrics stabilize or a hard max round boundary is met.
3. **Evaluation Signatures:** Exporting deterministic execution transcripts (`/share/[uuid]`) to verify AI evaluation processes.

## 🤝 Contributing

Got a hard multi-token logic puzzle, code syntax mismatch, or policy prompt that single models choke on?
1. Toss it into the [Debate Engine](https://debate.tellodb.com/).
2. Submit a Pull Request inserting your sealed share link into our archive table!

---
**License:** MIT
