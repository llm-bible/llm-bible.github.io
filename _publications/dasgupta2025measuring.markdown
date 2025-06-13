---
layout: publication
title: 'Hallushift: Measuring Distribution Shifts Towards Hallucination Detection In Llms'
authors: Sharanya Dasgupta, Sujoy Nath, Arkaprabha Basu, Pourya Shamsolmoali, Swagatam Das
conference: "Arxiv"
year: 2025
bibkey: dasgupta2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09482"}
  - {name: "Code", url: "https://github.com/sharanya-dasgupta001/hallushift"}
tags: ['Prompting', 'Has Code', 'Model Architecture', 'Attention Mechanism']
---
Large Language Models (LLMs) have recently garnered widespread attention due
to their adeptness at generating innovative responses to the given prompts
across a multitude of domains. However, LLMs often suffer from the inherent
limitation of hallucinations and generate incorrect information while
maintaining well-structured and coherent responses. In this work, we
hypothesize that hallucinations stem from the internal dynamics of LLMs. Our
observations indicate that, during passage generation, LLMs tend to deviate
from factual accuracy in subtle parts of responses, eventually shifting toward
misinformation. This phenomenon bears a resemblance to human cognition, where
individuals may hallucinate while maintaining logical coherence, embedding
uncertainty within minor segments of their speech. To investigate this further,
we introduce an innovative approach, HalluShift, designed to analyze the
distribution shifts in the internal state space and token probabilities of the
LLM-generated responses. Our method attains superior performance compared to
existing baselines across various benchmark datasets. Our codebase is available
at https://github.com/sharanya-dasgupta001/hallushift.
