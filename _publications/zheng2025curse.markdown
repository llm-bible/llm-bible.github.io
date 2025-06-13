---
layout: publication
title: 'The Curse Of Cot: On The Limitations Of Chain-of-thought In In-context Learning'
authors: Tianshi Zheng, Yixiang Chen, Chengxi Li, Chunyang Li, Qing Zong, Haochen Shi, Baixuan Xu, Yangqiu Song, Ginny Y. Wong, Simon See
conference: "Arxiv"
year: 2025
bibkey: zheng2025curse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05081"}
tags: ['Prompting', 'Interpretability and Explainability', 'In-Context Learning', 'Reinforcement Learning']
---
Chain-of-Thought (CoT) prompting has been widely recognized for its ability
to enhance reasoning capabilities in large language models (LLMs) through the
generation of explicit explanatory rationales. However, our study reveals a
surprising contradiction to this prevailing perspective. Through extensive
experiments involving 16 state-of-the-art LLMs and nine diverse pattern-based
in-context learning (ICL) datasets, we demonstrate that CoT and its reasoning
variants consistently underperform direct answering across varying model scales
and benchmark complexities. To systematically investigate this unexpected
phenomenon, we designed extensive experiments to validate several hypothetical
explanations. Our analysis uncovers a fundamental explicit-implicit duality
driving CoT's performance in pattern-based ICL: while explicit reasoning
falters due to LLMs' struggles to infer underlying patterns from
demonstrations, implicit reasoning-disrupted by the increased contextual
distance of CoT rationales-often compensates, delivering correct answers
despite flawed rationales. This duality explains CoT's relative
underperformance, as noise from weak explicit inference undermines the process,
even as implicit mechanisms partially salvage outcomes. Notably, even long-CoT
reasoning models, which excel in abstract and symbolic reasoning, fail to fully
overcome these limitations despite higher computational costs. Our findings
challenge existing assumptions regarding the universal efficacy of CoT,
yielding novel insights into its limitations and guiding future research toward
more nuanced and effective reasoning methodologies for LLMs.
