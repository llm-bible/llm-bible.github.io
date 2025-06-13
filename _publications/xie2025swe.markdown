---
layout: publication
title: 'Swe-fixer: Training Open-source Llms For Effective And Efficient Github Issue Resolution'
authors: Chengxing Xie, Bowen Li, Chang Gao, He Du, Wai Lam, Difan Zou, Kai Chen
conference: "Arxiv"
year: 2025
bibkey: xie2025swe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05040"}
  - {name: "Code", url: "https://github.com/InternLM/SWE-Fixer"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Has Code']
---
Large Language Models (LLMs) have demonstrated remarkable proficiency across
a variety of complex tasks. One significant application of LLMs is in tackling
software engineering challenges, particularly in resolving real-world tasks on
GitHub by fixing code based on the issues reported by the users. However, many
current approaches rely on proprietary LLMs, which limits reproducibility,
accessibility, and transparency. The critical components of LLMs for addressing
software engineering issues and how their capabilities can be effectively
enhanced remain unclear. To address these challenges, we introduce SWE-Fixer, a
novel open-source framework designed to effectively and efficiently resolve
GitHub issues. SWE-Fixer comprises two essential modules: a code file retrieval
module and a code editing module. The retrieval module employs BM25 along with
a lightweight model to achieve coarse-to-fine file retrieval. Subsequently, the
code editing module utilizes the other model to generate patches for the
identified files. To mitigate the lack of publicly available datasets, we
compile an extensive dataset that includes 110K GitHub issues along with their
corresponding patches and train the two models of SWE-Fixer separately. We
assess our approach on the SWE-Bench Lite and Verified benchmarks, achieving
competitive performance among open-source models with scores of 22.0% and
30.2%. Furthermore, SWE-Fixer reaches state-of-the-art performance (24.7% on
Lite and 32.8% on Verified) with PASS_TO_PASS (P2P) filtering. Additionally,
our approach requires only two model calls per instance, making it
significantly more efficient than existing methods. These results highlight the
effectiveness of SWE-Fixer in real-world code-fixing scenarios. We will make
our model, dataset, and code publicly available at
https://github.com/InternLM/SWE-Fixer.
