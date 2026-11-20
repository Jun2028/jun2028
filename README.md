## こんにちは / 你好 / Hello! 👋

I’m a mathematics PhD student at the [National University of Singapore](https://www.math.nus.edu.sg/about/) (office S17-05-23). I started with pen-and-paper proofs and now work on machine learning for mathematical reasoning and discovery.

<details>
<summary><strong>1 open goal</strong> &nbsp; <code>⊢ human + AI &gt; AI</code></summary>

Give two agents the same conjecture. One tries to prove it while the other looks for a counterexample.

```mermaid
flowchart LR
    accTitle: Two searches for a universal conjecture
    accDescr: One agent seeks a formal proof. Another looks for a counterexample, which the mathematician can use to revise the conjecture.
    C(["∀ x, P(x)?"]) -->|prove| P["π : ∀ x, P(x)"]
    C -->|refute| W["w with ¬P(w)"]
    W -.->|revise the claim| C
```

If the search returns `w` and `hw : ¬ P w`, then `fun h => hw (h w)` is a Lean proof that the conjecture is false.

</details>

### Research

- **Formal theorem proving** with language models, [Lean 4](https://lean-lang.org/), and [mathlib](https://github.com/leanprover-community/mathlib4).
- **Evaluator-guided search** for mathematical examples and formulas. [AlphaEvolve](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/) · [ASYS](https://github.com/scaling-group/ASYS-PDE)
- **Research workflows** in which agents pursue different approaches to the same problem and share their results. [EvE](https://github.com/scaling-group/eve)
