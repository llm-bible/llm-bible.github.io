---
layout: publication
title: 'Logic-of-thought: Injecting Logic Into Contexts For Full Reasoning In Large Language Models'
authors: Tongxuan Liu, Wenjiang Xu, Weizhe Huang, Yuting Zeng, Jiaxing Wang, Xingyu Wang, Hailong Yang, Jing Li
conference: "Arxiv"
year: 2024
bibkey: liu2024logic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.17539'}
tags: ['Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
various tasks but their performance in complex logical reasoning tasks remains
unsatisfactory. Although some prompting methods, such as Chain-of-Thought, can
improve the reasoning ability of LLMs to some extent, they suffer from an
unfaithful issue where derived conclusions may not align with the generated
reasoning chain. To address this issue, some studies employ the approach of
propositional logic to further enhance logical reasoning abilities of LLMs.
However, the potential omissions in the extraction of logical expressions in
these methods can cause information loss in the logical reasoning process,
thereby generating incorrect results. To this end, we propose Logic-of-Thought
(LoT) prompting which employs propositional logic to generate expanded logical
information descriptions and utilizes them as an additional augmentation to
original contexts, thereby ensuring information completeness and enhancing
logical reasoning ability. LoT is orthogonal to existing prompting methods and
can be seamlessly integrated with them. Extensive experiments demonstrate that
LoT boosts the performance of various prompting methods with a striking margin
across five logical reasoning tasks. In particular, LoT enhances
Chain-of-Thought's performance on the ReClor dataset by +4.35%, improves
Chain-of-Thought with Self-Consistency's performance on the RuleTaker dataset
by +3.52%, and boosts performance of Tree-of-Thoughts on the ProofWriter
dataset by +8%.
