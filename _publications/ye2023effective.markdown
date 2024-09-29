---
layout: publication
title: "Effective Large Language Model Adaptation For Improved Grounding And Citation Generation"
authors: Ye Xi, Sun Ruoxi, Arik Sercan Ö., Pfister Tomas
conference: "Arxiv"
year: 2023
bibkey: ye2023effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09533"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have achieved remarkable advancements in natural language understanding and generation. However one major issue towards their widespread deployment in the real world is that they can generate hallucinated answers that are not factual. Towards this end this paper focuses on improving LLMs by grounding their responses in retrieved passages and by providing citations. We propose a new framework AGREE Adaptation for GRounding EnhancEment that improves the grounding from a holistic perspective. Our framework tunes LLMs to selfground the claims in their responses and provide accurate citations to retrieved documents. This tuning on top of the pre-trained LLMs requires well-grounded responses (with citations) for paired queries for which we introduce a method that can automatically construct such data from unlabeled queries. The selfgrounding capability of tuned LLMs further grants them a test-time adaptation (TTA) capability that can actively retrieve passages to support the claims that have not been grounded which iteratively improves the responses of LLMs. Across five datasets and two LLMs our results show that the proposed tuningbased AGREE framework generates superior grounded responses with more accurate citations compared to prompting-based approaches and post-hoc citing-based approaches
