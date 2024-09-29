---
layout: publication
title: Alleviating Hallucination In Large Vision45;language Models With Active Retrieval Augmentation
authors: Xiaoye Qu, Qiyuan Chen, Wei Wei, Jishuo Sun, Jianfeng Dong
conference: "Arxiv"
year: 2024
bibkey: qu2024alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2408.00555v1"}
tags: ['Applications', 'RAG', 'Tools']
---
Despite the remarkable ability of large vision45;language models (LVLMs) in image comprehension these models frequently generate plausible yet factually incorrect responses a phenomenon known as hallucination.Recently in large language models (LLMs) augmenting LLMs by retrieving information from external knowledge resources has been proven as a promising solution to mitigate hallucinations.However the retrieval augmentation in LVLM significantly lags behind the widespread applications of LVLM. Moreover when transferred to augmenting LVLMs sometimes the hallucination degree of the model is even exacerbated.Motivated by the research gap and counter45;intuitive phenomenon we introduce a novel framework the Active Retrieval45;Augmented large vision45;language model (ARA) specifically designed to address hallucinations by incorporating three critical dimensions (i) dissecting the retrieval targets based on the inherent hierarchical structures of images. (ii) pinpointing the most effective retrieval methods and filtering out the reliable retrieval results. (iii) timing the retrieval process to coincide with episodes of low certainty while circumventing unnecessary retrieval during periods of high certainty. To assess the capability of our proposed ARA model in reducing hallucination we employ three widely used LVLM models (LLaVA45;1.5 Qwen45;VL and mPLUG45;Owl2) across four benchmarks. Our empirical observations suggest that by utilizing fitting retrieval mechanisms and timing the retrieval judiciously we can effectively mitigate the hallucination problem. We hope that this study can provide deeper insights into how to adapt the retrieval augmentation to LVLMs for reducing hallucinations with more effective retrieval and minimal retrieval occurrences.
