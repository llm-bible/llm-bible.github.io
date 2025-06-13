---
layout: publication
title: 'Deprompt: Desensitization And Evaluation Of Personal Identifiable Information In Large Language Model Prompts'
authors: Xiongtao Sun, Gan Liu, Zhipeng He, Hui Li, Xiaoguang Li
conference: "Arxiv"
year: 2024
bibkey: sun2024desensitization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08930"}
tags: ['Fine-Tuning', 'Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Prompt serves as a crucial link in interacting with large language models
(LLMs), widely impacting the accuracy and interpretability of model outputs.
However, acquiring accurate and high-quality responses necessitates precise
prompts, which inevitably pose significant risks of personal identifiable
information (PII) leakage. Therefore, this paper proposes DePrompt, a
desensitization protection and effectiveness evaluation framework for prompt,
enabling users to safely and transparently utilize LLMs. Specifically, by
leveraging large model fine-tuning techniques as the underlying privacy
protection method, we integrate contextual attributes to define privacy types,
achieving high-precision PII entity identification. Additionally, through the
analysis of key features in prompt desensitization scenarios, we devise
adversarial generative desensitization methods that retain important semantic
content while disrupting the link between identifiers and privacy attributes.
Furthermore, we present utility evaluation metrics for prompt to better gauge
and balance privacy and usability. Our framework is adaptable to prompts and
can be extended to text usability-dependent scenarios. Through comparison with
benchmarks and other model methods, experimental evaluations demonstrate that
our desensitized prompt exhibit superior privacy protection utility and model
inference results.
