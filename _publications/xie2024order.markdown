---
layout: publication
title: 'Order Matters In Hallucination: Reasoning Order As Benchmark And Reflexive Prompting For Large-language-models'
authors: Xie Zikai
conference: "Arxiv"
year: 2024
bibkey: xie2024order
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05093"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
'Large language models (LLMs) have generated significant attention since their inception, finding applications across various academic and industrial domains. However, these models often suffer from the hallucination problem, where outputs, though grammatically and logically coherent, lack factual accuracy or are entirely fabricated. A particularly troubling issue discovered and widely discussed recently is the numerical comparison error where multiple LLMs incorrectly infer that 9.11\(>\)9.9. We discovered that the order in which LLMs generate answers and reasoning impacts their consistency. Specifically, results vary significantly when an LLM generates an answer first and then provides the reasoning versus generating the reasoning process first and then the conclusion. Inspired by this, we propose a new benchmark method for assessing LLM consistency: comparing responses generated through these two different approaches. This benchmark effectively identifies instances where LLMs fabricate answers and subsequently generate justifications. Furthermore, we introduce a novel and straightforward prompt strategy designed to mitigate this issue. Experimental results demonstrate that this strategy improves performance across various LLMs compared to direct questioning. This work not only sheds light on a critical flaw in LLMs but also offers a practical solution to enhance their reliability.'
