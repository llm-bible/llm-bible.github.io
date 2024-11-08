---
layout: publication
title: 'Pollmgraph: Unraveling Hallucinations In Large Language Models Via State Transition Dynamics'
authors: Zhu Derui, Chen Dingfan, Li Qing, Chen Zongxiong, Ma Lei, Grossklags Jens, Fritz Mario
conference: "Arxiv"
year: 2024
bibkey: zhu2024unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04722"}
tags: []
---
Despite tremendous advancements in large language models (LLMs) over recent
years, a notably urgent challenge for their practical deployment is the
phenomenon of hallucination, where the model fabricates facts and produces
non-factual statements. In response, we propose PoLLMgraph, a Polygraph for
LLMs, as an effective model-based white-box detection and forecasting approach.
PoLLMgraph distinctly differs from the large body of existing research that
concentrates on addressing such challenges through black-box evaluations. In
particular, we demonstrate that hallucination can be effectively detected by
analyzing the LLM's internal state transition dynamics during generation via
tractable probabilistic models. Experimental results on various open-source
LLMs confirm the efficacy of PoLLMgraph, outperforming state-of-the-art methods
by a considerable margin, evidenced by over 20% improvement in AUC-ROC on
common benchmarking datasets like TruthfulQA. Our work paves a new way for
model-based white-box analysis of LLMs, motivating the research community to
further explore, understand, and refine the intricate dynamics of LLM
behaviors.
