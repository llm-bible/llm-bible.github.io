---
layout: publication
title: Zero45;resource Hallucination Prevention For Large Language Models
authors: Luo Junyu, Xiao Cao, Ma Fenglong
conference: "Arxiv"
year: 2023
bibkey: luo2023zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02654"}
tags: ['Applications', 'Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture']
---
The prevalent use of large language models (LLMs) in various domains has drawn attention to the issue of hallucination which refers to instances where LLMs generate factually inaccurate or ungrounded information. Existing techniques for hallucination detection in language assistants rely on intricate fuzzy specific free45;language45;based chain of thought (CoT) techniques or parameter45;based methods that suffer from interpretability issues. Additionally the methods that identify hallucinations post45;generation could not prevent their occurrence and suffer from inconsistent performance due to the influence of the instruction format and model style. In this paper we introduce a novel pre45;detection self45;evaluation technique referred to as SELF45;FAMILIARITY which focuses on evaluating the models familiarity with the concepts present in the input instruction and withholding the generation of response in case of unfamiliar concepts. This approach emulates the human ability to refrain from responding to unfamiliar topics thus reducing hallucinations. We validate SELF45;FAMILIARITY across four different large language models demonstrating consistently superior performance compared to existing techniques. Our findings propose a significant shift towards preemptive strategies for hallucination mitigation in LLM assistants promising improvements in reliability applicability and interpretability.
