---
layout: publication
title: 'Keys To Robust Edits: From Theoretical Insights To Practical Advances'
authors: Jianhao Yan, Futing Wang, Yun Luo, Yafu Li, Yue Zhang
conference: "Arxiv"
year: 2024
bibkey: yan2024keys
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09338'}
  - {name: "Code", url: 'https://github.com/ElliottYan/RobustKeyEdit'}
tags: ['Has Code', 'Security', 'Pretraining Methods']
---
Large language models (LLMs) struggle with maintaining accurate knowledge due to conflicting/outdated parametric memories. While locate-and-edit methods address this, their reliance on models' internal representations leads to robustness failures in long-context reasoning and paraphrased queries. We identify a fundamental limitation of locate-and-edit methods: existing semantic keys (for memory localization) cannot simultaneously satisfy robustness (context-invariant activation) and specificity (precise knowledge discrimination). Through theoretical error-bound analysis, we establish formal criteria for effective editing. Our solution introduces \textit\{Robust Edit Pathway (REP)\}, a plug-and-play module that: (1) disentangles editing keys from native model representations; (2) dynamically adjusts keys via contrastive learning to achieve robustness-specificity balance. Extensive experiments across various editing methods (ROME/MEMIT/R-ROME/EMMET), existing LLMs (LLaMA2, QWen, Mistral), and datasets (CounterFact, ZsRE) show that REP improves success rate over robustness tests by up-to 66.4% while maintaining the success rate unaffected. Our code can be found at https://github.com/ElliottYan/RobustKeyEdit .
