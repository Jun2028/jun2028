## こんにちは / 你好 / Hello! 👋

I’m a mathematics PhD student at the [National University of Singapore](https://www.math.nus.edu.sg/about/) (office S17-05-23). I started with pen-and-paper proofs and now work on machine learning for mathematical reasoning and discovery.

### Research

- **Formal theorem proving** with language models, [Lean 4](https://lean-lang.org/), and [mathlib](https://github.com/leanprover-community/mathlib4).
- **Evaluator-guided search** for mathematical examples and formulas. [AlphaEvolve](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/) · [ASYS](https://github.com/scaling-group/ASYS-PDE)
- **Research workflows** in which agents pursue different approaches to the same problem and share their results. [EvE](https://github.com/scaling-group/eve)

<details>
<summary><code>⊢ human + AI &gt; AI</code></summary>

```mermaid
---
config:
  flowchart:
    minNodeWidth: 0
    nodeSpacing: 18
    rankSpacing: 28
    padding: 8
    diagramPadding: 6
---
flowchart TB
    accTitle: Two searches for a universal conjecture
    accDescr: A conjecture branches into a search for a proof and a search for a counterexample. A counterexample can lead to a revision.
    C(["∀ x, P(x)?"]) -->|prove| P["π : ∀ x, P(x)"]
    C -->|refute| W["w with ¬P(w)"]
    W -.->|revise| C
```

</details>
