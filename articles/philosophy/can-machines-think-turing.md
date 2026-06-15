# Can Machines Think? — The Imitation Game

> **Source:** *Mind*, Vol. 59, No. 236, pp. 433–460  
> **Author:** Alan Turing  
> **Published:** 1950  
> **Category:** Philosophy of Mind | AI | Foundational

---

## TL;DR

Turing proposed replacing the question "Can machines think?" — philosophically intractable — with a behavioral test: can a machine imitate a human in conversation well enough that an interrogator can't reliably distinguish them? This reframing influenced decades of AI research, but the test's relationship to genuine intelligence or consciousness remains deeply contested.

---

## The Imitation Game

Turing proposed a game with three players:
- **A:** A man
- **B:** A woman  
- **C:** An interrogator who can only communicate via text

The interrogator asks questions to determine which is the man and which the woman. A tries to mislead; B tries to help the interrogator.

Turing then asks: **what if we replace A (the man) with a machine?** If the interrogator can't reliably identify the machine as non-human, the machine has "passed" the test.

This became known as the **Turing Test** (though Turing didn't call it that).

---

## Why This Reframing?

Turing's move was pragmatic: "Can machines think?" depends on definitions of "machine" and "think" that are philosophically contested and perhaps unanswerable. The imitation game replaces it with a behavioral criterion — something we can actually test.

This reflects Turing's **behaviorist sympathies**: what matters about mental states is their behavioral expression, not some inner essence that might be inaccessible.

---

## Turing's Anticipation of Objections

In the same paper, Turing systematically addressed objections he anticipated:

### The Theological Objection
"Thinking is a function of the soul; machines can't have souls."  
*Turing:* This places unwarranted limits on divine omnipotence — God could give machines souls if desired. More practically, this is just an assertion, not an argument.

### The "Heads in the Sand" Objection
"Thinking machines would be too frightening; let's hope they're impossible."  
*Turing:* This isn't an argument against possibility.

### The Mathematical Objection (Gödel)
"Gödel's incompleteness theorems show there are things machines can't do that humans can."  
*Turing:* Even if there are things discrete state machines can't do, this doesn't show humans can do them either. And this objection only applies to formal systems, not necessarily to all machine types.

### The Argument from Consciousness
"Machines can't have subjective experience; without it, they can't truly think."  
*Turing:* This is the solipsism problem — we can't verify other minds directly anyway. We infer them from behavior. The same inference should apply to machines.

### The Argument from Originality
"Machines only do what they're programmed to do; they can't be original."  
*Turing:* Machines can surprise their creators. Predictability in principle ≠ predictability in practice. Humans are also "programmed" by genetics and experience.

### The Argument from Informality of Behavior
"Human behavior can't be captured by rules; machines can only follow rules."  
*Turing:* This assumes we know that human behavior can't be formalized — which we don't.

---

## The Learning Machine

Turing's more interesting vision was not a hand-coded machine, but a **learning machine** — one that starts with minimal programming and learns through interaction, analogous to how children learn. He described something remarkably like modern large language models:

> "Instead of trying to produce a programme to simulate the adult mind, why not rather try to produce one which simulates the child's mind? If this were subjected to an appropriate course of education one would obtain the adult brain."

He also suggested that *random* elements might be important — making the machine less predictable and more interesting. This foreshadows stochastic elements in modern ML training.

---

## Limitations and Critiques of the Turing Test

### The Chinese Room (Searle)
The room passes the Turing test for Chinese without understanding Chinese. Behavioral indistinguishability is not sufficient for genuine cognition. (See [Chinese Room](chinese-room.md))

### Clever Hans
The famous horse who seemed to do arithmetic but was actually reading subtle cues from handlers. Passing behavioral tests doesn't guarantee the underlying process is what we think it is.

### GPT-4 and the Test
Modern LLMs routinely pass informal Turing tests in many domains. This either means: (a) they're approaching genuine intelligence/consciousness, or (b) the test was too behavioral and doesn't capture what matters. The field is divided.

### Winograd's Critique
The test conflates many different cognitive capacities. A machine might pass by exploiting statistical patterns rather than genuine understanding. Winograd and others proposed harder tests (Winograd schema) targeting specific reasoning capacities.

---

## Turing's Legacy

Turing's 1950 paper established:
- **Behavioral criteria** as the dominant framework for AI evaluation (for better or worse)
- The **learning machine** vision that anticipates modern ML
- A systematic engagement with philosophical objections that remains relevant

His own view of consciousness and machine minds was nuanced: he was skeptical of strong claims in either direction, and thought the question would eventually be settled empirically — through machines that convincingly mimicked human behavior in open-ended interaction.

---

## Citation

```
Turing, A. M. (1950). Computing machinery and intelligence. 
Mind, 59(236), 433–460.
```

---

## See Also
- [The Chinese Room](chinese-room.md)
- [Functionalism and the Mind](functionalism.md)
- [The Hard Problem of Consciousness](../human-consciousness/hard-problem.md)
- [Evidence for AI Consciousness, Today](../ai-consciousness/evidence-for-ai-consciousness-today.md)
- [GLOSSARY: Turing Test](../../GLOSSARY.md#turing-test)
- [GLOSSARY: Behaviorism](../../GLOSSARY.md#behaviorism)
