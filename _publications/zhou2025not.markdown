---
layout: publication
title: 'Not All Tokens Are Meant To Be Forgotten'
authors: Xiangyu Zhou, Yao Qiang, Saleh Zare Zade, Douglas Zytko, Prashant Khanduri, Dongxiao Zhu
conference: "Arxiv"
year: 2025
bibkey: zhou2025not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03142"}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
Large Language Models (LLMs), pre-trained on massive text corpora, exhibit remarkable human-level language understanding, reasoning, and decision-making abilities. However, they tend to memorize unwanted information, such as private or copyrighted content, raising significant privacy and legal concerns. Unlearning has emerged as a promising solution, but existing methods face a significant challenge of over-forgetting. This issue arises because they indiscriminately suppress the generation of all the tokens in forget samples, leading to a substantial loss of model utility. To overcome this challenge, we introduce the Targeted Information Forgetting (TIF) framework, which consists of (1) a flexible targeted information identifier designed to differentiate between unwanted words (UW) and general words (GW) in the forget samples, and (2) a novel Targeted Preference Optimization approach that leverages Logit Preference Loss to unlearn unwanted information associated with UW and Preservation Loss to retain general information in GW, effectively improving the unlearning process while mitigating utility degradation. Extensive experiments on the TOFU and MUSE benchmarks demonstrate that the proposed TIF framework enhances unlearning effectiveness while preserving model utility and achieving state-of-the-art results.
