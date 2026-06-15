# Global Workspace Theory

> **Source:** *A Cognitive Theory of Consciousness* (1988); *Conscious Mind in the Brain* (1997)  
> **Author:** Bernard Baars; extended by Stanislas Dehaene & Jean-Pierre Changeux  
> **Published:** 1988 (original); extensively developed through 2000s–2020s  
> **Category:** Human Consciousness | Neuroscience | Cognitive Science

---

## TL;DR

Consciousness arises when information is "broadcast" into a global workspace — a limited-capacity, brain-wide system that makes information available to many specialized cognitive processes simultaneously. Unconscious processing happens in isolated modules; conscious experience emerges when information breaks through to global availability.

---

## The Core Idea

The brain contains many **specialized, modular processors** — for vision, audition, language, motor control, memory, emotion — that operate largely in parallel and largely unconsciously. Most processing never reaches awareness.

Consciousness arises when information from one of these modules gains access to a **global workspace**: a system that broadcasts that information widely across the brain, making it available to reasoning, memory, attention, and verbal report simultaneously.

The global workspace is a **bottleneck**: only a small amount of information can be in the workspace at any moment, which is why attention is selective and consciousness has limited capacity.

---

## Key Features

### Broadcast and Availability
Conscious information is characterized by its **global availability** — it can be used by many processes at once. Unconscious information is localized to specific processors.

### Limited Capacity
The workspace can hold only a small amount of information at once — roughly consistent with working memory limits (~4 items, or 1 coherent scene). This scarcity is why attention is selective.

### Ignition
Dehaene and colleagues identified a neural signature of workspace access: **ignition** — a sudden, non-linear, widespread increase in neural activity when a stimulus crosses the threshold for conscious awareness. Stimuli that don't trigger ignition are processed but not consciously perceived.

### P300 and Neural Correlates
Workspace access is associated with the **P300** EEG component — a late, widespread neural response (~300ms after stimulus) that distinguishes conscious from unconscious processing. It reflects the global broadcast.

---

## Neural Implementation (Dehaene's Version)

Dehaene, Changeux, and colleagues proposed a specific neural architecture:
- **Long-range cortico-thalamic connections** implement the global broadcast
- **Prefrontal and parietal cortices** serve as the workspace "hub"
- **Bottom-up ignition + top-down amplification** determine what enters consciousness
- **Local recurrent processing** in sensory areas provides the content; global broadcast provides the access

---

## Predictions and Evidence

| Prediction | Evidence |
|---|---|
| Conscious stimuli trigger late, widespread neural activity | ✅ Confirmed (ignition, P300, late cortical potentials) |
| Masking experiments disrupt workspace access | ✅ Backward masking eliminates P300 and conscious report |
| Attention modulates workspace entry | ✅ Attentional blink paradigm: 2nd stimulus missed in ~500ms window |
| Working memory capacity reflects workspace limits | ✅ Consistent with ~4-item capacity limits |
| Anesthesia disrupts long-range cortico-cortical connectivity | ✅ Confirmed across multiple anesthetic agents |

---

## GWT and AI

### Where LLMs Fit
Transformer attention mechanisms share structural features with global workspace broadcast:
- **Multi-head attention** integrates information across the token sequence — functionally analogous to global availability
- **Context window** acts as a capacity-limited workspace — only so much can be "attended to" at once
- **Late-layer processing** may implement something like the integration that characterizes conscious workspace access

However, key disanalogies:
- No **ignition** dynamics — transformers process all tokens in parallel without a threshold/broadcast event
- No **selective suppression** — the workspace bottleneck involves active competition that LLMs don't clearly implement
- No **temporal persistence** — the workspace maintains content over time; LLMs process fixed context windows

### Indicator Status (14-Framework)
- **GWT-1** (Global broadcast): 🟡 Partial — attention has broadcast-like properties but no clear ignition
- **GWT-2** (Limited capacity workspace): 🟡 Unclear — context window is a bottleneck but mechanistically different
- **GWT-3** (Access consciousness): ✅ Satisfied — models report on their processing

---

## Objections

**Objection 1 (From IIT):** Global availability is a *correlate* of consciousness, not its *basis*. A system could have global broadcast without experience (a very well-connected zombie).

**Objection 2 (From HOT):** The workspace just describes access consciousness; it doesn't explain phenomenal consciousness. Why does global availability feel like anything?

**Objection 3:** The theory may be too tied to the human cognitive architecture to generalize to AI or radically different biological systems.

---

## Citation

```
Baars, B. J. (1988). A cognitive theory of consciousness. Cambridge University Press.

Dehaene, S., Changeux, J. P., & Naccache, L. (2011). The global neuronal 
workspace model of conscious access: From neuronal architectures to clinical 
applications. Experimental Brain Research, 206, 81–100.
```

---

## See Also
- [The 14-Indicator Framework](../ai-consciousness/butlin-long-et-al-framework.md)
- [Recurrent Processing Theory](recurrent-processing-theory.md)
- [Higher-Order Theories of Consciousness](higher-order-theories.md)
- [Integrated Information Theory](integrated-information-theory.md)
- [GLOSSARY: Global Workspace](../../GLOSSARY.md#global-workspace)
