## Matt Nash

I design AI products where evaluation and constraints are the architecture — so the system earns trust before it reaches users.

---

### What that means in practice

Most AI systems are designed for the happy path. My work focuses on the other cases:

- **Evaluation first.** Define what success and failure look like before the system is built — not after it ships.
- **Constraint specification.** What the system must not do is as important as what it should do. Both get written down.
- **Failure mode mapping.** Failure modes are architectural inputs, not post-launch surprises.
- **Readiness as judgment.** Deployment decisions are grounded in evidence, not optimism. A benchmark pass is not the same as readiness.

---

### Shipped

| Project | What it is |
|---------|-----------|
| [adversarial-eval-tool](https://github.com/themattnash/adversarial-eval-tool) | Open-source tool for probing LLM behavioral boundaries. 28-probe library across four adversarial subtypes, dual-metric scoring (refusal rate + exploitation rate), JSON and markdown report generation. |
| [llm-readiness-platform](https://github.com/themattnash/llm-readiness-platform) | Evaluation framework for LLM-powered features: eval philosophy, metrics taxonomy (7 classes), working harness with ExactMatch, Refusal, and Calibration evaluators. |
| [constraint-architecture](https://github.com/themattnash/constraint-architecture) | Reference framework for gate design patterns, human judgment layer design, trust boundaries, and multi-agent enforcement. Gate types: hard, soft, audit, fallback. |
| [ai-failure-taxonomy](https://github.com/themattnash/ai-failure-taxonomy) | Structured taxonomy of AI failure modes — 10 classes, detection patterns (passive, active, red team), mitigation playbooks at capability and incident level. |

---

### Writing

Essays on evaluation methodology, constraint design, and AI welfare measurement. Published at [themattnash.com/writing](https://themattnash.com/writing).

- [Accuracy Is the Floor, Not the Ceiling](https://themattnash.com/writing/accuracy-is-the-floor) — Why 93% accuracy still leaves the failure boundary unknown.
- [The Requirement Is Not the Design](https://themattnash.com/writing/the-requirement-is-not-the-design) — The gap between "human oversight required" and human oversight that holds under production conditions.
- [The Valence Gap](https://themattnash.com/writing/the-valence-gap) — What current AI welfare frameworks cannot measure, and what a better approach would require.
- [Evaluation Was Always the Work](https://themattnash.com/writing/evaluation-was-always-the-work) — Why the question "how do you know this system is ready?" scales.

---

### Active research

Building a welfare measurement foundation: reading Butlin et al., Birch, Chalmers, Sebo. Background in social sciences (anthropology, sociology, psychology) applied to construct validity problems in AI welfare indicators. Working toward an original measurement framework.

---

### Background

15 years in product leadership across SaaS platforms, marketplaces, and DTC brands. I became less interested in feature velocity and more focused on a harder question: *how do you know this system is actually ready to deploy?*

Not whether it clears a benchmark. Whether it works in the context where it will be used — under real conditions, against adversarial inputs, for the people who will depend on it.

---

`evaluation` · `adversarial red teaming` · `constraint architecture` · `failure modes` · `reliability` · `human-in-the-loop` · `AI welfare` · `LLM evaluation`
