---
layout: publication
title: Or-bench\: An Over-refusal Benchmark For Large Language Models
authors: Cui Justin, Chiang Wei-lin, Stoica Ion, Hsieh Cho-jui
conference: "Arxiv"
year: 2024
bibkey: cui2024over
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20947"}
tags: ['Applications', 'Prompting', 'RAG', 'Responsible AI', 'Survey Paper']
---
Large Language Models (LLMs) require careful safety alignment to prevent malicious outputs. While significant research focuses on mitigating harmful content generation the enhanced safety often come with the side effect of over-refusal where LLMs may reject innocuous prompts and become less helpful. Although the issue of over-refusal has been empirically observed a systematic measurement is challenging due to the difficulty of crafting prompts that appear harmful but are benign. This study proposes a novel method for automatically generating large-scale sets of seemingly toxic prompts (benign prompts likely rejected by LLMs). Leveraging this technique we introduce OR-Bench the first large-scale over-refusal benchmark. OR-Bench comprises 80000 seemingly toxic prompts across 10 common rejection categories a subset of around 1000 hard prompts that are challenging even for state-of-the-art LLMs and an additional 600 toxic prompts to prevent indiscriminate responses. We then conduct a comprehensive study to measure the over-refusal of 25 popular LLMs across 8 model families. Our datasets are available at https://huggingface.co/datasets/bench-llm/or-bench and the demo can be found at https://huggingface.co/spaces/bench-llm/or-bench. We hope this benchmark can help the community develop better safety aligned models.
