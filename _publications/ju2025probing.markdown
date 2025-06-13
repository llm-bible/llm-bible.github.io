---
layout: publication
title: 'Probing Then Editing Response Personality Of Large Language Models'
authors: Tianjie Ju, Zhenyu Shao, Bowen Wang, Yujia Chen, Zhuosheng Zhang, Hao Fei, Mong-li Lee, Wynne Hsu, Sufeng Duan, Gongshen Liu
conference: "Arxiv"
year: 2025
bibkey: ju2025probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10227"}
  - {name: "Code", url: "https://github.com/universe-sky/probing-then-editing-personality"}
tags: ['Training Techniques', 'Has Code', 'Prompting', 'Tools']
---
Large Language Models (LLMs) have demonstrated promising capabilities to
generate responses that exhibit consistent personality traits. Despite the
major attempts to analyze personality expression through output-based
evaluations, little is known about how such traits are internally encoded
within LLM parameters. In this paper, we introduce a layer-wise probing
framework to systematically investigate the layer-wise capability of LLMs in
encoding personality for responding. We conduct probing experiments on 11
open-source LLMs over the PersonalityEdit benchmark and find that LLMs
predominantly encode personality for responding in their middle and upper
layers, with instruction-tuned models demonstrating a slightly clearer
separation of personality traits. Furthermore, by interpreting the trained
probing hyperplane as a layer-wise boundary for each personality category, we
propose a layer-wise perturbation method to edit the personality expressed by
LLMs during inference. Our results show that even when the prompt explicitly
specifies a particular personality, our method can still successfully alter the
response personality of LLMs. Interestingly, the difficulty of converting
between certain personality traits varies substantially, which aligns with the
representational distances in our probing experiments. Finally, we conduct a
comprehensive MMLU benchmark evaluation and time overhead analysis,
demonstrating that our proposed personality editing method incurs only minimal
degradation in general capabilities while maintaining low training costs and
acceptable inference latency. Our code is publicly available at
https://github.com/universe-sky/probing-then-editing-personality.
