---
layout: publication
title: 'Towards Verifiable Text Generation With Evolving Memory And Self-reflection'
authors: Sun Hao, Cai Hengyi, Wang Bo, Hou Yingyan, Wei Xiaochi, Wang Shuaiqiang, Zhang Yan, Yin Dawei
conference: "Arxiv"
year: 2023
bibkey: sun2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09075"}
tags: ['Applications', 'Language Modeling', 'Prompting', 'Tools']
---
Despite the remarkable ability of large language models (LLMs) in language comprehension and generation, they often suffer from producing factually incorrect information, also known as hallucination. A promising solution to this issue is verifiable text generation, which prompts LLMs to generate content with citations for accuracy verification. However, verifiable text generation is non-trivial due to the focus-shifting phenomenon, the intricate reasoning needed to align the claim with correct citations, and the dilemma between the precision and breadth of retrieved documents. In this paper, we present VTG, an innovative framework for Verifiable Text Generation with evolving memory and self-reflection. VTG introduces evolving long short-term memory to retain both valuable documents and recent documents. A two-tier verifier equipped with an evidence finder is proposed to rethink and reflect on the relationship between the claim and citations. Furthermore, active retrieval and diverse query generation are utilized to enhance both the precision and breadth of the retrieved documents. We conduct extensive experiments on five datasets across three knowledge-intensive tasks and the results reveal that VTG significantly outperforms baselines.
