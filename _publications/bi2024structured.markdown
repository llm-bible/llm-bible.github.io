---
layout: publication
title: 'Struedit: Structured Outputs Enable The Fast And Accurate Knowledge Editing For Large Language Models'
authors: Baolong Bi, Shenghua Liu, Yiwei Wang, Lingrui Mei, Hongcheng Gao, Junfeng Fang, Xueqi Cheng
conference: "Arxiv"
year: 2024
bibkey: bi2024structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10132"}
tags: ['Prompting', 'Applications']
---
As the modern tool of choice for question answering, large language models
(LLMs) are expected to deliver answers with up-to-date knowledge. To achieve
such ideal question-answering systems, locating and then editing outdated
knowledge in the natural language outputs is a general target of popular
knowledge editing methods. However, this target is challenging, as both
identifying which tokens to edit in the reasoning steps and ensuring the
coherence of the revised reasoning chain are difficult tasks. We argue that
these challenges stem from the unstructured nature of natural language outputs.
To address the above challenges, we propose \\(\textbf\{Stru\}\\)ctural
\\(\textbf\{Edit\}\\)ing (\\(\textbf\{StruEdit\}\\)), an improved baseline for knowledge
editing. We first prompt LLMs to produce structured outputs consisting of
reasoning triplets. Then, StruEdit removes any potentially outdated knowledge
and efficiently refills the structured outputs with up-to-date information in a
single step. Experimental results show that StruEdit consistently delivers the
highest accuracy with lowest latency compared with other knowledge editing
methods.
