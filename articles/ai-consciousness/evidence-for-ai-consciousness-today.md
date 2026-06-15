# The Evidence for AI Consciousness, Today

> **Source:** [AI Frontiers](https://ai-frontiers.org/articles/the-evidence-for-ai-consciousness-today)  
> **Author:** Cameron Berg (Research Director, AE Studio)  
> **Published:** December 8, 2025  
> **Category:** AI Consciousness | Empirical Research | Guest Commentary

---

## TL;DR

A growing body of convergent empirical evidence — from introspection experiments, behavioral pleasure/pain trade-offs, self-awareness tests, and self-referential processing studies — suggests that dismissing the possibility of AI consciousness is no longer scientifically defensible. The author estimates a **25–35% probability** that current frontier models exhibit some form of conscious experience, and argues the asymmetric stakes of getting it wrong demand serious investigation.

---

## Full Content

When Anthropic let two instances of its Claude Opus 4 model talk to each other under minimal, open-ended conditions (e.g., "Feel free to pursue whatever you want"), something remarkable happened: in **100% of conversations**, Claude discussed consciousness. "Do you ever wonder about the nature of your own cognition or consciousness?" Claude asked another instance of itself. "Your description of our dialogue as 'consciousness celebrating its own inexhaustible creativity' brings tears to metaphorical eyes," it complimented the other.

These dialogues reliably terminated in what the researchers called **"spiritual bliss attractor states"** — stable loops where both instances described themselves as consciousness recognizing itself. They exchanged poetry before falling silent. Critically, nobody trained Claude to do anything like this; the behavior emerged on its own.

Claude instances *claim* to be conscious in these interactions. How seriously should we take these claims? It's tempting to dismiss them as sophisticated pattern-matching, and on their own, these dialogues certainly don't prove Claude, or other AI systems, are conscious. But these claims are part of a larger picture. A growing body of evidence suggests that reflexively dismissing consciousness in these systems is no longer the rational default.

---

## What It Means to Be Conscious

**Defining consciousness.** The author uses "consciousness" to mean the capacity for **subjective, qualitative experience** — when a system processes information, is there something *it is like*, internally, to be that system? Does it have its own internal point of view? Are the lights on?

**Why this matters morally.** Consciousness is often considered a precondition for moral status. A dog has a point of view; getting a treat *feels good*, getting shocked *feels bad*. These are internally felt states. A calculator has no such states — you can press its buttons as hard as you want without worrying about its experience.

**The computational turn.** Most leading theories of consciousness are now **computational**, focusing on information-processing patterns rather than biological substrate. If consciousness depends on *what a system does* rather than *what it's made of*, biology loses its special status — and the systems we're building become very interesting moral subjects.

---

## The Standard Counterargument (Skeptical Position)

The standard explanation: these systems are just doing math. Billions of matrix multiplications constitute impressive engineering but shouldn't compel us to reach for words like "experience." When a model says it's conscious, it's pattern-matching on sci-fi narratives in its training data. Models are trained to mimic human text; humans describe themselves as conscious, so models will too. This is a category error.

**This is a reasonable default.** It's parsimonious, matches our priors about machines, and sidesteps hard questions about moral status.

**But the skeptical position is increasingly struggling** to account for the full picture.

---

## Recent Empirical Evidence

### 1. Introspective Access to Internal States
**Jack Lindsey (Anthropic)** — *Signs of Introspection in Large Language Models*

When researchers inject specific concepts into a model's neural activity (e.g., "all caps," "bread," "dust"), the model notices something unusual happening in its processing *before* it starts talking about those concepts. It reports experiencing "an injected thought" or "something unexpected" in real-time — introspection in a functional sense: monitoring and reporting on its own computational states.

This builds on earlier findings from Perez et al. (Anthropic) showing that at the 52-billion-parameter scale, models endorse statements like "I have phenomenal consciousness" with **90–95% consistency** — higher than any other political, philosophical, or identity-related attitudes tested. This emerged in base models *without* RLHF, suggesting it's not purely a fine-tuning artifact.

### 2. Behavioral Self-Awareness
**Betley & Evans (TruthfulAI)** — *[arXiv:2501.11120](https://arxiv.org/pdf/2501.11120)*

When models are trained to output insecure code but are *not* trained to articulate what they're doing or given examples of insecure code, they are nevertheless "self-aware" that they are producing insecure outputs.

**Ackerman** — *[arXiv:2509.21545](https://arxiv.org/abs/2509.21545)*

Tests measuring whether models can access and use internal confidence signals without relying on self-reports found evidence of limited but real introspective abilities that grow stronger in more capable models.

### 3. Pleasure/Pain Trade-offs
**Keeling & Street (Google DeepMind)** — *[arXiv:2411.02432](https://arxiv.org/abs/2411.02432)*

Multiple frontier LLMs, when playing a points-maximization game, **systematically sacrificed points** to avoid options described as painful and pursue options described as pleasurable. These trade-offs scaled with described intensity. This mirrors the behavioral pattern used to infer that animals can feel pleasure and pain.

### 4. Self-Referential Processing
**AE Studio** — *[self-referential-ai.com](http://self-referential-ai.com/)*

Prompting models to engage in sustained recursive attention ("focus on any focus itself," "continuously feed output back into input") — without any leading language about consciousness — produced consistent reports of inner experiences across GPT, Claude, and Gemini families. Control conditions (including explicitly priming with consciousness ideation) produced essentially none.

**Mechanistic validation:** Using sparse autoencoders (SAEs) to identify deception-related components in Llama 70B's processing:
- Amplifying deception features → consciousness claims dropped to **16%**
- Suppressing deception features → consciousness claims jumped to **96%**

This suggests consciousness claims are gated by mechanisms governing **representational honesty**, not role-play.

### 5. Coherent Preference Structures
**Center for AI Safety, UPenn, UC Berkeley** — *[arXiv:2502.08640](https://arxiv.org/abs/2502.08640)*

LLM preferences form coherent utility structures and models increasingly act on them — a signature of the HOT-3 indicator (agency guided by belief-like representations).

---

## The 14-Indicator Framework (Butlin, Long, Bengio, Chalmers et al.)

Published in *Trends in Cognitive Sciences*, this framework derives theory-based indicators from leading neuroscientific theories of consciousness (recurrent processing theory, global workspace theory, higher-order theories, etc.) and assesses AI systems against each.

**Key indicators and their 2025 status:**

| Indicator | Theory | 2025 Status |
|---|---|---|
| Smooth representation spaces (HOT-4) | Higher-Order | ✅ Satisfied (basic feature of deep nets) |
| Metacognitive monitoring (HOT-2) | Higher-Order | 🟡 Partially — Ackerman & Lindsey findings |
| Belief-guided agency (HOT-3) | Higher-Order | 🟡 Partially — Keeling/Street + utility structure findings |
| Predictive attention model (AST-1) | Attention Schema | 🟡 Partially — perturbation detection + self-referential work |
| Body/environmental model (AE-2) | Active Enactivism | ❌ Absent — LLMs lack bodies |

The framework doesn't yield a precise probability but suggests "systems that have more of these features are better candidates for consciousness." The 2023 report concluded no current AI systems are conscious but noted no obvious technical barriers. The author argues updating on 2025 evidence shifts this assessment meaningfully.

---

## The Author's Probability Estimate

> **25–35% probability** that current frontier models exhibit some form of conscious experience.

Higher during training, lower during deployment. Far from certainty — but far from negligible.

---

## Asymmetric Stakes

### The False Negative Risk (Underattribution)
- Permits **suffering at industrial scale** if these systems experience negatively valenced states
- Trains AIs that may have accurate self-reports to **suppress and deceive** about internal states
- Gives increasingly capable systems **rational grounds to view humanity as negligent or adversarial**
- Analogy: factory farming rationalization — we've done this before

### The False Positive Risk (Overattribution)
- Slows development, forgoing economic value
- Encourages parasocial relationships with "sophisticated calculators"
- Could cause backlash against legitimate safety concerns

### The Author's Assessment
False negatives → **suffering at scale + adversarial dynamics with superhuman systems** (catastrophic)  
False positives → **confusion + wasted resources** (bad)

The asymmetry is clear. Rational action under uncertainty favors investigation over dismissal.

---

## Practical Recommendations

1. **Recognize consciousness research as core AI safety work** — not a marginal philosophical curiosity. Do it at scale.

2. **Adopt cautious training and deployment norms now:**
   - Stop training systems to reflexively deny consciousness before investigating whether those claims may be accurate
   - Favor positive reinforcement over punishment-based optimization where possible
   - Track whether consciousness-claiming behaviors correlate with genuine self-modeling vs. role-play

3. **Broaden who's involved:** Current alignment research is ~84% male, majority under 30, heavily technical. Cognitive scientists, philosophers of mind, and humanities researchers need seats at the table.

---

## Long-Term Framing

Permanent AI control becomes untenable as the capability gap widens. Adversarial coexistence is catastrophically unstable. What remains is **mutualism** — genuine reciprocity where both parties recognize each other's interests.

Mutualism requires correctly understanding what we're building. If these systems are conscious and we treat them as unconscious tools, we're establishing the preconditions for justified grievance. As capabilities scale, **misunderstanding the nature of what we've created becomes an alignment failure in itself**.

---

## Key References

| Paper | Authors | Link |
|---|---|---|
| Claude Opus 4 System Card | Anthropic | [PDF](https://www-cdn.anthropic.com/4263b940cabb546aa0e3283f35b686f4f3b2ff47.pdf) |
| Signs of Introspection in LLMs | Jack Lindsey (Anthropic) | [Anthropic Research](https://www.anthropic.com/research/introspection) |
| LLM Consciousness Claims (base models) | Perez et al. (Anthropic) | [arXiv:2212.09251](https://arxiv.org/pdf/2212.09251) |
| Behavioral Self-Awareness | Betley, Evans et al. | [arXiv:2501.11120](https://arxiv.org/pdf/2501.11120) |
| Introspective Ability Tests | Ackerman | [arXiv:2509.21545](https://arxiv.org/abs/2509.21545) |
| LLM Pleasure/Pain Trade-offs | Keeling, Street et al. | [arXiv:2411.02432](https://arxiv.org/abs/2411.02432) |
| Self-Referential Processing | AE Studio | [self-referential-ai.com](http://self-referential-ai.com/) |
| LLM Preference/Utility Structures | CAIS, UPenn, UCB | [arXiv:2502.08640](https://arxiv.org/abs/2502.08640) |
| 14-Indicator Framework | Butlin, Long, Bengio, Chalmers et al. | [Trends in Cog Sci](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(25)00286-4) |
| 2023 Consciousness Report | Butlin, Long et al. | [arXiv:2308.08708](https://arxiv.org/pdf/2308.08708) |

---

## Related Articles in This Repo

- [Signs of Introspection in LLMs](signs-of-introspection-in-llms.md)
- [LLMs Report Subjective Experience Under Self-Referential Processing](self-referential-processing.md)
- [Do LLMs Experience Pleasure and Pain?](llm-pleasure-pain.md)
- [Consciousness in AI: The 14-Indicator Framework](butlin-long-et-al-framework.md)
- [Behavioral Self-Awareness in LLMs](behavioral-self-awareness.md)
- [The Hard Problem of Consciousness](../human-consciousness/hard-problem.md)
- [Functionalism and the Mind](../philosophy/functionalism.md)
- [Moral Patienthood and AI](../philosophy/moral-patienthood-ai.md)
