---
layout: publication
title: Knowledge Verification to Nip Hallucination in the Bud
authors: Wan Fanqi, Huang Xinting, Cui Leyang, Quan Xiaojun, Bi Wei, Shi Shuming
conference: "Arxiv"
year: 2024
bibkey: wan2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10768"}
tags: ['Applications']
---
While large language models (LLMs) have demonstrated exceptional performance across various tasks following human alignment they may still generate responses that sound plausible but contradict factual knowledge a phenomenon known as . In this paper we demonstrate the feasibility of mitigating hallucinations by verifying and minimizing the inconsistency between external knowledge present in the alignment data and the intrinsic knowledge embedded within foundation LLMs. Specifically we propose a novel approach called Knowledge Consistent Alignment (KCA) which employs a well-aligned LLM to automatically formulate assessments based on external knowledge to evaluate the knowledge boundaries of foundation LLMs. To address knowledge inconsistencies in the alignment data KCA implements several specific strategies to deal with these data instances. We demonstrate the superior efficacy of KCA in reducing hallucinations across six benchmarks utilizing foundation LLMs of varying backbones and scales. This confirms the effectiveness of mitigating hallucinations by reducing knowledge inconsistency. Our code model weights and data are openly accessible at .
