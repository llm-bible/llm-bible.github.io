---
layout: publication
title: 'Improving Faithfulness Of Large Language Models In Summarization Via Sliding Generation And Self-consistency'
authors: Li Taiji, Li Zhi, Zhang Yin
conference: "Arxiv"
year: 2024
bibkey: li2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21443"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Despite large language models (LLMs) have demonstrated impressive performance
in various tasks, they are still suffering from the factual inconsistency
problem called hallucinations. For instance, LLMs occasionally generate content
that diverges from source article, and prefer to extract information that
appears at the beginning and end of the context, especially in long document
summarization. Inspired by these findings, we propose to improve the
faithfulness of LLMs in summarization by impelling them to process the entire
article more fairly and faithfully. We present a novel summary generation
strategy, namely SliSum, which exploits the ideas of sliding windows and
self-consistency. Specifically, SliSum divides the source article into
overlapping windows, and utilizes LLM to generate local summaries for the
content in the windows. Finally, SliSum aggregates all local summaries using
clustering and majority voting algorithm to produce more faithful summary of
entire article. Extensive experiments demonstrate that SliSum significantly
improves the faithfulness of diverse LLMs including LLaMA-2, Claude-2 and
GPT-3.5 in both short and long text summarization, while maintaining their
fluency and informativeness and without additional fine-tuning and resources.
We further conduct qualitative and quantitative studies to investigate why
SliSum works and impacts of hyperparameters in SliSum on performance.
