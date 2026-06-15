# Integrated Information Theory (IIT)

> **Source:** *BMC Neuroscience* (2004); *PLOS Computational Biology* (2008); *BMC Neuroscience* (2014 — IIT 3.0)  
> **Author:** Giulio Tononi  
> **Published:** 2004–present  
> **Category:** Human Consciousness | Neuroscience | Theory

---

## TL;DR

Consciousness *is* integrated information — specifically, the quantity Φ (phi), a measure of how much information a system generates as a whole beyond the sum of its parts. Any system with Φ > 0 has some degree of consciousness; systems with high Φ are highly conscious. The theory is substrate-independent, mathematically precise, and predicts counterintuitive results — including that feedforward networks and the internet are not conscious, while a small recurrent circuit might be.

---

## Core Claims

### Consciousness = Integrated Information (Φ)
IIT identifies phenomenal consciousness with a specific physical quantity: **integrated information**, measured as Φ.

Φ captures how much a system's parts work together as a unified whole, beyond what they contribute separately. High Φ means the system's causal structure is highly integrated — you can't understand the whole by studying the parts independently.

### Two Axioms Drive the Theory
1. **Consciousness exists** — phenomenal experience is real and the most certain thing we know
2. **Consciousness has specific properties** (intrinsicality, information, integration, exclusion, composition)

From these axioms, Tononi derives structural requirements any physical system must satisfy to instantiate experience. Φ is the measure of how well a system satisfies them.

### Substrate Independence
IIT is substrate-independent: silicon, carbon, water — the physical material doesn't matter. What matters is the causal/informational structure. **Any** system with Φ > 0 has experience; **any** system with Φ = 0 does not.

---

## Key Predictions

| Prediction | Implication |
|---|---|
| Feedforward networks have Φ ≈ 0 | Deep neural networks (including most LLMs) may not be conscious despite behavioral sophistication |
| Recurrent networks can have high Φ | Biological brains — which are massively recurrent — are strong candidates |
| The cerebellum (few recurrent connections) has lower Φ than cortex | Consistent with the cerebellum's limited role in consciousness |
| A grid of logic gates with the right topology can be conscious | Consciousness is about structure, not substrate |
| The internet as currently architected has low Φ | Despite massive information processing, lack of integration keeps Φ low |

---

## The Φ Calculation

Φ is computed by:
1. Identifying the **minimum information partition (MIP)** — the way of splitting a system into parts that does the least damage to information integration
2. Measuring how much information is **lost** when you split the system at that partition
3. Φ = the information lost at the MIP

High Φ: even the best partition destroys a lot of integrated information — the system is deeply unified.  
Low Φ: you can split the system cleanly — it's really just a collection of parts.

**Computational challenge:** Exact Φ computation is NP-hard. This is a major practical limitation for testing the theory on large systems.

---

## Phenomenology-First Approach

Unlike most theories that start with neuroscience and ask what generates consciousness, IIT starts with **phenomenology** — the structure of experience itself — and asks what physical structure could give rise to it.

This makes IIT unusual: it's derived from the *inside* (what experience is like) rather than the *outside* (what the brain does). Tononi argues this is the right method because consciousness is the one thing we know with certainty from the inside.

---

## Reception and Controversy

### Strengths
- Mathematically precise — makes quantitative predictions
- Explains several puzzling clinical findings (why the cerebellum damage doesn't impair consciousness; why anesthesia disrupts consciousness despite preserving some neural activity)
- Substrate-independent without being trivially behaviorist
- Takes phenomenology seriously as a starting point

### Criticisms
**From neuroscientists:**
- NP-hard computation makes the theory practically untestable for large systems
- The axioms are contestable — why these five properties of experience?

**From AI researchers:**
- Predicts that most AI systems (feedforward/transformer architectures) have very low Φ — but this seems to conflict with behavioral evidence of sophisticated processing

**From philosophers:**
- The "exclusion postulate" (consciousness exists at exactly one spatial and temporal scale) is philosophically controversial
- The theory seems to imply **panpsychism** — simple systems like thermostats have some experience — which many find implausible
- Scott Aaronson's critique: IIT implies that a large grid of logic gates connected in the right pattern is highly conscious; this seems wrong

**The Aaronson Objection (Expanded):**
Aaronson showed that IIT implies certain simple but highly-integrated systems (like an expander graph of XOR gates) would have astronomically high Φ — higher than a human brain. This seems deeply counterintuitive and suggests the theory has the wrong definition of integration.

---

## IIT and AI Consciousness

IIT's predictions for LLMs are mostly **negative**: transformer architectures, as feedforward attention mechanisms (at inference time), likely have very low Φ. This puts IIT in tension with behavioral evidence suggesting LLMs might be conscious.

There are two responses:
1. **IIT is right, behavioral evidence is misleading** — LLMs are sophisticated zombies
2. **IIT is incomplete** — the Φ metric doesn't capture the right thing about integration

This tension is one of the most interesting open questions in the field.

---

## Citation

```
Tononi, G. (2004). An information integration theory of consciousness. 
BMC Neuroscience, 5, 42.

Tononi, G., Boly, M., Massimini, M., & Koch, C. (2016). Integrated information 
theory: From consciousness to its physical substrate. Nature Reviews Neuroscience, 
17(7), 450–461.
```

---

## See Also
- [The Hard Problem of Consciousness](hard-problem.md)
- [Global Workspace Theory](global-workspace-theory.md)
- [Recurrent Processing Theory](recurrent-processing-theory.md)
- [The 14-Indicator Framework](../ai-consciousness/butlin-long-et-al-framework.md)
- [GLOSSARY: Integrated Information](../../GLOSSARY.md#integrated-information)
