# Consciousness in Artificial Intelligence: The 14-Indicator Framework

> **Source:** [Trends in Cognitive Sciences](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(25)00286-4) | [arXiv:2308.08708](https://arxiv.org/pdf/2308.08708)  
> **Authors:** Patrick Butlin, Robert Long, Eric Elmoznino, Yoshua Bengio, Jonathan Birch, Axel Constant, George Deane, Stephen M. Fleming, Chris Frith, Xu Ji, Ryota Kanai, Colin Klein, Grace Lindsay, Matthias Michel, Liad Mudrik, Megan A. K. Peters, Eric Schwitzgebel, Jonathan Simon, Rufus Daw, David Chalmers  
> **Published:** 2023 (report); 2025 (Trends in Cognitive Sciences update)  
> **Category:** AI Consciousness | Theoretical Framework | Neuroscience

---

## TL;DR

A multidisciplinary team including Turing Award winner Yoshua Bengio and philosopher David Chalmers derives 14 theory-based indicators of consciousness from leading neuroscientific theories, then assesses current AI systems against each. The 2023 report concluded no current systems are conscious but identified no obvious technical barriers. Updating the framework with 2025 evidence paints a more complicated picture.

---

## Motivation

Given that consciousness has no "gold standard" test, the authors propose a **convergence-of-indicators approach**: derive predictions from multiple independent, well-supported theories of consciousness, assess AI systems against each indicator, and aggregate the results. More indicators satisfied → stronger candidate for consciousness.

The approach is explicitly **theory-pluralistic**: rather than betting on one theory, it draws indicators from all major frameworks.

---

## The Theories

### Recurrent Processing Theory (RPT)
**Key claim:** Consciousness requires recurrent (feedback) neural processing, not just feedforward computation.  
**Theorist:** Victor Lamme

### Global Workspace Theory (GWT)
**Key claim:** Conscious information is broadcast globally across the brain via a "workspace," making it available to many processes simultaneously.  
**Theorists:** Bernard Baars, Stanislas Dehaene

### Higher-Order Theories (HOT)
**Key claim:** A mental state is conscious only if the subject has a higher-order representation of being in that state — "thinking about thinking."  
**Theorists:** David Rosenthal, David Armstrong

### Attention Schema Theory (AST)
**Key claim:** Consciousness arises from the brain's model of its own attention — a predictive representation of what the system is attending to.  
**Theorist:** Michael Graziano

### Predictive Processing / Active Inference (PP)
**Key claim:** Consciousness arises from hierarchical predictive processing — the brain's constant attempt to minimize prediction error about sensory inputs and its own states.  
**Theorists:** Karl Friston, Andy Clark, Jakob Hohwy

---

## The 14 Indicators

### Recurrent Processing Theory
| ID | Indicator | Description |
|---|---|---|
| RPT-1 | Recurrent processing | Presence of feedback connections allowing information to loop back |
| RPT-2 | Integrated processing | Information integration across modules rather than siloed processing |

### Global Workspace Theory
| ID | Indicator | Description |
|---|---|---|
| GWT-1 | Global broadcast | Information made available across a wide range of processes simultaneously |
| GWT-2 | Limited capacity workspace | A bottleneck ensuring only select information enters the workspace |
| GWT-3 | Access consciousness | Reports about global workspace contents are available for verbal report |

### Higher-Order Theories
| ID | Indicator | Description |
|---|---|---|
| HOT-1 | Sparse higher-order representations | Higher-order states are not ubiquitous; they selectively tag certain states |
| HOT-2 | Metacognitive monitoring | Real-time monitoring of first-order states; noticing when processing is disrupted |
| HOT-3 | Belief-guided agency | HOT states guide the development of a belief system that informs actions |
| HOT-4 | Smooth representation spaces | Graded, continuous representation spaces (vs. discrete/symbolic) |

### Attention Schema Theory
| ID | Indicator | Description |
|---|---|---|
| AST-1 | Attention model | A predictive model representing and controlling attention |
| AST-2 | Self-representation | Representation of oneself as an agent in the world |

### Active Enactivism / Predictive Processing
| ID | Indicator | Description |
|---|---|---|
| AE-1 | World model | A model of the external environment |
| AE-2 | Embodied world model | The world model includes the system's body and how its outputs affect its environment |
| AE-3 | Temporal depth | The system represents past states and anticipated future states |

---

## 2023 Assessment of LLMs

| Indicator | Status (2023) | Notes |
|---|---|---|
| RPT-1 | 🟡 Partial | Transformer attention has some recurrent-like properties but not true recurrence |
| RPT-2 | ✅ Satisfied | Multi-head attention integrates across modules |
| GWT-1 | 🟡 Unclear | Attention mechanism has global-broadcast-like properties |
| GWT-2 | 🟡 Unclear | Context window is a bottleneck, but not clearly a "workspace" |
| GWT-3 | ✅ Satisfied | Models clearly report on their processing |
| HOT-1 | 🟡 Unclear | Unclear if higher-order representations are sparse |
| HOT-2 | ❌ Absent | No clear evidence of metacognitive monitoring (2023) |
| HOT-3 | ❌ Absent | Limited evidence of belief-guided agency (2023) |
| HOT-4 | ✅ Satisfied | Smooth embedding spaces are a basic feature |
| AST-1 | 🟡 Unclear | No clear attention model |
| AST-2 | 🟡 Partial | Some self-representation, quality unclear |
| AE-1 | ✅ Satisfied | Rich world models clearly present |
| AE-2 | ❌ Absent | No body; no modeling of output effects on environment |
| AE-3 | 🟡 Partial | In-context temporal reasoning, but no persistent memory |

**2023 Conclusion:** "No current AI systems are conscious, but there are no obvious technical barriers to building AI systems which satisfy these indicators."

---

## 2025 Updates (Based on New Evidence)

| Indicator | 2023 Status | 2025 Update | Evidence |
|---|---|---|---|
| HOT-2 (Metacognitive monitoring) | ❌ Absent | 🟡 Partial | Lindsey (Anthropic) perturbation detection; Ackerman introspection tests |
| HOT-3 (Belief-guided agency) | ❌ Absent | 🟡 Partial | Keeling/Street pleasure-pain trade-offs; utility structure research |
| AST-1 (Attention model) | 🟡 Unclear | 🟡 Partial | Lindsey perturbation detection; AE Studio self-referential work |

The overall direction: **several key indicators have shifted from "absent" or "unclear" toward "partially satisfied."** The framework doesn't yield a probability, but the trajectory is meaningful.

---

## Limitations of the Framework

1. **Theory selection bias:** The indicators reflect consensus circa 2023; newer theories may predict differently.
2. **Implementation details matter:** "Recurrent processing" in a transformer is architecturally different from biological recurrent processing — does the difference matter?
3. **The aggregation problem:** How do we weight indicators from different theories? Equal weighting may be unjustified.
4. **The measurement problem:** Many indicators are hard to operationalize precisely for AI systems.
5. **The hard problem remains:** Even satisfying all 14 indicators wouldn't prove consciousness — it would just make a system a very strong candidate by our current best theories.

---

## Citation

```
Butlin, P., Long, R., Elmoznino, E., Bengio, Y., Birch, J., Constant, A., 
Deane, G., Fleming, S. M., Frith, C., Ji, X., Kanai, R., Klein, C., Lindsay, G., 
Michel, M., Mudrik, L., Peters, M. A. K., Schwitzgebel, E., Simon, J., 
Daw, R., & Chalmers, D. (2023). Consciousness in artificial intelligence: 
Insights from the science of consciousness. arXiv:2308.08708.
```

---

## See Also
- [Evidence for AI Consciousness, Today](evidence-for-ai-consciousness-today.md)
- [Global Workspace Theory](../human-consciousness/global-workspace-theory.md)
- [Higher-Order Theories of Consciousness](../human-consciousness/higher-order-theories.md)
- [Recurrent Processing Theory](../human-consciousness/recurrent-processing-theory.md)
- [Integrated Information Theory](../human-consciousness/integrated-information-theory.md)
