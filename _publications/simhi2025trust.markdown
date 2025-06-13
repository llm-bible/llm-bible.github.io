---
layout: publication
title: 'Trust Me, I''m Wrong: High-certainty Hallucinations In Llms'
authors: Adi Simhi, Itay Itzhak, Fazl Barez, Gabriel Stanovsky, Yonatan Belinkov
conference: "Arxiv"
year: 2025
bibkey: simhi2025trust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12964"}
  - {name: "Code", url: "https://github.com/technion-cs-nlp/Trust_me_Im_wrong"}
tags: ['Responsible AI', 'RAG', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) often generate outputs that lack grounding in
real-world facts, a phenomenon known as hallucinations. Prior research has
associated hallucinations with model uncertainty, leveraging this relationship
for hallucination detection and mitigation. In this paper, we challenge the
underlying assumption that all hallucinations are associated with uncertainty.
Using knowledge detection and uncertainty measurement methods, we demonstrate
that models can hallucinate with high certainty even when they have the correct
knowledge. We further show that high-certainty hallucinations are consistent
across models and datasets, distinctive enough to be singled out, and challenge
existing mitigation methods. Our findings reveal an overlooked aspect of
hallucinations, emphasizing the need to understand their origins and improve
mitigation strategies to enhance LLM safety. The code is available at
https://github.com/technion-cs-nlp/Trust_me_Im_wrong .
