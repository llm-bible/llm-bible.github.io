---
layout: publication
title: 'Sparse Brains Are Also Adaptive Brains: Cognitive-load-aware Dynamic Activation For Llms'
authors: Yiheng Yang, Yujie Wang, Chi Ma, Lei Yu, Emmanuele Chersoni, Chu-ren Huang
conference: "Arxiv"
year: 2025
bibkey: yang2025sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19078"}
  - {name: "Code", url: "https://github.com/Oldify/CLADA}{CLADA"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Has Code']
---
Dense large language models(LLMs) face critical efficiency bottlenecks as
they rigidly activate all parameters regardless of input complexity. While
existing sparsity methods(static pruning or dynamic activation) address this
partially, they either lack adaptivity to contextual or model structural
demands or incur prohibitive computational overhead. Inspired by human brain's
dual-process mechanisms - predictive coding (N400) for backbone sparsity and
structural reanalysis (P600) for complex context - we propose CLADA, a
\textit\{\textbf\{C\}ognitive-\textbf\{L\}oad-\textbf\{A\}ware \textbf\{D\}ynamic
\textbf\{A\}ctivation\} framework that synergizes statistical sparsity with
semantic adaptability. Our key insight is that LLM activations exhibit two
complementary patterns: 1) \textit\{Global statistical sparsity\} driven by
sequence-level prefix information, and 2) \textit\{Local semantic adaptability\}
modulated by cognitive load metrics(e.g., surprisal and entropy). CLADA employs
a hierarchical thresholding strategy: a baseline from offline error-controlled
optimization ensures 40%+ sparsity, dynamically adjusted by real-time
cognitive signals. Evaluations across six mainstream LLMs and nine benchmarks
demonstrate that CLADA achieves \textbf\{~20% average speedup with <2%
accuracy drop\}, outperforming Griffin (5%+ degradation) and TT (negligible
speedup). Crucially, we establish the first formal connection between
neurolinguistic event-related potential (ERP) components and LLM efficiency
mechanisms through multi-level regression analysis (\\(R^2=0.17\\) for
sparsity-adaptation synergy). Requiring no retraining or architectural changes,
CLADA offers a deployable solution for resource-aware LLM inference while
advancing biologically-inspired AI design. Our code is available at
\href\{https://github.com/Oldify/CLADA\}\{CLADA\}.
