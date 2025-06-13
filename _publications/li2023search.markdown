---
layout: publication
title: 'In Search Of The Long-tail: Systematic Generation Of Long-tail Inferential Knowledge Via Logical Rule Guided Search'
authors: Huihan Li, Yuting Ning, Zeyi Liao, Siyuan Wang, Xiang Lorraine Li, Ximing Lu, Wenting Zhao, Faeze Brahman, Yejin Choi, Xiang Ren
conference: "Arxiv"
year: 2023
bibkey: li2023search
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.07237'}
tags: ['GPT', 'Tools', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
To effectively use large language models (LLMs) for real-world queries, it is
imperative that they generalize to the long-tail distribution, i.e. rare
examples where models exhibit low confidence. In this work, we take the first
step towards evaluating LLMs in the long-tail distribution of inferential
knowledge. We exemplify long-tail evaluation on the Natural Language Inference
task. First, we introduce Logic-Induced-Knowledge-Search (LINK), a systematic
long-tail data generation framework, to obtain factually-correct yet long-tail
inferential statements. LINK uses variable-wise prompting grounded on symbolic
rules to seek low-confidence statements while ensuring factual correctness. We
then use LINK to curate Logic-Induced-Long-Tail (LINT), a large-scale long-tail
inferential knowledge dataset that contains 108K statements spanning four
domains. We evaluate popular LLMs on LINT; we find that state-of-the-art LLMs
show significant performance drop (21% relative drop for GPT4) on long-tail
data as compared to on head distribution data, and smaller models show even
more generalization weakness. These results further underscore the necessity of
long-tail evaluation in developing generalizable LLMs.
