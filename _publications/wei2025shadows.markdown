---
layout: publication
title: 'Shadows In The Attention: Contextual Perturbation And Representation Drift In The Dynamics Of Hallucination In Llms'
authors: Zeyu Wei, Shuo Wang, Xiaohui Rong, Xuemin Liu, He Li
conference: "Arxiv"
year: 2025
bibkey: wei2025shadows
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16894'}
tags: ['Attention Mechanism', 'Model Architecture', 'Merging']
---
Hallucinations -- plausible yet erroneous outputs -- remain a critical barrier to reliable deployment of large language models (LLMs). We present the first systematic study linking hallucination incidence to internal-state drift induced by incremental context injection. Using TruthfulQA, we construct two 16-round "titration" tracks per question: one appends relevant but partially flawed snippets, the other injects deliberately misleading content. Across six open-source LLMs, we track overt hallucination rates with a tri-perspective detector and covert dynamics via cosine, entropy, JS and Spearman drifts of hidden states and attention maps. Results reveal (1) monotonic growth of hallucination frequency and representation drift that plateaus after 5--7 rounds; (2) relevant context drives deeper semantic assimilation, producing high-confidence "self-consistent" hallucinations, whereas irrelevant context induces topic-drift errors anchored by attention re-routing; and (3) convergence of JS-Drift (\\(\sim0.69\\)) and Spearman-Drift (\\(\sim0\\)) marks an "attention-locking" threshold beyond which hallucinations solidify and become resistant to correction. Correlation analyses expose a seesaw between assimilation capacity and attention diffusion, clarifying size-dependent error modes. These findings supply empirical foundations for intrinsic hallucination prediction and context-aware mitigation mechanisms.
