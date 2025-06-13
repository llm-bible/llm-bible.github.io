---
layout: publication
title: 'In-context Watermarks For Large Language Models'
authors: Yepeng Liu, Xuandong Zhao, Christopher Kruegel, Dawn Song, Yuheng Bu
conference: "Arxiv"
year: 2025
bibkey: liu2025watermarks
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16934"}
tags: ['Responsible AI', 'Survey Paper', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications', 'In-Context Learning']
---
The growing use of large language models (LLMs) for sensitive applications has highlighted the need for effective watermarking techniques to ensure the provenance and accountability of AI-generated text. However, most existing watermarking methods require access to the decoding process, limiting their applicability in real-world settings. One illustrative example is the use of LLMs by dishonest reviewers in the context of academic peer review, where conference organizers have no access to the model used but still need to detect AI-generated reviews. Motivated by this gap, we introduce In-Context Watermarking (ICW), which embeds watermarks into generated text solely through prompt engineering, leveraging LLMs' in-context learning and instruction-following abilities. We investigate four ICW strategies at different levels of granularity, each paired with a tailored detection method. We further examine the Indirect Prompt Injection (IPI) setting as a specific case study, in which watermarking is covertly triggered by modifying input documents such as academic manuscripts. Our experiments validate the feasibility of ICW as a model-agnostic, practical watermarking approach. Moreover, our findings suggest that as LLMs become more capable, ICW offers a promising direction for scalable and accessible content attribution.
