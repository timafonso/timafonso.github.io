---
title: "ProofCoder: Continuous Reasoning for Automated Software Verification"
collection: publications
category: preprints
permalink: /publication/2026-11-10-proofcoder
excerpt: 'An agentic proof-synthesis system for the Rocq proof assistant that reasons continuously during search, using proof-checker feedback to decide when to gather information, inspect proof states, revise, or backtrack.'
date: 2026-11-10
venue: 'arXiv preprint arXiv:2611.14106'
paperurl: 'https://arxiv.org/abs/2611.14106'
citation: 'Afonso, M., Lynce, I., Morisio, M., &amp; Ferreira, J. F. (2026). &quot;ProofCoder: Continuous Reasoning for Automated Software Verification.&quot; <i>arXiv preprint arXiv:2611.14106</i>.'
bibtex: |
  @article{afonso2026proofcoder,
    title   = {ProofCoder: Continuous Reasoning for Automated Software Verification},
    author  = {Afonso, Martim and Lynce, Inês and Morisio, Maurizio and Ferreira, João F.},
    journal = {arXiv preprint arXiv:2611.14106},
    year    = {2026}
  }
---

**Authors:** Martim Afonso, Inês Lynce, Maurizio Morisio, João F. Ferreira

Formal proofs in proof assistants give strong correctness guarantees but are hard and time-consuming to write. Earlier LLM-based methods tend to confine the model to a fixed tactic-generation loop, where the surrounding system manages premise retrieval, proof states, and backtracking. We present ProofCoder, an agentic proof-synthesis system for the Rocq proof assistant that works like a coding agent: it reasons continuously during search and uses proof-checker feedback to decide when to gather information, inspect proof states, revise proof fragments, or backtrack, operating at tactic or whole-proof granularity. On 280 tasks from the AutoRocq Benchmark, the best configurations raise proof success from 47% to 60% over AutoRocq — a 27.7% relative gain at about half the cost. Ablations show that continuous reasoning is key: without it, the agent solves fewer lemmas, costs more, backtracks far more often, and discards more of its own revisions.

[Read on arXiv](https://arxiv.org/abs/2611.14106){: .btn} [PDF](https://arxiv.org/pdf/2611.14106){: .btn}
