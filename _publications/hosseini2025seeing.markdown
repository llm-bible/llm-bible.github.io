---
layout: publication
title: 'Seeing What''s Not There: Spurious Correlation In Multimodal Llms'
authors: Parsa Hosseini, Sumit Nawathe, Mazda Moayeri, Sriram Balasubramanian, Soheil Feizi
conference: "Arxiv"
year: 2025
bibkey: hosseini2025seeing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08884'}
tags: ['RAG', 'Model Architecture', 'GPT', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Unimodal vision models are known to rely on spurious correlations, but it
remains unclear to what extent Multimodal Large Language Models (MLLMs) exhibit
similar biases despite language supervision. In this paper, we investigate
spurious bias in MLLMs and introduce SpurLens, a pipeline that leverages GPT-4
and open-set object detectors to automatically identify spurious visual cues
without human supervision. Our findings reveal that spurious correlations cause
two major failure modes in MLLMs: (1) over-reliance on spurious cues for object
recognition, where removing these cues reduces accuracy, and (2) object
hallucination, where spurious cues amplify the hallucination by over 10x. We
validate our findings in various MLLMs and datasets. Beyond diagnosing these
failures, we explore potential mitigation strategies, such as prompt ensembling
and reasoning-based prompting, and conduct ablation studies to examine the root
causes of spurious bias in MLLMs. By exposing the persistence of spurious
correlations, our study calls for more rigorous evaluation methods and
mitigation strategies to enhance the reliability of MLLMs.
