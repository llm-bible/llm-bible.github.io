---
layout: publication
title: 'The Mirage Of Multimodality: Where Truth Is Tested And Honesty Unravels'
authors: Jiaming Ji, Sitong Fang, Wenjing Cao, Jiahao Li, Xuyao Wang, Juntao Dai, Chi-min Chan, Sirui Han, Yike Guo, Yaodong Yang
conference: "Arxiv"
year: 2025
bibkey: ji2025mirage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20214"}
tags: ['Security', 'Model Architecture', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Attention Mechanism']
---
Reasoning models have recently attracted significant attention, especially for tasks that involve complex inference. Their strengths exemplify the System II paradigm (slow, structured thinking), contrasting with the System I (rapid, heuristic-driven). Yet, does slower reasoning necessarily lead to greater truthfulness? Our findings suggest otherwise. In this study, we present the first systematic investigation of distortions associated with System I and System II reasoning in multimodal contexts. We demonstrate that slower reasoning models, when presented with incomplete or misleading visual inputs, are more likely to fabricate plausible yet false details to support flawed reasoning -- a phenomenon we term the "Mirage of Multimodality". To examine this, we constructed a 5,000-sample hierarchical prompt dataset annotated by 50 human participants. These prompts gradually increase in complexity, revealing a consistent pattern: slower reasoning models tend to employ depth-first thinking (delving deeper into incorrect premises), whereas faster chat models favor breadth-first inference, exhibiting greater caution under uncertainty. Our results highlight a critical vulnerability of slower reasoning models: although highly effective in structured domains such as mathematics, it becomes brittle when confronted with ambiguous multimodal inputs.
