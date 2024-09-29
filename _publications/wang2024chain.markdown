---
layout: publication
title: "Chain-of-thought Reasoning Without Prompting"
authors: Wang Xuezhi, Zhou Denny
conference: "Arxiv"
year: 2024
bibkey: wang2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10200"}
tags: ['Few Shot', 'Prompting']
---
In enhancing the reasoning capabilities of large language models (LLMs) prior research primarily focuses on specific prompting techniques such as few-shot or zero-shot chain-of-thought (CoT) prompting. These methods while effective often involve manually intensive prompt engineering. Our study takes a novel approach by asking Can LLMs reason effectively without prompting Our findings reveal that intriguingly CoT reasoning paths can be elicited from pre-trained LLMs by simply altering the (textitdecoding) process. Rather than conventional greedy decoding we investigate the top-k alternative tokens uncovering that CoT paths are frequently inherent in these sequences. This approach not only bypasses the confounders of prompting but also allows us to assess the LLMs (textitintrinsic) reasoning abilities. Moreover we observe that the presence of a CoT in the decoding path correlates with a higher confidence in the models decoded answer. This confidence metric effectively differentiates between CoT and non-CoT paths. Extensive empirical studies on various reasoning benchmarks show that the proposed CoT-decoding effectively elicits reasoning capabilities from language models which were previously obscured by standard greedy decoding.
